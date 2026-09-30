# Android Debugger — Downloads

Android Debugger의 공식 설치 파일과 업데이트 배포 저장소입니다.

[최신 Windows 설치 파일 받기](https://github.com/junha8959/android-debugger-releases/releases/latest)

## Windows

1. 최신 릴리스의 `Android-Debugger-<버전>-windows-x64-setup.exe`를 내려받습니다.
2. 실행 중인 Android Debugger를 종료하고 설치합니다.
3. 시작 메뉴에서 실행합니다. 0.45.0부터 **설정 → 앱 업데이트**에서 새 버전 확인, 다운로드, 재시작 설치를 사용할 수 있습니다.

새 버전은 앱 실행 중 자동으로 확인하며 설정에서 끌 수 있습니다. 다운로드와 설치는 각각 직접 선택합니다. 설치 전 기록과 설정은 해당 컴퓨터의 사용자 데이터 폴더 아래 `update-backups`에 백업합니다. 기존 0.44.3 이하는 이 기능이 없어 처음 한 번 직접 설치해야 합니다.

Windows x64용입니다. 기기 연결에는 ADB가 필요하며 네트워크·DB 등 앱 내부 검사에는 Android Debugger SDK 연동이 필요합니다. Windows 설치 파일은 아직 게시자 인증서로 서명하지 않았으므로 운영체제의 확인 안내가 표시될 수 있습니다.

## 배포 범위

이 저장소에는 설치 파일, 업데이트 메타데이터, 변경 안내, 체크섬을 제공합니다. 소스 저장소는 별도로 비공개 운영합니다. 이 저장소의 자동 생성된 “Source code” ZIP은 다운로드 안내 문서만 포함하며 앱 소스 배포물이 아닙니다.

`SHA256SUMS.txt`로 파일 손상 여부를 확인할 수 있습니다. 업데이트 기능은 다운로드한 설치 파일의 SHA-512를 검사합니다. Mac 설치 파일과 Mac 자동 업데이트는 현재 이 공개 채널에서 제공하지 않습니다.
