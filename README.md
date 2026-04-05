# 프로젝토리 / Projectory

> 미래 세대를 위한 실험실.  
> A laboratory for the next generation.

`프로젝토리`는 결과물을 전시하는 웹사이트가 아니라, 아이들이 직접 만들고, 그리고, 고르고, 남길 수 있는 실험 공간을 웹으로 옮긴 프로젝트입니다.  
2020년의 나는 이 프로젝트를 통해 "재미있는 UI"보다 "사람이 자기 방식으로 참여할 수 있는 경험"이 더 중요하다고 생각했습니다.

`Projectory` is not just a showcase site. It is a web-based experiment space where children can make, draw, choose, and leave something behind.  
In 2020, I cared less about flashy UI and more about building an experience that let people participate in their own way.

## Why I Built This / 왜 만들었는가

- **한국어**: 무언가를 배우는 과정에서 중요한 것은 정답을 보여주는 것이 아니라, 스스로 손을 움직여보는 경험이라고 봤습니다. 이 프로젝트는 그 감각을 웹 인터페이스로 옮기려는 시도였습니다.
- **English**: I believed that learning should not be reduced to showing the answer. It should feel like touching, choosing, and making something yourself. This project was my attempt to translate that into a web interface.
- **한국어**: 아이들을 위한 서비스는 단순히 귀여운 디자인이 아니라, 이해하기 쉬운 흐름과 즉시 반응하는 상호작용이 중요했습니다.
- **English**: For a kids-oriented service, cute visuals alone were not enough. The interaction had to be obvious, immediate, and easy to trust.
- **한국어**: 2020년의 나는 시각적으로 설명되는 구조와 프로토타입 중심의 접근에 강했습니다. 대신 제품을 장기적으로 확장 가능한 구조로 설계하는 힘은 지금보다 약했습니다.
- **English**: In 2020, I was strong at visual structure and prototype-driven work. My weaker point was building systems that were cleanly scalable over time.

## What It Means / 이 프로젝트의 의미

이 프로젝트는 "보여주는 웹"보다 "참여하게 만드는 웹"에 더 가깝습니다.  
사용자는 단순히 결과물을 보는 사람이 아니라, 만들기/그리기/영상/편지/음악 같은 여러 활동에 들어와 자기 흔적을 남기는 참여자가 됩니다.

This project is closer to a web experience that invites participation than a site that only displays content.  
The user is not just a viewer. They become a participant who leaves traces through making, drawing, video, letters, and music.

## Experience Structure / 경험 구조

- **메이킹 / Making**: 손으로 만드는 감각을 중심에 둔 활동 섹션.
- **그리기 / Drawing**: 그림과 캐릭터, 색감 중심의 탐색 섹션.
- **영상 / Video**: 움직임과 짧은 서사를 보여주는 영상 섹션.
- **편지 / Letter**: 메시지와 감정을 남기는 텍스트 중심 섹션.
- **음악 / Music**: 소리와 분위기를 체험하는 섹션.
- **기타 / Etc**: 위 분류에 들어가지 않는 실험적 콘텐츠 영역.

## 2020 Perspective / 2020년의 나를 어떻게 보는가

### Strengths / 강점

- **한국어**: 주제를 빠르게 장면으로 바꾸는 감각이 있었습니다. 아이들이 무엇을 보면 이해할지, 무엇에 반응할지 시각적으로 빠르게 잡아냈습니다.
- **English**: I was good at turning abstract ideas into scenes. I could quickly predict what children would understand and respond to visually.
- **한국어**: 정적인 설명보다 흐름과 반응을 먼저 설계하려고 했습니다. 그래서 페이지마다 배너, 선택, 전환이 분명하게 느껴지도록 구성했습니다.
- **English**: I preferred designing flow and feedback over static explanation. That is why each section emphasizes banners, selection, and transitions.

### Weaknesses / 한계

- **한국어**: 당시에는 감각적으로 만들 수는 있었지만, 코드와 콘텐츠를 분리해 재사용 가능한 구조로 정리하는 습관은 부족했습니다.
- **English**: I could build things intuitively, but I was less disciplined about separating code from content and making the structure reusable.
- **한국어**: 기능 확장성이나 유지보수 관점에서는 지금보다 덜 엄격했습니다.
- **English**: I was less strict than I am now about extensibility and maintainability.

### Why It Still Matters / 지금도 의미가 있는 이유

프로젝토리는 내가 "디자인은 보여주는 것이 아니라 참여를 설계하는 일"이라고 생각하게 만든 프로젝트입니다.  
그 관점은 이후의 UX, 인터랙티브, AI, 시스템 작업으로 계속 이어졌습니다.

`Projectory` shaped the way I think about design: not as display, but as participation.  
That idea continued into my later UX, interactive, AI, and systems work.

## Tech Stack / 기술 스택

- **Framework**: React
- **Build**: Create React App
- **Styling and media**: CSS, image assets, audio assets, static banner content
- **UI library**: Reactstrap / Bootstrap 기반 컴포넌트 활용
- **Typography**: Google Fonts (`Noto Sans KR`, `Nanum Pen Script`, `Poor Story`)

## What Is Included / 포함된 콘텐츠

- 메이킹 콘텐츠
- 드로잉 콘텐츠
- 비디오 콘텐츠
- 편지 콘텐츠
- 음악 콘텐츠
- 기타 실험 콘텐츠

## Local Preview / 확인 방법

정적 산출물 기준으로는 별도 실행 스크립트가 저장소에 포함되어 있지 않습니다.  
빌드 원본이 있다면 CRA 개발 서버로 확인하는 방식이 일반적입니다.

## Project Layout / 구조

- `index.html` - React entry shell
- `static/js/` - production bundle
- `static/css/` - compiled styles
- `img/` - banners, logos, thumbnails, and section assets
- `music/` - audio asset

---

Built as a child-friendly experimental lab.  
아이들이 직접 참여할 수 있는 실험실로 만들었습니다.
