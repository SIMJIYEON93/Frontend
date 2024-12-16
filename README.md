This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## 디렉토리 구조
```
frontend/
├── app/
│   ├── layout.tsx        # 모든 페이지에 공통으로 적용될 레이아웃 정의
│   ├── page.tsx          # 루트 경로('/')에 대한 페이지 컴포넌트
│   ├── api/              # API 라우트를 정의하는 디렉토리
│   │   ├── hello/route.ts # /api/hello 경로를 처리하는 API 핸들러
│   └── styles/           # CSS 스타일 정의
│       └── globals.css   # 전역 스타일 파일
├── public/               # 정적 파일 (이미지, 폰트 등)
├── package.json          # 프로젝트의 의존성 및 스크립트 정의
├── tsconfig.json         # TypeScript 설정 파일
├── next.config.js        # Next.js 설정 파일

```
