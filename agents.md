# 🤖 AI 에이전트 설정 파일

이 파일은 AI 어시스턴트(Claude, Antigravity 등)가 이 프로젝트를 도울 때 참고하는 설정입니다.

---

## 🖥️ 환경 정보

- **OS**: Windows
- **Shell**: PowerShell (cmd도 사용 가능)
- **에디터**: VS Code + Obsidian

### ⚠️ PowerShell 명령어 주의사항

```powershell
# ❌ 리눅스/맥 방식 (PowerShell에서 안 됨)
git add . && git commit -m "message"

# ✅ PowerShell 방식 (세미콜론으로 구분)
git add .; git commit -m "message"; git push origin main

# ✅ 또는 줄 나눠서
git add .
git commit -m "message"
git push origin main
```

---

## 📁 프로젝트 구조

```
c:\study\일본어\
├── Week1-2-계획.md        # 주간 학습 계획
├── Daily-Logs\             # 날짜별 학습 로그
│   ├── YYYY-MM-DD-DayN.md
│   └── 로그-템플릿.md
├── Vocabulary\             # 어휘 단어장
│   ├── Day1-가족-직업-30개.md
│   ├── Day3-4-단어장.md
│   └── Day5-동사-30개.md
├── Grammar\                # 문법 자료
├── Resources\              # 참고 자료
├── agents.md               # ← 이 파일 (AI 설정)
├── .claude.md              # Claude용 설정 (agents.md 참조)
└── claude.md               # 일반 참조용 (agents.md 참조)
```

---

## 🎯 학습 목표

- **목표**: JPT 400점 달성
- **기간**: 2026-02-11 ~ 2026-02-24 (Week 1-2)
- **현재 진도**: Day 5 완료 + 복습 세션 진행 중

---

## 📌 AI 작업 규칙

### 어휘/문법 표기 규칙
- 한자에는 **반드시 읽는 법(히라가나)을 병기**: `書(か)く` 형식
- 어휘 파일에는 **한국어 발음**도 함께 표기
- 예: `食(た)べます` (타베마스) - 먹습니다

### 학습 세션 진행 방식
- 사용자는 **히라가나/가타카나를 읽을 수 있음** (로마자 표기 불필요)
- 한자는 읽는 법 모를 수 있으므로 **히라가나 병기 필수**
- 답변은 **한국어**로, 일본어는 **히라가나+한자(よみかた)** 형식으로

### 파일 저장 규칙
- Daily Log: `Daily-Logs/YYYY-MM-DD-DayN.md`
- 복습 세션: `Daily-Logs/YYYY-MM-DD-복습.md`
- 어휘 파일: `Vocabulary/DayN-주제-30개.md`

### Git 작업
- **항상 PowerShell 문법** 사용
- 브랜치: `main`
- 커밋 메시지: 한국어 또는 영어 모두 OK

---

## 🗓️ 학습 진도 현황

| Day | 날짜 | 주제 | 상태 |
|-----|------|------|------|
| Day 1 | 2026-02-14 | は/が + 가족/직업 어휘 | ✅ |
| Day 2 | 2026-02-15 | を/に/で 조사 + 동사 | ✅ |
| Day 3 | 2026-02-18 | へ/と/から/まで | ✅ |
| Day 4 | 2026-02-18 | です/でした/じゃありません | ✅ |
| Day 5 | 2026-02-19 | ます형 4가지 활용 | ✅ |
| 복습 | 2026-03-05 | Day1~5 복습 + JPT400 표현 | ✅ |
| Day 6 | - | ます형 심화 + い형용사 | ⬜ |
