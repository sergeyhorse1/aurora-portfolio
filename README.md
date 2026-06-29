# Aurora — interactive shader playground

> Write GLSL fragment shaders, see them live, share via URL. A creative sandbox for everyone curious about generative graphics.

[![CI](https://github.com/sergeyhorse1/aurora-shaders/actions/workflows/ci.yml/badge.svg)](https://github.com/sergeyhorse1/aurora-shaders/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-in_development-orange)

🚧 **Status:** in active development. Live demo will appear here.

---

## EN

### What it is
A web playground for fragment shaders: write GLSL on the left, see the result render live on the right. Save your creations, share via short URL (the whole shader is encoded into the URL — no backend in v1), fork other people's shaders and tweak them.

### Stack
Vite · React 19 · TypeScript (strict) · React Three Fiber + drei + postprocessing · CodeMirror 6 · Zustand · Tailwind 4 · Framer Motion · LZ-string (URL encoding)

### Highlights
- Shaders encoded into URL — share without an account, no backend needed in v1
- Live preview debounced at 200ms — smooth typing
- Inline shader compile errors right in the editor
- GPU-friendly: FPS cap, throttle on low-end devices
- WebGL context-lost handling for mobile / background tabs
- Respects `prefers-reduced-motion` — static frame instead of animation

### Run locally
```bash
pnpm install
pnpm dev
```

---

## RU

### Что это
Веб-площадка для фрагментных шейдеров: пишешь GLSL слева, видишь результат справа в реальном времени. Сохраняешь, делишься короткой ссылкой (сам шейдер кодируется в URL — никакого backend в v1), форкаешь чужие шейдеры и докручиваешь под себя.

### Стек
Vite · React 19 · TypeScript (strict) · React Three Fiber + drei + postprocessing · CodeMirror 6 · Zustand · Tailwind 4 · Framer Motion · LZ-string (URL encoding)

### Highlights
- Шейдеры кодируются в URL — sharing без аккаунта, без backend в v1
- Живой preview с debounce 200ms — печатать плавно
- Inline ошибки компиляции прямо в редакторе
- GPU-дружелюбно: cap FPS, throttle на слабых устройствах
- Обработка WebGL context lost (мобильный, background-таб)
- Уважает `prefers-reduced-motion` — статичный кадр вместо анимации

### Запуск локально
```bash
pnpm install
pnpm dev
```

---

## License
[MIT](LICENSE)
