<div align="center">

# MyLauncher

RPG 모드 서버용 마인크래프트 런처 · Minecraft 1.20.1 · Forge

<br>

<a href="https://github.com/kindeo8989/mylauncher-releases/releases/latest/download/MyLauncher-Web-Tauri-Setup.exe">
  <img src="https://img.shields.io/badge/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C-Windows%20%EC%84%A4%EC%B9%98%20%ED%8C%8C%EC%9D%BC-e3b258?style=for-the-badge&logo=windows&logoColor=white" alt="다운로드 - Windows 설치 파일" height="56">
</a>

<br><br>

<a href="https://github.com/kindeo8989/mylauncher-releases/releases/latest">
  <img src="https://img.shields.io/github/v/release/kindeo8989/mylauncher-releases?label=%EC%B5%9C%EC%8B%A0%20%EB%B2%84%EC%A0%84&style=flat-square" alt="최신 버전">
</a>

버튼이 안 보이면 → **[MyLauncher-Web-Tauri-Setup.exe 받기](https://github.com/kindeo8989/mylauncher-releases/releases/latest/download/MyLauncher-Web-Tauri-Setup.exe)**

</div>

---

## 설치

1. 위 버튼을 눌러 `MyLauncher-Web-Tauri-Setup.exe`를 받아 실행해요.
2. Windows 파란 경고 창이 뜨면 **추가 정보 → 실행**을 눌러요. (설치 파일에 Windows 코드 서명이 아직 없어서 나오는 경고예요. 파일이 진짜인지는 런처가 자체 서명으로 따로 확인해요.)
3. 설치가 끝나면 런처가 켜져요. 마이크로소프트 계정으로 로그인하고 **플레이**를 누르면 게임과 모드를 알아서 받아요.

옛 Electron판(MyLauncher-Web)을 쓰고 있다면 새 설치 파일을 실행하면 옛 버전을 알아서 정리하고 옮겨 와요. 게임 폴더와 설정, 로그인은 그대로예요.

## 업데이트

이미 설치했다면 따로 받을 필요가 없어요. **런처를 껐다가 다시 켜면** 새 버전을 확인해서 자동으로 설치해요. 업데이트 정보는 서명된 목록으로 확인하고, GitHub가 잠깐 불안정하면 예비 서버로 받아요.

## 릴리스 페이지의 파일들

[릴리스 페이지](https://github.com/kindeo8989/mylauncher-releases/releases)에는 파일이 여러 개 있어요. **받을 것은 `MyLauncher-Web-Tauri-Setup.exe` 하나뿐**이에요.

| 파일 | 하는 일 |
|---|---|
| `MyLauncher-Web-Tauri-Setup.exe` | 설치 파일 (이것만 받으면 돼요) |
| `MyLauncher-Web-Tauri-Setup.exe.sig` | 설치 파일이 진짜인지 런처가 확인할 때 써요 |
| `MyLauncher-Web-Setup.exe`, `.sig`, `latest.yml` | 옛 Electron판 런처 사용자를 새 런처로 옮길 때만 써요. 같은 설치 파일이에요 |
| `changelog.json` | 런처의 패치노트 화면에 보여 줄 내용이에요 |
| Source code (zip / tar.gz) | GitHub가 자동으로 붙이는 파일이에요. 받지 않아도 돼요 |

`update-manifest`라는 이름의 릴리스는 런처가 새 버전을 확인할 때 읽는 서명된 목록(`latest.json`)과 원격 설정(`config.json`)을 담고 있어요. 설치 파일이 아니에요.

## 문제가 생기면

런처의 **로그** 화면을 캡처해서 알려 주세요. (이메일이 보이면 가려 주세요.) 게임이 튕기면 홈의 안내에서 오류 보고서를 만들 수 있어요.
