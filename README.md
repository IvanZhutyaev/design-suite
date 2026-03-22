# Design Suite

A **monorepo of standalone Next.js experiments**—each folder is a complete app with its own layout, motion language, and visual identity. Nothing here is a toy snippet: these are full pages you can run, fork, and ship ideas from.

The unifying thread is **contemporary front-end craft**: App Router, TypeScript, Tailwind (v3 or v4 depending on the project), Radix-based primitives, and motion where it matters—whether that is WebGL, scroll storytelling, or crisp UI micro-interactions.

---

## What’s inside

| Project | Vibe | Notes |
|--------|------|--------|
| [**Cool bg**](Cool%20bg/) | Immersive **WebGL** hero | React Three Fiber, Drei, Three.js, Leva for tuning—built for atmospheric, shader-driven backgrounds. |
| [**Cool linqid glass landing**](Cool%20linqid%20glass%20landing/) | **Glass / dark** SaaS landing | Lenis smooth scroll, bento grid, pricing, marquee—polished marketing surface. |
| [**Cool modern design**](Cool%20modern%20design/) | **Bold** product marketing | High-contrast palette, marquee, services grid—Framer Motion–driven sections. |
| [**For Site-Portfolio**](For%20Site-Portfolio/) | **Single-page portfolio** | Section-based layout, intersection-driven reveals, light/dark toggle—classic personal site structure. |
| [**For Site-Portfolio 2**](For%20Site-Portfolio%202/) | **Portfolio** (alternate kit) | Same family as above with a different component set and styling pass—compare approaches side by side. |
| [**Just interesting design**](Just%20interesting%20design/) | **Portfolio + lab** (“EinCode”) | Blog, projects, workbench routes, structured data, theme system—closest to a full personal site product. |
| [**Just very interesting design**](Just%20very%20interesting%20design/) | **Scrollytelling** | Scroll-driven hero (e.g. headphone narrative), dark minimal chrome—story-first layout. |
| [**Nice landing page**](Nice%20landing%20page/) | **Community / brand** landing | Framer Motion, timeline, testimonials, gradient text, chatbot block—rich editorial marketing page. |

---

## Tech you’ll see everywhere

- **Next.js** (15.x or 16.x) with the **App Router**
- **React 19** and **TypeScript**
- **Tailwind CSS** + **Radix UI** primitives (shadcn-style `components/ui`)
- **next-themes** for dark/light where applicable
- Optional: **Framer Motion**, **Vercel Analytics**, **Recharts**, **Embla** carousels, **react-hook-form** + **Zod**

The **Cool bg** app layers **@react-three/fiber**, **three**, and tooling like **r3f-perf** / **leva** for 3D and dev controls.

---

## Getting started

There is **no root `package.json`**—treat each directory as its own project.

1. **Prerequisites:** Node.js 20+ (recommended) and your preferred package manager (`npm`, `pnpm`, or `yarn`).

2. **Install and run** (repeat per app):

   ```bash
   cd "Cool linqid glass landing"
   npm install
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) unless the dev server prints a different port.

3. **Production build:**

   ```bash
   npm run build
   npm start
   ```

Some folders may include a `pnpm-lock.yaml` or other lockfile—use the matching client for reproducible installs.

---

## How to use this repo

- **Steal patterns:** typography scales, section rhythm, glass/blur treatment, scroll coupling, and component composition are all copy-paste friendly within the same open-source stack.
- **Compare stacks:** jump between Tailwind v3 and v4 projects, or between “landing only” and the fuller **Just interesting design** app router structure.
- **Deploy:** each app is a normal Next.js deploy target (e.g. Vercel)—set `NEXT_PUBLIC_*` env vars where a project expects a public site URL.

---

## License

This repository does not include a root license file. Add one if you publish the work; confirm licenses of third-party assets (fonts, images, remote URLs) before commercial use.

---

*Design Suite — modern interfaces, isolated experiments, one repository.*
