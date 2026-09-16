# 🎲 Dice Mini Games

> HTML5, CSS3, JavaScript로 만든 재미있는 주사위 미니게임 모음

[![GitHub](https://img.shields.io/badge/GitHub-eric8966%2Fminigame-blue?logo=github)](https://github.com/eric8966/minigame)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)](https://www.javascript.com)

## 📌 소개

주사위를 활용한 두 가지 재미있는 미니게임을 제공합니다. 순수 바닐라 JavaScript로 개발되어 외부 라이브러리 없이 빠르고 가볍게 실행됩니다.

**[🌐 온라인에서 바로 플레이하기](https://eric8966.github.io/minigame/)** ← 클릭!

---

## 🎮 게임 소개

### 1️⃣ Dice Simulator (주사위 시뮬레이터)

두 개의 주사위를 굴려 결과를 추적하는 시뮬레이터입니다.

#### 기능
- 🎲 **두 개의 주사위 동시 굴리기** - 부드러운 회전 애니메이션
- 📊 **실시간 합계 계산** - 각 주사위 값과 합계 표시
- 📈 **통계 추적** - 굴린 횟수와 평균값 계산
- 🔄 **히스토리 관리** - 지난 굴림 결과 저장 및 표시
- 🎨 **반응형 디자인** - 모바일/태블릿 완벽 지원

#### 스크린샷
```
┌─────────────────────────┐
│   🎲 주사위 시뮬레이터   │
│                         │
│    [4]      [6]        │
│                         │
│   합계: 10              │
│  주사위 굴리기  초기화   │
│                         │
│ 기록: 10 | 7 | 12 | ... │
│ 총 횟수: 42  평균: 7.2  │
└─────────────────────────┘
```

---

### 2️⃣ Higher or Lower (높낮이 게임)

다음 주사위의 값을 예측하는 전략 게임입니다.

#### 게임 규칙
1. 🎲 첫 번째 주사위가 굴려집니다
2. 🤔 다음 주사위가 **높을지(Higher) / 낮을지(Lower) / 같을지(Same)** 선택
3. ✅ 정답을 맞추면 점수 획득
4. 🔥 연쇄 성공할수록 점수 배수 증가 (1연=1점, 2연=2점, 최대 6배)
5. ❌ 틀리면 게임 오버

#### 특징
- 🎯 **예측 기반 게임플레이** - 전략적 사고 필요
- 📈 **배수 시스템** - 연쇄 성공으로 점수 급증
- 🏆 **통계 기록** - 최종 점수와 연쇄 기록 저장
- ⚡ **빠른 게임 진행** - 쉽지만 중독성 높음

#### 스크린샷
```
┌──────────────────────────┐
│  🎯 Higher or Lower      │
│                          │
│  점수: 24    연쇄: 4    │
│                          │
│   현재: [5]  다음: [?]  │
│  다음이 높을까요?       │
│                          │
│ [낮을까] [같을까] [높을까]│
│                          │
│ ✓ 정답! +4점 [4배]      │
└──────────────────────────┘
```

---

## 🚀 빠른 시작

### 온라인에서 플레이
GitHub Pages를 통해 바로 플레이할 수 있습니다!

👉 **[게임 플레이하기](https://eric8966.github.io/minigame/)**

### 로컬에서 실행
```bash
# 저장소 클론
git clone https://github.com/eric8966/minigame.git
cd minigame

# 브라우저에서 열기 (Windows)
start index.html

# 또는 Live Server 사용 (VS Code)
# VS Code에서 Live Server 확장 프로그램 설치 후
# index.html에서 우클릭 → "Open with Live Server"
```

---

## 📁 파일 구조

```
minigame/
├── index.html              # 🏠 홈페이지 - 게임 선택 화면
├── dice_simulator.html     # 🎲 주사위 시뮬레이터 게임
├── higher_or_lower.html    # 🎯 Higher or Lower 게임
└── README.md               # 📖 이 파일
```

---

## 🛠️ 기술 스택

| 기술 | 설명 |
|------|------|
| **HTML5** | 시맨틱 마크업 |
| **CSS3** | Flexbox, Grid, 애니메이션 |
| **JavaScript (ES6+)** | 순수 바닐라 JS, 외부 라이브러리 없음 |
| **반응형 디자인** | 모든 디바이스 지원 |
| **Dark Mode** | `prefers-color-scheme` 지원 |

### 주요 특징
- ✅ **외부 라이브러리 없음** - 순수 HTML/CSS/JS만 사용
- ⚡ **빠른 로딩** - 용량 작고 가벼움
- 🎨 **라이트/다크 모드** - 자동 지원
- 📱 **완벽한 반응형** - 모든 화면 크기 지원
- ♿ **접근성 고려** - 시맨틱 HTML

---

## 💡 사용 예시

### Dice Simulator
1. "주사위 굴리기" 버튼 클릭
2. 두 개의 주사위가 회전하면서 랜덤 값 생성
3. 합계와 기록이 자동으로 업데이트
4. 평균값으로 운의 흐름 분석

### Higher or Lower
1. "게임 시작" 클릭 → 첫 주사위 표시
2. 다음 주사위가 높을지/낮을지/같을지 선택
3. 정답 시 연쇄 성공 증가 및 점수 획득
4. 오답 시 게임 오버 → 최종 성과 표시

---

## 🎯 게임 전략

### Higher or Lower 게임 팁
- 🎲 **확률 이용** - 3, 4는 높고 낮을 확률이 높음
- 🔄 **패턴 분석** - 연속된 높은 수는 낮을 확률 높음
- ⏸️ **멈출 타이밍** - 5연 이상은 매우 위험함
- 🎯 **목표 설정** - 처음엔 3-4연쇄를 노리기

---

## 📊 통계 및 분석

### Dice Simulator
- 주사위 2개 합계 범위: 2 ~ 12
- 평균값: 약 7
- 가장 확률 높은 값: 7
- 게임 시간: 5-10분

### Higher or Lower
- 난이도: 중상
- 평균 연쇄: 2-3회
- 최고 점수: 36점 (6연쇄)
- 게임 시간: 1-3분

---

## 🎨 디자인 특징

- **그래디언트 배경** - 현대적인 퍼플/블루 그래디언트
- **카드 레이아웃** - 깔끔하고 구조적인 UI
- **부드러운 애니메이션** - 주사위 회전 효과
- **다크 모드 지원** - 눈이 편한 다크 테마
- **반응형 그리드** - 모바일/태블릿/데스크톱 최적화

---

## 📈 향후 계획

- [ ] 멀티플레이 모드 (두 플레이어 경쟁)
- [ ] 랭킹 시스템 (로컬 스토리지 저장)
- [ ] 다양한 게임 모드 추가
- [ ] PWA 지원 (오프라인 플레이)
- [ ] 게임 음향 효과 추가
- [ ] 성과 배지 시스템

---

## 🤝 기여하기

버그 리포트나 기능 제안은 언제든 환영합니다!

1. 이 저장소를 Fork하기
2. 새 브랜치 생성 (`git checkout -b feature/amazing-feature`)
3. 변경사항 커밋 (`git commit -m 'Add amazing feature'`)
4. 브랜치에 Push (`git push origin feature/amazing-feature`)
5. Pull Request 생성

---

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에서 공개됩니다.
자유롭게 수정, 배포, 상용화할 수 있습니다.

---

## 👤 저자

**Eric8966**
- 🐙 GitHub: [@eric8966](https://github.com/eric8966)
- 💻 Email: nextad11@s2b.ai.kr

---

## 🙏 감사의 말

이 프로젝트는 순수 바닐라 JavaScript로 개발되었습니다.

---

## 📞 피드백 및 문의

- 🐛 **버그 리포트**: [Issues](https://github.com/eric8966/minigame/issues) 페이지
- 💬 **기능 제안**: Discussion 또는 Issue 생성
- ⭐ **마음에 들면**: Star를 눌러주세요!

---

<div align="center">

**[🌐 온라인에서 게임 플레이하기](https://eric8966.github.io/minigame/)**

Made with ❤️ using HTML5, CSS3 & JavaScript

![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</div>