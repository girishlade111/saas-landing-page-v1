# saas-landing-page-v1

Two independent, drop-in SaaS landing page React components — two design variants of a
full marketing page (features, pricing cues, testimonials, CTA sections).

## Contents

- **`saas-landing-page sample 1`** (233 lines) — SaaS landing page variant 1:
  `SaasLandingPage()` component built with shadcn/ui (`Button`, `Card` family) and
  Lucide icons (`Users`, `Shield`, `Clock`, `Check`).
- **`saas-landing-page sample 2`** (422 lines) — SaaS landing page variant 2: an extended
  layout (more sections/detail).

Each file is self-contained and independent — pick the variant you like.

## Tech stack

- React (JSX, hooks-free functional components)
- shadcn/ui (`components/ui/button`, `components/ui/card`)
- Lucide React (icons)

## Usage

These are **standalone component files**, not runnable apps. Drop one into a React project
with shadcn/ui set up, rename it to `.tsx`/`.jsx`, then:

```tsx
import SaasLandingPage from "./SaasLandingPage";

export default function Page() {
  return <SaasLandingPage />;
}
```

## Project structure

```
.
├── "saas-landing-page sample 1"   # landing page component variant 1
├── "saas-landing-page sample 2"   # landing page component variant 2
├── LICENSE
└── README.md
```

## Deploy notes

Not deployed — this repo ships reusable landing-page components, not a website.

---

Built by Girish Lade — https://ladestack.in
