# PK Proxy Manager 다운로드

PK Proxy Manager는 이제 소스 코드와 설치 파일을 같은 공개 저장소에서 배포합니다. 이 저장소에는 새 설치 파일을 게시하지 않습니다.

최신 설치 파일: [PK Proxy Manager Releases](https://github.com/gogiari/pk-rs/releases/latest)

| 운영체제 | 설치 파일 | 업데이트 방법 |
| --- | --- | --- |
| Windows x64 | `*_windows-x64-setup.exe` | 새 설치 파일을 실행합니다. |
| macOS Intel·Apple Silicon | `*_macos-universal.pkg` | `pk stop` 후 새 패키지를 설치합니다. |
| Ubuntu·Debian x64 | `*.deb` | `sudo apt install ./파일명.deb` |
| Fedora·RHEL x64 | `*.rpm` | `sudo dnf install ./파일명.rpm` |
| Alpine x64 | `*.apk` | `sudo apk add --allow-untrusted ./파일명.apk` |
| Arch x64 | `*.pkg.tar.zst` | `sudo pacman -U ./파일명.pkg.tar.zst` |
| 기타 Linux x64 | `*.tar.gz` | `pk stop` 후 압축을 풀어 `./install.sh` 실행 |

새 버전을 설치해도 개인 설정은 유지됩니다. 각 릴리스의 `SHA256SUMS`로 파일 무결성을 확인할 수 있습니다. macOS 설치 파일은 아직 서명·공증되지 않았습니다.
