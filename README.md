# Shozzle

## [online](https://gentle-queijadas-a317c9.netlify.app/)

## 🚀 Project Structure

```
src
├─ components
│  ├─ CategoryCloud.astro
│  ├─ Footer.astro
│  ├─ Hamburger.astro
│  ├─ Link.astro
│  ├─ Menu.astro
│  ├─ Nav.astro
│  ├─ Pagination.astro
│  ├─ PostCard.astro
│  ├─ PostHeader.astro
│  ├─ RelatedPosts.astro
│  └─ index.astro
├─ constants
│  └─ navData.js
├─ env.d.ts
├─ icons
│  └─ logo.svg
├─ layouts
│  ├─ BlogPostLayout.astro
│  ├─ MainHead.astro
│  └─ MainLayout.astro
├─ pages
│  ├─ 404.astro
│  ├─ about.astro
│  ├─ author
│  │  ├─ [author].astro
│  │  └─ allen.astro
│  ├─ category
│  │  └─ [category].astro
│  ├─ index.astro
│  └─ posts
│     └─ Shozzle blog post introduction.mdx
├─ scripts
│  └─ menu.js
├─ style
│  ├─ _arrow-animation.sass
│  ├─ _break-point.sass
│  ├─ _dark-mode-switcher.sass
│  ├─ _hamburger-animation.sass
│  ├─ _reset.sass
│  ├─ _variables.sass
│  ├─ github-markdown-light.css
│  └─ global.sass
└─ utils
   └─ index.js

```

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## project style

考慮到專案類型並不會很複雜，所以直接訂定一套 style 標準，基本上這部分交給 Allen

另外，專案也已經有加上 tailwind 可以寫，不過比較像是輔助

若想針對元件做類似 module css 的話 astro 亦提供了解決方案 [官網](https://docs.astro.build/zh-tw/tutorial/2-pages/4/#style-an-individual-page)

## dependencies

- npm : 9.5.1
- node : v16.17.1

## 👀 Common Rules

- 有寫元件記得統一由 index.astro 匯出
- icon 用這 [icones](https://icones.js.org/)
