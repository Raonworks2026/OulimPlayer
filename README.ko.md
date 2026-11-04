# Oulim Player

**내 영상을 모든 기기에서.**

휴대폰 속 영상, NAS에 있는 영화, PC에 모아 둔 시리즈까지. 휴대폰 · 태블릿 · TV · 데스크탑에서 앱 하나로 재생해요.

이 저장소는 Oulim Player의 **Windows · macOS 설치 파일**을 내려받는 곳이에요. 소스 코드는 없어요.

[English](README.md)

## 내려받기

| 플랫폼 | 파일 | |
|---|---|---|
| Windows 10 / 11 (64비트) | `OulimPlayer-windows-x64.msi` | 곧 출시 |
| macOS | `OulimPlayer-macos.dmg` | 곧 출시 |

모든 판과 바뀐 점은 [Releases](https://github.com/Raonworks2026/OulimPlayer/releases)에서 볼 수 있어요.

휴대폰 · 태블릿 · TV용 Oulim Player는 여기가 아니라 앱 스토어(Google Play · App Store)에서 받아요.

## 이런 걸 해요

- **거의 모든 형식 재생** — 먼저 기기에 내장된 디코더로 재생하고, 안 되면 FFmpeg로 자동 전환해 보던 장면부터 이어서 보여 줘요.
- **라이브러리를 한곳에** — 이 PC · NAS · 다른 PC에 있는 영상을 영화 · 시리즈 · 음악으로 정리하고, 포스터와 이어보기까지 보여 줘요.
- **NAS 바로 재생** — SMB · SFTP · WebDAV · DLNA로 연결해, 다운로드나 변환 없이 바로 재생해요.
- **PC를 NAS처럼** — Oulim Player를 켜 두면 휴대폰 · TV에서 이 PC의 영상을 볼 수 있어요. 집 밖에서도 중계 서버 없이 연결돼요.
- **기록은 내 기기에만** — 시청 기록 · 이어보기 위치 · NAS 비밀번호는 이 기기에만 남아요. 계정도 클라우드도 사용 통계도 없어요.

## 설치

### Windows

1. `OulimPlayer-windows-x64.msi`를 받아 실행해요.
2. **'Windows의 PC 보호'** 창이 뜨면 **추가 정보 → 실행**을 눌러요.
   아직 코드 서명을 하지 않은 설치 파일이라 SmartScreen이 알아보지 못해서 그래요.
3. 처음 켜면 라이브러리에 넣을 폴더를 골라요. 휴대폰 · TV에서 이 PC의 영상을 보려면 미디어 서버를 켜고, Windows 방화벽 창이 뜨면 **개인 네트워크**를 허용해요.

### macOS

곧 출시해요.

### 업데이트

데스크탑용 Oulim Player는 하루에 한 번 최신 버전 번호만 확인해요. 기기 정보는 보내지 않아요. 새 판이 있으면 여기 Release로 가는 링크를 보여 주고, 스스로 설치하지는 않아요. **설정 › 개인정보 · 잠금 › 새 버전 자동 확인**에서 끌 수 있어요.

## 무료 · Pro

Oulim Player는 무료로 쓸 수 있어요. Pro에 들어 있는 기능은 홈페이지에서 볼 수 있어요.
Pro는 플랫폼마다 따로 구매해요. PC에 등록한 휴대폰 · 태블릿 · TV가 Pro라면 그 PC에서도 Pro를 이어받을 수 있어요.

## 문의 · 문제 신고

- **문제가 생겼나요?** 앱에서 **설정 › 정보 · Pro › 도움말 › 문제 신고**를 열어요. 보낼 내용을 먼저 그대로 보여 드리고, '보내기'를 누르기 전에는 아무것도 보내지 않아요.

## 오픈소스

Oulim Player는 LGPL v2.1로 [FFmpeg](https://ffmpeg.org)를 써요. 판마다 Release에 `ffmpeg-<판>-source.tar.xz`(우리가 쓴 FFmpeg 소스와 빌드 설정)를 함께 올려요. 전체 오픈소스 라이선스는 앱의 **설정 › 정보 · Pro › 오픈소스 라이선스**에서 볼 수 있어요.

---

© 2026 Raonworks
