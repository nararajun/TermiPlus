# TermiPlus

**SSH & 로컬 터미널 클라이언트 for Android**

[![Latest release](https://img.shields.io/github/v/release/nararajun/nararajun?color=2f81f7&label=release)](https://github.com/nararajun/nararajun/releases/latest)
[![Android](https://img.shields.io/badge/Android-7.0%2B-3ddc84)](#설치-방법--installation)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-support-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/nararajun)

안드로이드에서 SSH 서버에 접속해 터미널을 쓰고, 파일을 옮기고, 자주 쓰는 명령을 골라 쓰기 위한 앱입니다.
블루투스·USB·태블릿 커버 같은 **물리 키보드**를 붙여 쓰는 것을 전제로 만들어졌고, **한국어 IME(조합 입력)** 가 터미널 입력에서 깨지지 않도록 처리했습니다.

---

## 다운로드

| 버전 | 파일 | 비고 |
| --- | --- | --- |
| **v1.0.16** (최신) | [TermiPlus_v1.0.16.apk](https://github.com/nararajun/nararajun/releases/latest/download/TermiPlus_v1.0.16.apk) | GitHub Release에서 내려받기 |

- 릴리스 목록: <https://github.com/nararajun/nararajun/releases>
- 요구 사항: **Android 7.0 (API 24) 이상**
- APK 크기: 약 23.5 MB

## 설치 방법 / Installation

1. 위 다운로드 링크를 눌러 `TermiPlus_v1.0.16.apk`를 휴대폰에 저장합니다.
2. 파일을 열면 나오는 안내에 따라 **"알 수 없는 앱 설치"** (출처를 알 수 없는 앱 허용)를 해당 파일 관리자·브라우저에 대해 한 번 허용합니다.
3. 설치 후 실행하면 바로 호스트를 등록하거나 기기 내 로컬 셸을 열 수 있습니다.
4. 이미 이전 버전이 설치되어 있다면 데이터를 그대로 둔 채 업데이트로 설치됩니다.

> Google Play 스토어를 거치지 않고 배포되는 APK입니다. 설치 여부와 시기는 직접 판단하시면 됩니다.

## 주요 기능

- **SSH 접속과 다중 세션** — 탭으로 여러 세션을 오가며 사용, 탭 닫기·재접속 지원
- **호스트 관리** — 라벨·호스트명/IP·포트·계정·태그 저장, 검색, 즐겨찾기, 원탭 접속
- **인증** — 비밀번호와 SSH 키 인증, 앱에서 RSA/Ed25519 키 생성 및 공개키 복사
- **SFTP 파일 탐색기** — 원격 서버의 파일 목록 조회·탐색
- **스니펫(Quick Phrases)** — 자주 쓰는 명령을 저장하고 터미널에서 바로 실행
- **명령 히스토리** — 최근 실행 명령 다시 쓰기, 전체 복사
- **터미널 빠른 접근 바** — 방향키·Esc·Ctrl 등 자주 쓰는 키를 화면에서 바로
- **물리 키보드 지원** — 블루투스·USB·태블릿 커버 키보드, Ctrl+C/Ctrl+V 등 단축키
- **한국어 IME 조합 입력 보호** — Gboard 등에서 한글 조합 중인 글자가 터미널로 새어 나가지 않도록 처리
- **백그라운드 세션 유지** — 다른 앱을 쓰는 동안에도 SSH 연결 유지(포그라운드 서비스), 연결 끊김 감지 시 재접속
- **로컬 안드로이드 셸** — 서버 없이 기기 안의 CLI를 바로 열어 사용
- **화면 설정** — 터미널 테마·글꼴 크기, 인터페이스 언어(한국어·영어·일본어·중국어·스페인어·프랑스어·베트남어)

## 후원 / Support the development

TermiPlus는 무료로 배포되며, 개발은 자발적인 후원으로 이어집니다.
후원은 **강제가 아니라 순수한 응원**이고, 후원 여부와 관계없이 모든 기능을 그대로 쓰실 수 있습니다.

[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nararajun)

- 후원 페이지: <https://ko-fi.com/nararajun> — Ko-fi에서 카드 또는 PayPal로 커피 한 잔 값만큼 보내실 수 있습니다.
- 금액은 정해져 있지 않습니다. 크게 한 번보다 가볍게 자주 응원해 주시는 편이 개발에 훨씬 도움이 됩니다.
- 후원하지 않으셔도 됩니다. 버그 제보나 사용 후기만으로도 큰 도움이 됩니다.

## 소스 코드 / Source

- 소스 코드는 **비공개(private) 저장소**에서 관리하며, 배포는 빌드된 APK로만 이루어집니다.
- 버그 제보·기능 제안은 [Issues](https://github.com/nararajun/nararajun/issues)에 남겨 주세요.

---

## English

**TermiPlus** is an SSH and local terminal client for Android, built for people who type on a **physical keyboard** (Bluetooth, USB, or a tablet cover keyboard) and who need **Korean IME composition** to work properly inside a terminal.

**Download:** [TermiPlus_v1.0.16.apk](https://github.com/nararajun/nararajun/releases/latest/download/TermiPlus_v1.0.16.apk) (Android 7.0+, ~23.5 MB)

**Install:** download the APK on your phone, open it, and allow "install unknown apps" for your browser or file manager when prompted. Installing over an older version keeps your data.

**Features**
- SSH sessions in tabs, host management with tags, search and favorites
- Password and SSH key auth; generate RSA/Ed25519 keys in the app
- SFTP file browser
- Snippets (quick command library) and command history
- Quick access bar for arrows, Esc, Ctrl and other keys
- Physical keyboard shortcuts (Ctrl+C / Ctrl+V and more)
- Korean IME composition protection, so composing text does not leak into the shell
- Background keep-alive for SSH sessions, with reconnect on drop
- On-device Android shell (local CLI)
- Terminal themes, font size, and UI language (English, Korean, Japanese, Chinese, Spanish, French, Vietnamese)

**Support:** TermiPlus is free, and donations are purely voluntary — nothing is locked behind them.

[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nararajun)

You can buy me a coffee on Ko-fi: <https://ko-fi.com/nararajun> (card or PayPal, any amount). Bug reports and feedback are welcome in [Issues](https://github.com/nararajun/nararajun/issues).

**Source:** developed in a private repository; only built APKs are distributed.
