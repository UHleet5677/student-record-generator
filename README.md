# 🎓 중고등학생 학교생활기록부(생기부) 작성 도우미

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FUHleet5677%2Fstudent-record-generator)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen)](https://uhleet5677.github.io/student-record-generator/)

학생의 **학번**, **이름**, 그리고 **관찰 키워드**를 입력하면 교육부 훈령 및 NEIS 규격에 부합하는 **한글 300~400자 내외**의 맞춤형 생기부 문안을 즉시 생성해 주는 프로그램입니다.

---

## 📌 주요 특징 및 기능

1. **학번, 이름, 키워드 기반 즉시 생성**
   - 학생별 개별 관찰 키워드(예: `문학적 비평 능력`, `논리적 사고 능력`, `비판적 읽기 역량`, `사회 현상 다각적 고찰`)를 입력하면 자연스러운 완성형 문장으로 자동 합성합니다.
   - 한국어 자연어 조사(`은/는`, `이/가`, `을/를`, `과/와`, `으로/로`)를 문맥과 받침에 맞춰 자동으로 완벽하게 부착합니다.

2. **300~400자 정밀 분량 제어 & NEIS 바이트 계산기**
   - 공백 포함 글자 수, 공백 제외 글자 수, NEIS 기준 바이트(한글 3Byte, 영숫자 1Byte, 줄바꿈 2Byte)를 실시간으로 측정합니다.
   - 글자 수가 300~400자 황금 범위에 도달하면 초록색 `🎯 최적 분량` 배지가 표시됩니다.

3. **중고등학교 생기부 전 영역 지원**
   - **과목별 세부능력 및 특기사항 (세특)**
   - **행동특성 및 종합의견 (행특)**
   - **진로활동 (창체)**
   - **동아리활동 (창체)**
   - **자율활동 (창체)**

4. **100% 무설치 / 오프라인 실행 지원**
   - 파이썬이나 별도 프로그램 설치 없이, 웹 브라우저(크롬, 엣지 등)만 있으면 바로 더블 클릭으로 실행됩니다.
   - 내장된 자연어 합성 엔진으로 인터넷이 연결되지 않은 환경에서도 무제한 무료로 사용할 수 있습니다.
   - (선택 사항) Google Gemini API 키를 입력하면 최신 초거대 AI 기반의 심화 문장 생성 모드로도 전환할 수 있습니다.

5. **교사업무 편의 기능**
   - **NEIS 원클릭 복사**: 복사 버튼 한 번으로 NEIS 나이스 생활기록부 입력창에 바로 붙여넣기(Ctrl+V) 가능
   - **문장 미세 조절**: 다른 표현으로 재생성, +35자 문장 보강, -35자 축약 정리
   - **학생 명단 관리 & 엑셀(CSV) 내보내기**: 여러 학생의 생기부를 차례대로 작성하고 엑셀 파일(.csv) 또는 텍스트(.txt)로 일괄 저장

---

## 🚀 실행 방법

### 방법 1 (가장 간편한 방법)
폴더 내의 **`실행하기.bat`** 파일을 더블 클릭합니다.

### 방법 2
**`index.html`** 파일을 더블 클릭하여 크롬(Chrome) 또는 엣지(Edge) 브라우저에서 엽니다.

---

## 📂 파일 위치
- 프로그램 위치: `C:\Users\USER\.gemini\antigravity\scratch\student-record-generator\`
- 메인 파일: [index.html](file:///C:/Users/USER/.gemini/antigravity/scratch/student-record-generator/index.html)
- 런처: [실행하기.bat](file:///C:/Users/USER/.gemini/antigravity/scratch/student-record-generator/실행하기.bat)
