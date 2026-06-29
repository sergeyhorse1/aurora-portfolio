# Aurora — 3D portfolio site

> One-screen awwwards-style portfolio with a custom GLSL-shaded 3D hero, smooth Lenis scroll, and GSAP-driven section reveals. Built with Next.js 15, React Three Fiber and GSAP.

[![CI](https://github.com/sergeyhorse1/aurora-portfolio/actions/workflows/ci.yml/badge.svg)](https://github.com/sergeyhorse1/aurora-portfolio/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-in_development-orange)

🚧 **Status:** in active development. Demo and screenshots will appear here as features land.

---

## EN

### What it is
A single-page awwwards-style portfolio. Hero is a custom GLSL-shaded R3F sphere reacting to the cursor; sections reveal on scroll via GSAP ScrollTrigger; "Selected Work" uses a horizontal pinned-scroll layout. Built to demonstrate production-grade animation and 3D craft inside Next.js App Router.

### Stack
Next.js 15 · React 19 · TypeScript (strict) · React Three Fiber · drei · postprocessing · GSAP + ScrollTrigger + SplitText · Lenis · Framer Motion · Tailwind 4

### Highlights
- Hero scene with vertex-displacement shader, reacting to cursor
- Horizontal pinned scroll for "Selected Work" on desktop, vertical list on mobile
- A11y: respects `prefers-reduced-motion`, focus-visible everywhere
- Performance target: Lighthouse ≥95 desktop, ≥90 mobile
- Smooth scroll via Lenis synced with GSAP ticker (single rAF source of truth)
- All three-modules lazy-loaded via `next/dynamic` (`ssr: false`) to keep RSC bundle clean

### Run locally
```bash
pnpm install
pnpm dev                # http://localhost:3000
pnpm build && pnpm start
```

---

## RU

### Что это
Одностраничный awwwards-style портфолио-сайт. Hero — кастомный GLSL-шейдер на R3F-сфере, реагирует на курсор. Секции «выезжают» по скроллу через GSAP ScrollTrigger. «Selected Work» — горизонтальный pinned-скролл. Демонстрирует продакшен-уровень анимаций и 3D в Next.js App Router.

### Стек
Next.js 15 · React 19 · TypeScript (strict) · React Three Fiber · drei · postprocessing · GSAP + ScrollTrigger + SplitText · Lenis · Framer Motion · Tailwind 4

### Highlights
- Hero с шейдером vertex-displacement, реагирует на курсор
- Горизонтальный pinned-скролл для «Selected Work» на десктопе, обычный список на мобильном
- A11y: уважает `prefers-reduced-motion`, focus-visible везде
- Цель по performance: Lighthouse ≥95 desktop, ≥90 mobile
- Плавный скролл через Lenis, синхронизирован с GSAP-тикером (один rAF на всё)
- Все three-модули — через `next/dynamic` с `ssr: false`, чтобы не попадать в RSC-бандл

### Запуск локально
```bash
pnpm install
pnpm dev
pnpm build && pnpm start
```

---

## License
[MIT](LICENSE)
