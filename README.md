# 📊 Market Journal

> 매일의 시장 흐름을 기록하고, Claude AI로 인사이트를 얻는 개인 마켓 저널

**GitHub Pages로 무료 호스팅 + GitHub Gist에 데이터 저장**

---

## 🚀 설치 (5분)

### 1. GitHub 레포지토리 생성
```
레포 이름: market-journal  (또는 원하는 이름)
Public 또는 Private 둘 다 가능
```

### 2. 파일 업로드
`index.html` 파일을 레포에 올리세요.

```bash
git clone https://github.com/YOUR_USERNAME/market-journal
cd market-journal
# index.html 복사 후
git add index.html
git commit -m "init: market journal"
git push
```

### 3. GitHub Pages 활성화
```
레포 → Settings → Pages
Source: Deploy from a branch
Branch: main / root
```
몇 분 후 → `https://YOUR_USERNAME.github.io/market-journal` 접속 가능

### 4. API 키 설정 (앱 내)
앱 우측 상단 `⚙ SETTINGS` 클릭:

| 항목 | 발급처 | 권한 |
|------|--------|------|
| GitHub Token | Settings → Developer settings → PAT (classic) | `gist` ✓ |
| Gist ID | 첫 저장 시 자동 생성 — 비워두기 | — |
| Claude API Key | console.anthropic.com | — |

---

## 📋 기능

| 기능 | 설명 |
|------|------|
| **4섹션 저널** | 마켓 오버뷰 / 주식·종목 / 산업·섹터 / 요주의 와치리스트 |
| **FREE MEMO** | 글자 제한 없는 자유 메모 |
| **태그** | #market #stock #industry #macro |
| **AI 요약** | Claude API로 핵심 인사이트 자동 생성 |
| **커스텀 AI 질문** | 원하는 질문을 직접 입력 |
| **Gist 동기화** | GitHub Gist에 자동 백업 / 다른 기기에서 불러오기 |
| **단축키** | `Ctrl+S` 저장, `Ctrl+N` 새 항목 |

---

## 💾 데이터 저장 방식

```
브라우저 로컬 스토리지 (기본)
       ↓ 저장 버튼
GitHub Gist (자동 백업)
       ↓ 다른 기기
GitHub Gist에서 불러오기
```

데이터는 `market-journal.json`으로 Gist에 **비공개** 저장됩니다.

---

## 🔒 보안 주의

- GitHub Token과 Claude API Key는 **브라우저 로컬 스토리지**에만 저장됩니다.
- GitHub Pages는 HTTPS이므로 안전합니다.
- Private Gist로 저장되어 본인만 볼 수 있습니다.
- API 키를 코드에 하드코딩하지 마세요.

---

## 📁 파일 구조

```
market-journal/
└── index.html   ← 전체 앱 (단일 파일)
└── README.md    ← 이 파일
```

---

Made with ♥ using Claude AI
