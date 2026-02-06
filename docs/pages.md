# Page Layouts & Content Structure

> Detailed specifications for each page and section of the Proyecto 26 website.

## Table of Contents
- [Homepage](#homepage)
- [Games Page](#games-page)
- [Navigation](#navigation)
- [Responsive Behavior](#responsive-behavior)

---

## Homepage

The homepage is the main showcase of Proyecto 26's identity, projects, and capabilities.

### Page Structure Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                         NAVIGATION                               │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│                         HERO SECTION                             │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│                     FEATURED PROJECTS                            │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│                      WHAT WE BUILD                               │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│                     GAMES SHOWCASE                               │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│                    MEET THE FOUNDER                              │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│                        COMMUNITY                                 │
│                                                                  │
├─────────────────────────────────────────────────────────────────┤
│                          FOOTER                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

### Section 1: Hero

**Purpose**: Capture attention, communicate value proposition, encourage exploration.

#### Layout

```
┌──────────────────────────────────────────────────────────────────────────┐
│                                                                          │
│  ╔══════════════════════════════════════════════════════════════════╗   │
│  ║                                                                   ║   │
│  ║                        PROYECTO 26                                ║   │
│  ║                                                                   ║   │
│  ╚══════════════════════════════════════════════════════════════════╝   │
│                                                                          │
│            Changing the world with small contributions.                  │
│                                                                          │
│     We build open source tools for Web, Mobile, and Game Development     │
│                    that developers around the world love.                │
│                                                                          │
│                                                                          │
│         ┌──────────────────┐       ┌──────────────────┐                 │
│         │ Explore Projects │       │   Play Games     │                 │
│         └──────────────────┘       └──────────────────┘                 │
│                                                                          │
│                                                                          │
│      ┌─────────────┐    ┌─────────────┐    ┌─────────────┐             │
│      │   2,923+    │    │     5+      │    │    50+      │             │
│      │   Stars     │    │  Projects   │    │ Contributors│             │
│      └─────────────┘    └─────────────┘    └─────────────┘             │
│                                                                          │
│                                                                          │
│                           ↓ Scroll                                       │
│                                                                          │
└──────────────────────────────────────────────────────────────────────────┘
```

#### Content

| Element | Content | Style |
|---------|---------|-------|
| Title | "PROYECTO 26" | `--text-6xl`, black weight, gradient or white |
| Tagline | "Changing the world with small contributions." | `--text-3xl`, semibold, white |
| Description | "We build open source tools for Web, Mobile, and Game Development that developers around the world love." | `--text-xl`, regular, `--color-text-secondary` |
| CTA Primary | "Explore Projects" | Primary button, coral |
| CTA Secondary | "Play Games" | Secondary button, outlined |

#### Stats

| Stat | Value | Source |
|------|-------|--------|
| Stars | Sum of all repo stars (~2,923) | GitHub API |
| Projects | Count of public repos (5+) | GitHub API |
| Contributors | Unique contributors | GitHub API or static |

#### Background

- Background: Retro style image (`p26-retro.jpg`) with gradient overlay
- Floating shapes: 3-5 abstract shapes with parallax (overlay)
- Optional: Particle effect (subtle, performance-conscious)

#### Animations

1. Title: Split text reveal with rotation (0.8s)
2. Tagline: Fade up (0.6s, 0.2s delay)
3. Description: Fade up (0.6s, 0.4s delay)
4. Buttons: Stagger fade up (0.5s, 0.6s delay)
5. Stats: Fade up + counter animation (1s, 0.8s delay)
6. Background shapes: Continuous float animation

---

### Section 2: Featured Projects

**Purpose**: Showcase main open source contributions with live GitHub stats.

#### Layout

```
┌──────────────────────────────────────────────────────────────────────────┐
│                                                                          │
│                    Open Source Tools Developers Love                     │
│                                                                          │
│       Building the future of web, mobile, and game development           │
│                                                                          │
│  ┌────────────────────┐  ┌────────────────────┐  ┌────────────────────┐ │
│  │                    │  │                    │  │                    │ │
│  │  [Icon]            │  │  [Icon]            │  │  [Icon]            │ │
│  │                    │  │                    │  │                    │ │
│  │  InAppBrowser      │  │  RestClient        │  │  Animatable        │ │
│  │  for React Native  │  │  for Unity         │  │  Component         │ │
│  │                    │  │                    │  │                    │ │
│  │  InAppBrowser for  │  │  Promise-based     │  │  Web component     │ │
│  │  React Native...   │  │  REST client...    │  │  for animations... │ │
│  │                    │  │                    │  │                    │ │
│  │  [RN] [iOS] [And]  │  │  [Unity] [C#]      │  │  [TS] [Web]        │ │
│  │                    │  │                    │  │                    │ │
│  │  ⭐ 1,423  🍴 234  │  │  ⭐ 1,312  🍴 189  │  │  ⭐ 258   🍴 42   │ │
│  │                    │  │                    │  │                    │ │
│  │  [View] [GitHub]   │  │  [View] [GitHub]   │  │  [View] [GitHub]   │ │
│  │                    │  │                    │  │                    │ │
│  └────────────────────┘  └────────────────────┘  └────────────────────┘ │
│                                                                          │
│  ┌────────────────────┐  ┌────────────────────┐                         │
│  │                    │  │                    │                         │
│  │  [Icon]            │  │  [Icon]            │                         │
│  │                    │  │                    │                         │
│  │  IonPhaser         │  │  InAppBrowser      │                         │
│  │                    │  │  for NativeScript  │                         │
│  │  Web component     │  │                    │                         │
│  │  for Phaser...     │  │  InAppBrowser for  │                         │
│  │                    │  │  NativeScript...   │                         │
│  │  [Phaser] [Ionic]  │  │  [NS] [iOS] [And]  │                         │
│  │                    │  │                    │                         │
│  │  ⭐ 252   🍴 38   │  │  ⭐ 87    🍴 21   │                         │
│  │                    │  │                    │                         │
│  │  [View] [GitHub]   │  │  [View] [GitHub]   │                         │
│  │                    │  │                    │                         │
│  └────────────────────┘  └────────────────────┘                         │
│                                                                          │
│                        [View All Projects →]                             │
│                                                                          │
└──────────────────────────────────────────────────────────────────────────┘
```

#### Project Data

```javascript
const projects = [
  {
    name: 'react-native-inappbrowser',
    displayName: 'InAppBrowser for React Native',
    description: 'InAppBrowser for React Native with support for Chrome Custom Tabs and Safari Services.',
    repo: 'proyecto26/react-native-inappbrowser',
    tags: ['React Native', 'iOS', 'Android'],
    icon: '/img/projects/inappbrowser-react-native.png',
    demoUrl: null,
  },
  {
    name: 'RestClient',
    displayName: 'RestClient for Unity',
    description: 'Promise-based REST and HTTP client for Unity game development.',
    repo: 'proyecto26/RestClient',
    tags: ['Unity', 'C#'],
    icon: '/img/projects/restclient.png',
    demoUrl: null,
  },
  {
    name: 'animatable-component',
    displayName: 'Animatable Component',
    description: 'Web component for creating reusable animations using the Web Animations API.',
    repo: 'proyecto26/animatable-component',
    tags: ['TypeScript', 'Web Components'],
    icon: '/img/projects/animatable.png',
    demoUrl: 'https://proyecto26.github.io/animatable-component/',
  },
  {
    name: 'ion-phaser',
    displayName: 'IonPhaser',
    description: 'Web component to integrate Phaser game framework with Ionic and other frameworks.',
    repo: 'proyecto26/ion-phaser',
    tags: ['Phaser', 'Ionic', 'Web Components'],
    icon: '/img/projects/ionphaser.png',
    demoUrl: 'https://proyecto26.github.io/ion-phaser/',
  },
  {
    name: 'nativescript-inappbrowser',
    displayName: 'InAppBrowser for NativeScript',
    description: 'InAppBrowser plugin for NativeScript applications.',
    repo: 'proyecto26/nativescript-inappbrowser',
    tags: ['NativeScript', 'iOS', 'Android'],
    icon: '/img/projects/inappbrowser-nativescript.png',
    demoUrl: null,
  },
];
```

#### Animations

- Section title: Fade up on scroll
- Cards: Stagger reveal with 3D tilt setup
- Stats: Counter animation when card is visible

---

### Section 3: What We Build

**Purpose**: Communicate core capabilities and technology focus.

#### Layout

```
┌──────────────────────────────────────────────────────────────────────────┐
│                                                                          │
│                           What We Build                                  │
│                                                                          │
│     Specialized tools and libraries across three core domains            │
│                                                                          │
│                                                                          │
│    ┌──────────────────┐  ┌──────────────────┐  ┌──────────────────┐    │
│    │                  │  │                  │  │                  │    │
│    │      📱         │  │       🌐        │  │       🎮        │    │
│    │                  │  │                  │  │                  │    │
│    │     Mobile       │  │       Web        │  │      Games       │    │
│    │   Development    │  │   Components     │  │   Development    │    │
│    │                  │  │                  │  │                  │    │
│    │  React Native    │  │    Stencil       │  │     Phaser       │    │
│    │  NativeScript    │  │  Web Animations  │  │     Unity        │    │
│    │     Ionic        │  │   TypeScript     │  │      C#          │    │
│    │                  │  │                  │  │                  │    │
│    └──────────────────┘  └──────────────────┘  └──────────────────┘    │
│                                                                          │
└──────────────────────────────────────────────────────────────────────────┘
```

#### Content

| Service | Icon | Technologies |
|---------|------|--------------|
| Mobile Development | Phone icon | React Native, NativeScript, Ionic |
| Web Components | Globe icon | Stencil, Web Animations API, TypeScript |
| Game Development | Gamepad icon | Phaser, Unity, C# |

#### Animations

- Icons: Draw/reveal animation on scroll
- Cards: Fade up with stagger
- Connection lines (desktop): Animate on scroll

---

### Section 4: Games Showcase

**Purpose**: Highlight playful side and game development expertise.

#### Layout

```
┌──────────────────────────────────────────────────────────────────────────┐
│                                                                          │
│                          Play Our Games                                  │
│                                                                          │
│         Interactive demos built with Phaser game framework               │
│                                                                          │
│                                                                          │
│   ┌─────────────────────────────────────────────────────────────────┐   │
│   │                                                                 │   │
│   │                                                                 │   │
│   │                    [Game Preview GIF/Video]                     │   │
│   │                                                                 │   │
│   │                           ▶ PLAY                                │   │
│   │                                                                 │   │
│   │                                                                 │   │
│   └─────────────────────────────────────────────────────────────────┘   │
│                                                                          │
│   NinjaDev                                                              │
│                                                                          │
│   A side-scrolling platformer built with Phaser to showcase             │
│   game development techniques and interactive animations.                │
│                                                                          │
│   [Phaser]  [2D]  [Platformer]                                          │
│                                                                          │
│                                                                          │
│                         [Explore All Games →]                            │
│                                                                          │
└──────────────────────────────────────────────────────────────────────────┘
```

#### Featured Game

Display one game prominently with a preview (GIF or video loop).

#### Animations

- Preview: Subtle zoom on hover
- Scanline overlay: Retro CRT effect
- Play button: Pulse animation

---

### Section 5: Meet the Founder

**Purpose**: Add human element and credibility.

#### Layout

```
┌──────────────────────────────────────────────────────────────────────────┐
│                                                                          │
│                         Meet the Founder                                 │
│                                                                          │
│                                                                          │
│       ┌───────────────┐                                                 │
│       │               │                                                 │
│       │               │    Juan David Nicholls                          │
│       │    [Photo]    │    ──────────────────                           │
│       │               │    Founder & Lead Developer                     │
│       │               │                                                 │
│       └───────────────┘    Developer with 13+ years of experience       │
│                            building interactive experiences across       │
│                            web, mobile, and game development.           │
│                                                                          │
│                            Passionate about open source and              │
│                            changing the world with small                 │
│                            contributions.                                │
│                                                                          │
│                            Based in Colombia 🇨🇴                         │
│                                                                          │
│                            [LinkedIn] [GitHub] [Twitter] [SO]           │
│                                                                          │
└──────────────────────────────────────────────────────────────────────────┘
```

#### Content

```javascript
const founder = {
  name: 'Juan David Nicholls',
  role: 'Founder & Lead Developer',
  bio: 'Full-Stack Developer and Open Source Contributor with over 14 years of expertise in web, mobile, game, blockchain and cloud development. Skilled in building scalable architectures, seamless user experiences and driving innovation through Open Source. Passionate about sharing knowledge as a speaker and mentor.',
  location: 'Colombia',
  image: '/img/leosuarizzi.jpg',
  social: {
    linkedin: 'https://www.linkedin.com/in/leonardo-squarizzi/',
    github: 'https://github.com/LeoSquarizzi',
    twitter: 'https://x.com/jdnichollsc',
    stackoverflow: 'https://stackoverflow.com/users/jdnichollsc',
  },
};
```

#### Animations

- Photo: Mask reveal from center
- Gradient border: Slow rotation
- Social icons: Bounce on hover

---

### Section 6: Community

**Purpose**: Encourage community engagement and contributions.

#### Layout

```
┌──────────────────────────────────────────────────────────────────────────┐
│                                                                          │
│                        Join Our Community                                │
│                                                                          │
│     Contribute to open source projects used by developers worldwide      │
│                                                                          │
│                                                                          │
│      ┌────────────────────────────────────────────────────────────┐     │
│      │                                                            │     │
│      │        ⭐ Star us on GitHub                                │     │
│      │                                                            │     │
│      │  [──────────────────────────────────────────] View Repos   │     │
│      │                                                            │     │
│      └────────────────────────────────────────────────────────────┘     │
│                                                                          │
│                                                                          │
│     How to Contribute:                                                   │
│                                                                          │
│     1. Fork the repository                                              │
│     2. Create your feature branch                                       │
│     3. Submit a pull request                                            │
│                                                                          │
│                      [Read Contribution Guide]                           │
│                                                                          │
└──────────────────────────────────────────────────────────────────────────┘
```

---

## Games Page

Dedicated page for browsing all games.

### Layout

```
┌──────────────────────────────────────────────────────────────────────────┐
│                            NAVIGATION                                    │
├──────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                            Our Games                                     │
│                                                                          │
│      Interactive demos and experiments built with Phaser                 │
│                                                                          │
│                                                                          │
│   ┌────────────────────────┐      ┌────────────────────────┐            │
│   │                        │      │                        │            │
│   │    [Ninja Preview]     │      │   [Zombies Preview]    │            │
│   │                        │      │                        │            │
│   │    NinjaDev            │      │    Zombie Attack       │            │
│   │                        │      │                        │            │
│   │    Side-scrolling      │      │    Survival shooter    │            │
│   │    platformer          │      │    with waves          │            │
│   │                        │      │                        │
│   │    [Play Now]          │      │    [Play Now]          │            │
│   │                        │      │                        │            │
│   └────────────────────────┘      └────────────────────────┘            │
│                                                                          │
│   ┌────────────────────────┐                                            │
│   │                        │                                            │
│   │   [NinjaDev Preview]   │                                            │
│   │                        │                                            │
│   │    NinjaDev (v2)       │                                            │
│   │                        │                                            │
│   │    Enhanced version    │                                            │
│   │    with new features   │                                            │
│   │                        │                                            │
│   │    [Play Now]          │                                            │
│   │                        │                                            │
│   └────────────────────────┘                                            │
│                                                                          │
│                                                                          │
│                          [← Back to Home]                                │
│                                                                          │
├──────────────────────────────────────────────────────────────────────────┤
│                             FOOTER                                       │
└──────────────────────────────────────────────────────────────────────────┘
```

### Games Data

```javascript
const games = [
  {
    id: 'ninja',
    name: 'NinjaDev',
    description: 'A side-scrolling platformer with collectibles and obstacles.',
    image: '/img/ninja.png',
    path: '/games/ninja/',
    tags: ['Phaser', '2D', 'Platformer'],
  },
  {
    id: 'zombies',
    name: 'Zombie Attack',
    description: 'Survival shooter with waves of zombies and virtual joystick support.',
    image: '/img/zombies.png',
    path: '/games/zombies/',
    tags: ['Phaser', '2D', 'Shooter'],
  },
  {
    id: 'ninjadev',
    name: 'NinjaDev (v2)',
    description: 'Enhanced version with improved graphics and mechanics.',
    image: '/img/ninja-back.gif',
    path: '/games/ninjadev/',
    tags: ['Phaser', '2D', 'Platformer'],
  },
];
```

---

## Navigation

### Desktop

```
[P26 Logo]     Projects   Games   About   Contact     [Theme] [GitHub]
```

- **Logo**: SVG, 40px height, coral accent on hover
- **Links**: `--text-base`, medium weight, 32px spacing
- **Theme Toggle**: Sun/moon icon button
- **GitHub**: Icon button with star count badge

### Mobile (< 768px)

```
[P26 Logo]                                            [Theme] [Menu]
```

- **Menu**: Hamburger icon, opens full-screen drawer

### Scroll Behavior

```javascript
// Header scroll behavior
let lastScroll = 0;
const header = document.querySelector('.header');

window.addEventListener('scroll', () => {
  const currentScroll = window.pageYOffset;

  // Add background on scroll
  if (currentScroll > 50) {
    header.classList.add('scrolled');
  } else {
    header.classList.remove('scrolled');
  }

  // Hide on scroll down, show on scroll up
  if (currentScroll > lastScroll && currentScroll > 100) {
    header.classList.add('hidden');
  } else {
    header.classList.remove('hidden');
  }

  lastScroll = currentScroll;
});
```

---

## Responsive Behavior

### Breakpoints

| Breakpoint | Width | Layout Changes |
|------------|-------|----------------|
| Mobile | < 640px | Single column, stacked navigation |
| Tablet | 640-1023px | 2-column grids, side-by-side sections |
| Desktop | ≥ 1024px | Full layout, 3-column grids |
| Large | ≥ 1280px | Max container width, larger typography |

### Grid Adaptations

```css
/* Project cards grid */
.projects-grid {
  display: grid;
  gap: var(--grid-gap);
  grid-template-columns: 1fr; /* Mobile: 1 column */
}

@media (min-width: 640px) {
  .projects-grid {
    grid-template-columns: repeat(2, 1fr); /* Tablet: 2 columns */
  }
}

@media (min-width: 1024px) {
  .projects-grid {
    grid-template-columns: repeat(3, 1fr); /* Desktop: 3 columns */
  }
}
```

### Mobile Optimizations

- Touch targets: Minimum 44px × 44px
- Reduced animations for performance
- Simplified navigation (hamburger menu)
- Larger text for readability
- No custom cursor (touch devices)

---

*These page specifications provide a complete blueprint for implementing the Proyecto 26 website.*
