# dz

[홈페이지 / Website](https://dolzip.github.io) · [다운로드 / Download](https://github.com/dolzip/dz/releases/download/v0.1.0/dz-0.1.0.pkg) · [지원 / Issues](https://github.com/dolzip/dz/issues/new/choose)

## 한국어

목록 보기·압축 풀기·만들기·검사·편집을 지원하는 무료 명령줄 도구입니다. PKG를 열어 설치하면 `/usr/local/bin/dz`를 사용할 수 있습니다. Homebrew 배포는 추후 제공 예정입니다.

요구 환경: **macOS 11 이상 · Apple Silicon 및 Intel**. 암호화 AEA는 macOS 11.3 이상이 필요합니다.

이 Preview는 Developer ID 서명·공증이 없습니다. 처음 실행 또는 설치가 차단되면 시스템 설정 → 개인정보 보호 및 보안 → 그래도 열기를 선택하세요. macOS 11–12에서는 시스템 환경설정 → 보안 및 개인 정보 보호 → 일반을 사용합니다.

## English

A free command-line tool for listing, extracting, creating, testing and editing archives. Open the PKG to install `/usr/local/bin/dz`. Homebrew distribution is planned for later.

Requirements: **macOS 11+ · Apple Silicon and Intel**. Encrypted AEA requires macOS 11.3+.

This preview is not Developer ID signed or notarized. If the first launch or installation is blocked, use System Settings → Privacy & Security → Open Anyway. On macOS 11–12, use System Preferences → Security & Privacy → General.

## 사용 예 / Examples

```sh
dz --help
dz l archive.zip
dz x archive.zip
dz t archive.zip
```

## 삭제 / Uninstall

```sh
sudo rm /usr/local/bin/dz && sudo pkgutil --forget com.dolzip.dz
```

공유 라이브러리는 `/usr/local/lib/dz`에 남을 수 있습니다. / Supporting libraries may remain in `/usr/local/lib/dz`.

## 라이선스 / License

[무료 바이너리 EULA / Free binary EULA](LICENSE). 이 저장소에는 제품 소스가 없습니다. / This repository contains no product source code.

Copyright © 2026 Dolzip
