
# PDM 사용 간단 정리

### 1. PDM 설치

```bash
curl -sSL https://pdm-project.org/install-pdm.py | python3 -
```

### 환경변수 설정
```bash
export PATH="$HOME/.local/bin:$PATH"
```

위 내용을 ~/.zshrc 또는 ~/.bashrc에 추가한 뒤 터미널을 재시작하거나

터미널에서 source ~/.zshrc (또는 source ~/.bashrc) 입력해 바로 적용 가능

### 가상환경 생성 및 활성화
```bash
pdm use python3.11
pdm venv activate
```

### 코드 실행 
```bash
python src/discordbot/discord_bot_back.py
```

### 📌 Discord 출석체크봇
### ⏰ 기간: 2025.03.10 ~ 2025.03.19
### 🛠 기술 스택: Python
### 👥 인원: 1명

### 🔍 프로젝트 개요
매일 반복되는 퇴실 확인 업무의 효율화를 위해, 간단한 키워드 입력만으로 수강생의 퇴실 여부를 확인할 수 있는 Discord 봇을 개발했습니다.
복잡한 로그인과 수십 회의 클릭, 입력 과정을 대체하여 사용자 편의성과 관리 효율성을 높였습니다.

### 🎯 주요 기능
Discord 명령어 기반 퇴실 확인

키워드 입력만으로 퇴실 상태 간편 조회

PM 등 외부 외출 시에도 어디서든 확인 가능

### ✅ 프로젝트 성과
업무 시간 단축:
기존 수작업 대비 초단위로 업무 완료 가능, 반복적인 클릭 및 입력 작업 제거

데이터 접근성 향상:
장소에 구애받지 않고 실시간으로 출결 정보 확인 가능, 프로세스 간소화

