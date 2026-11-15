# 마이링크 (MyLink) 🔗

나만의 중요한 링크들을 간편하게 한 곳에 모아 공유하는 마이링크(MyLink) 서비스입니다.

---

## 📌 과제 제출 정보
- **1. GitHub 저장소 URL**: [https://github.com/sinjuhang-eng/my-link](https://github.com/sinjuhang-eng/my-link)
  - 마이링크(MyLink) 전용 폴더: [https://github.com/sinjuhang-eng/my-link/tree/main/mylink](https://github.com/sinjuhang-eng/my-link/tree/main/mylink)
- **2. 마이링크(MyLink) 접속 URL**: [https://sinjuhang-eng.github.io/my-link/](https://sinjuhang-eng.github.io/my-link/)
  - 폴더 경로 접속 URL: [https://sinjuhang-eng.github.io/my-link/mylink/](https://sinjuhang-eng.github.io/my-link/mylink/)

---

## 📁 디렉터리 구조
```text
my-link/
├── index.html               # GitHub Pages 루트 접속용 정적 마이링크 페이지
├── mylink/                  # '마이링크(MyLink)' 전용 폴더
│   └── index.html           # 전용 폴더 내 마이링크 페이지
├── src/                     # Next.js 소스 코드
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   └── LinkCard.tsx
│   └── types/
│       └── link.ts
├── public/
├── package.json
└── README.md
```

## ✨ 주요 기능
- 반응형 모바일/데스크톱 최적화 레이아웃
- 사용자 프로필 및 한 줄 소개
- GitHub, SNS, 이메일 다이렉트 소셜 아이콘 링크
- 핵심 링크 강조 카드 (그라데이션 & 애니메이션 효과)
- Tailwind CSS 기반 모던 UI 디자인
