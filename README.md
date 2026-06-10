# 아기 케어 트래커 — 설치 가이드

## 파일 구성
```
baby-care-tracker/
├── index.html      ← 앱 본체
├── manifest.json   ← PWA 설정
├── sw.js           ← 오프라인 캐시
├── icon-192.png    ← 앱 아이콘 (직접 추가)
└── icon-512.png    ← 앱 아이콘 (직접 추가)
```

---

## 🚀 무료 배포 방법 (GitHub Pages 추천)

### 1단계 — GitHub 계정 만들기
https://github.com 에서 무료 가입

### 2단계 — 새 저장소 만들기
- [New repository] 클릭
- Repository name: `baby-care-tracker`
- Public 선택
- [Create repository] 클릭

### 3단계 — 파일 업로드
- [uploading an existing file] 클릭
- index.html, manifest.json, sw.js 드래그 앤 드롭
- [Commit changes] 클릭

### 4단계 — GitHub Pages 활성화
- 저장소 → Settings → Pages
- Source: Deploy from a branch
- Branch: main / root 선택
- Save

### 5단계 — 앱 주소 확인
약 1~2분 후 아래 주소로 접속 가능:
`https://[내 깃헙 아이디].github.io/baby-care-tracker/`

---

## 📱 스마트폰에 설치하기

### Android (크롬)
1. 위 주소를 크롬으로 열기
2. 주소창 오른쪽 ⋮ 메뉴 → [홈 화면에 추가]
3. 앱 이름 확인 후 [추가]

### iPhone (사파리)
1. 위 주소를 사파리로 열기
2. 하단 공유 버튼(□↑) 탭
3. [홈 화면에 추가] 탭
4. [추가]

---

## 🎨 아이콘 만들기 (선택)
https://favicon.io/favicon-generator 에서
🍼 이모지로 192x192, 512x512 png 생성 후
파일명을 icon-192.png, icon-512.png 로 저장해서 업로드

---

## ⚠️ AI 증상 상담 기능 관련
이 앱은 Anthropic Claude API를 사용합니다.
배포 후 AI 기능이 작동하지 않을 경우,
Claude.ai 채팅 내 위젯에서 사용하시는 것을 권장합니다.
