<div align="center">
  <img src="https://socialify.git.ci/na64000/WeAreImagi/image?custom_language=JavaScript&description=1&font=Rokkitt&language=1&name=1&owner=1&theme=Dark" alt="WeAreImagi Project Banner" />

  <br />
  <br />

  <h1>WeAreImagi Official Platform</h1>

  <p>
    <strong>A high-performance, modern web application built with Nuxt 4, Vue 3, and Tailwind CSS.</strong>
  </p>

  <p>
    <a href="https://nuxt.com"><img src="https://img.shields.io/badge/Nuxt-4.2.1-00C58E?style=for-the-badge&logo=nuxt.js&logoColor=white" alt="Nuxt 4" /></a>
    <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/Vue.js-3.x-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue 3" /></a>
    <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" /></a>
    <a href="https://www.shadcn-vue.com/"><img src="https://img.shields.io/badge/shadcn--vue-000000?style=for-the-badge&logo=shadcnui&logoColor=white" alt="shadcn-vue" /></a>
  </p>
</div>

---

## 🚀 Overview

**WeAreImagi** is a robust, cutting-edge web platform built to deliver exceptional digital experiences. Powered by **Nuxt 4** and utilizing **shadcn-nuxt** for headless, accessible UI components, this project establishes a perfect balance between stunning aesthetics and top-tier performance.

### ✨ Key Features

- **⚡ Blazing Fast Performance:** SSR capabilities and optimized asset delivery via `@nuxt/image`.
- **🎨 Exquisite Design System:** Utility-first styling with **Tailwind CSS** and gorgeous, premium components powered by **shadcn-nuxt**.
- **🌗 Theming & Color Mode:** Seamless light/dark mode transitions handled by `@nuxtjs/color-mode`.
- **📝 Markdown-driven Content:** Effortless content management built-in using `@nuxt/content`.
- **🗄️ Local Database Integration:** Smooth local operations and fast data retrieval utilizing `better-sqlite3`.
- **🖼️ Iconography Ecosystem:** A rich set of scalable vector graphics through `@iconify/vue` and Material Symbols.

---

## 📸 Screenshots

_(Replace the URLs below with the actual paths to your hosted images)_

|                                                       Light Mode                                                        |                                                       Dark Mode                                                       |
| :---------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------: |
| <img src="https://placehold.co/600x400/f3f4f6/1f2937?text=Light+Mode+Preview" alt="Light Mode Screenshot" width="100%"> | <img src="https://placehold.co/600x400/111111/f44f44?text=Dark+Mode+Preview" alt="Dark Mode Screenshot" width="100%"> |

---

## 🛠️ Technology Stack

| Category               | Technology          | Description                         |
| ---------------------- | ------------------- | ----------------------------------- |
| **Core Framework**     | Nuxt `v4.x`         | Intuitive Vue Framework             |
| **Styling Engine**     | Tailwind CSS `v3.4` | Utility-first CSS framework         |
| **UI Components**      | shadcn-nuxt         | Unstyled, accessible UI components  |
| **Content Engine**     | @nuxt/content       | Git-based Headless CMS              |
| **Media Optimization** | @nuxt/image         | Plug-and-play image optimization    |
| **Database**           | better-sqlite3      | Fastest SQLite3 wrapper for Node.js |
| **Iconography**        | @iconify/vue        | Universal icon framework            |

---

## 🎨 Design Language

The project conforms strictly to a predetermined design aesthetic:

- **Primary Accent:** `#f44f44` (Vibrant Red)
- **Secondary Identity:** `#111111` (Deep Charcoal)
- **Typography:** [Manrope](https://fonts.google.com/specimen/Manrope) (Sleek, modern sans-serif)

> **Developer Note:** All custom styling should leverage existing Tailwind utility classes and the initialized Shadcn CSS variables to maintain visual consistency.

---

## ⚙️ Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- **Node.js**: `v18.x` or higher recommended.
- **npm** (or your preferred package manager like yarn/pnpm).

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/na64000/WeAreImagi.git
   cd WeAreImagi
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

### Development Server

Start the Nuxt development server at `http://localhost:3000`:

```bash
npm run dev
```

### Production Build

Build the project for production deployment:

```bash
npm run build
```

And start the production server:

```bash
npm run start
```

Or statically generate your site:

```bash
npm run generate
```

---

## 📂 Project Architecture

```text
weareimagi/
├── .nuxt/              # Auto-generated by Nuxt (Do not edit)
├── .output/            # Production build output
├── assets/             # Uncompiled assets (Sass, CSS, images, etc.)
├── components/         # Auto-imported Vue components (incl. Shadcn UI)
├── layouts/            # Custom application layouts
├── pages/              # File-system based routing views
├── plugins/            # Vue plugins to run auto-magically
├── nuxt.config.ts      # Main Nuxt configuration file
├── tailwind.config.cjs # Tailwind CSS configuration
└── package.json        # Project metadata and technical definitions
```

---

## 🤝 Contributing

We welcome community contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) to get started.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Built with ❤️ by <strong>na64000</strong>
</p>
