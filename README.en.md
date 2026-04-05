# Projectory

> A laboratory for the next generation.  
> A participatory web experience where children can make, draw, choose, and leave something behind.

![GitHub stars](https://img.shields.io/github/stars/dosigner/ncfound?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/dosigner/ncfound?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/dosigner/ncfound?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/dosigner/ncfound?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/dosigner/ncfound?style=flat-square)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dosigner/ncfound?style=flat-square)

[Live site](https://dosigner.github.io/ncfound/) · [Korean version](./README.md)

`Projectory` is not a showcase site. It is a web-based experiment space where children can make, draw, choose, and leave something behind.  
In 2020, I cared less about flashy UI and more about designing an experience that invited participation.

My motivation was simple: learning should not feel like reading an answer sheet. It should feel like touching, choosing, and making something yourself.  
So this project was designed around participation rather than explanation. Users should enter, choose, react, and leave a trace.

For me, Projectory became the first large experiment that showed how design can shape participation rather than only presentation.

> [!note]
> This repository now behaves more like a **deployed archive** than a full source tree.
> What remains is mostly static output such as `index.html`, `static/js`, `static/css`, `img`, and `music`.

## Why I Built This

I wanted to test whether a children's web experience could be structured around participation rather than explanation.

- I wanted to change the learning experience from passive reading to active participation.
- I wanted to validate an interaction flow that works for children.
- I wanted to build a web experience where the user leaves a trace, not just views a page.

## How I See My 2020 Self

In 2020, I was good at turning abstract ideas into scenes and quickly shaping flow with banners, choices, and transitions.

My gaps were also clear:

- I was less disciplined about separating code from content into reusable structures.
- I did not think as rigorously about maintainability and extensibility as I do now.
- I focused more on making something feel complete than on systemizing it.

## Why It Still Matters

Projectory changed how I think about design.  
After this project, I stopped seeing design as presentation and started seeing it as participation.

That mindset carried into later UX, interactive, AI, and systems work:

- UX: I started paying more attention to first-impression flow.
- Interactive work: I started designing feedback and rhythm more intentionally.
- AI and systems work: I started looking first for the user's real bottleneck.

## What Is Inside

- Making
- Drawing
- Video
- Letter
- Music
- Etc

## Tech Stack

- React-based single-page application
- Create React App-style static build output
- GitHub Pages subpath deployment at `/ncfound/`
- Bootstrap / Reactstrap-style component traces in the bundle
- Local image archives, banner assets, and audio files
- Google Fonts: `Noto Sans KR`, `Nanum Pen Script`, `Poor Story`

## What the Codebase Shows

- The original source tree is no longer present here; the repository mostly preserves the deployed artifact.
- `index.html` and the bundled CSS/JS indicate a React app built into a static distribution.
- The `img` and `music` directories show how heavily the project relied on atmosphere, visual rhythm, and sensory participation.

## IA

```mermaid
graph TD
    A["Projectory"] --> B["Making"]
    A --> C["Drawing"]
    A --> D["Video"]
    A --> E["Letter"]
    A --> F["Music"]
    A --> G["Etc"]
    A --> H["Visual System"]
    A --> I["Static Build"]

    H --> H1["Banners"]
    H --> H2["Illustrations"]
    H --> H3["Fonts"]

    I --> I1["index.html"]
    I --> I2["static/js"]
    I --> I3["static/css"]
    I --> I4["img / music"]
```

Useful Obsidian companion: [`IA.canvas`](./IA.canvas)

---

Built as a child-friendly experimental lab for participation, not just presentation.
