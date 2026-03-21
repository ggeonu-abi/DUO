# 🛡️ 디아블로 2: 레저렉션 공역 & 우버디아 트래커 (D2R Tracker)

디아블로 2: 레저렉션 플레이 중 **다음 공역(Terror Zone)** 정보와 **우버디아(Diablo Clone)** 의 각 서버별 진행 상황을 게임 화면 위에 실시간으로 표시해 주는 투명 오버레이 프로그램입니다.

---

## ✨ 주요 기능

* **실시간 공역 알림:** 매시 정각 및 30분마다 업데이트되는 다음 공역 정보를 한글로 표시합니다. (ACT 정보 포함)
* **우버디아 프로그레스 바:** 아시아, 유럽, 아메리카 서버의 진행도를 6단계(`■■■□□□`) 바 형태로 우측 하단에 표시합니다.
* **스마트 타이머:** 서버 부하를 방지하기 위해 정각/30분 5초 뒤에 데이터를 갱신하며, 유동적인 요청 주기를 유지합니다.
* **완벽한 게임 통합:** 투명 창 모드로 작동하며, 마우스 클릭이 오버레이를 통과하므로 게임 플레이에 전혀 지장을 주지 않습니다.
* **개인 설정 저장:** 래더/스탠, 하드코어/소프트코어 설정 및 우버디아 표시 여부 등 설정값이 `d2_overlay_config.json`에 자동 저장됩니다.

---

## 🚀 시작하기

### 1. 실행 파일 다운로드
* 제공된 `d2_tz_tracker.exe` 파일을 다운로드합니다. (또는 개발자 블로그 방문)

### 2. 사용 방법
1.  **디아블로 2: 레저렉션**을 실행합니다. (창 모드 또는 전체 화면 창 모드 권장)
2.  다운로드한 `d2_tz_tracker.exe`를 실행합니다.
3.  화면 우측 상단에는 **다음 공역** 정보가, 우측 하단에는 **우버디아 진행도**가 나타납니다.

### 3. 단축키 및 메뉴 설정
* **프로그램 완전 종료:** `Ctrl` + `Shift` + `Q`
* **환경설정:** 작업 표시줄(시스템 트레이)의 빨간 아이콘을 **마우스 우클릭**하여 모드 변경(래더/스탠, 하코/소코) 및 우버 표시 ON/OFF를 설정할 수 있습니다.

---

## 🛡️ 보안 및 백신 오탐지 안내 (Security)

본 프로그램은 파이썬(Python) 기반으로 제작되었으며, 키보드 단축키 감지를 위해 `keyboard` 라이브러리를 사용합니다. 이 과정에서 일부 백신 프로그램(Windows Defender 등)이 **오탐지**(False Positive)하여 실행을 차단하거나 파일을 삭제할 수 있습니다.

* **해결 방법:** 실행이 되지 않을 경우, 프로그램이 위치한 폴더를 **백신 검사 제외 대상**으로 등록한 후 다시 실행해 주시기 바랍니다.
* 본 프로그램은 오픈 소스 기반의 안전한 도구이며, 어떠한 개인 정보도 수집하지 않습니다.

---

## ⚠️ 면책 조항 (Disclaimer)

* 본 프로그램은 Blizzard Entertainment와 무관하며, 게임 데이터를 직접 수정하거나 조작하지 않는 **순수 오버레이 정보 표시 도구**입니다.
* 프로그램 사용으로 인해 발생하는 모든 책임은 사용자 본인에게 있으며, 제작자는 어떠한 결과에 대해서도 책임을 지지 않습니다.
* 데이터 제공처(D2Runewizard)의 상황에 따라 정보 표시가 지연되거나 부정확할 수 있습니다.

---

## ☕ 후원하기 (Support)
이 프로그램이 마음에 드셨다면, 개발자가 더 좋은 기능을 만들 수 있도록 커피 한 잔의 여유를 선물해 주세요! 

* [커피 한 잔 후원하기](https://www.buymeacoffee.com/본인아이디)

---

## 📢 채널 및 문의

* **공식 블로그:** [Life Money Hub](https://lifemoneyhub.com)
* **네이버 카페:** [스마트 라이프], [늦깎이 경제 교실]

---


<a href="https://lifemoneyhub.com">d2_tz_tracker</a> © 2026 by <a href="https://lifemoneyhub.com">ggeonu-abi</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0</a>
<img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
<img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
<img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
<img src="https://mirrors.creativecommons.org/presskit/icons/nd.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

**Credits:** Data provided by [D2Runewizard](https://d2runewizard.com)