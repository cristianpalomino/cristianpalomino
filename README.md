# Personal Portfolio Website

This repository contains the source code for my personal portfolio website, built with [Eleventy](https://www.11ty.dev/) (11ty), a simple and flexible static site generator.

## 🚀 Features

- Fast and lightweight static site
- Responsive design
- Blog/Experience section support
- Markdown content with syntax highlighting
- RSS feed
- Reading time estimation
- Tag system
- Asset bundling and optimization
- Mermaid diagram support

## 🛠 Technical Stack

- **Static Site Generator**: [Eleventy (11ty)](https://www.11ty.dev/)
- **Templating**: Nunjucks (`.njk`)
- **Styling**: CSS
- **Markdown**: For content management
- **Build Tools**: Webpack (for asset bundling)
- **Development Mode**: BrowserSync for local development

## 📦 Dependencies

- `@11ty/eleventy`: Static site generator
- `luxon`: Date formatting
- `eleventy-plugin-reading-time`: Reading time estimation
- `@11ty/eleventy-plugin-rss`: RSS feed generation
- `@11ty/eleventy-plugin-syntaxhighlight`: Code syntax highlighting

## 🚀 Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/cristianpalomino/cristianpalomino
cd cristianpalomino
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

### Development

To start the development server:
```bash
npm run dev
# or
yarn dev
```

This will start a local server at `http://localhost:8080` with BrowserSync enabled.

### Production Build

To create a production build:
```bash
npm run build
# or
yarn build
```

The built files will be in the `public` directory.

## 📁 Project Structure

```
.
├── src/                    # Source files
│   ├── data/               # Site data files
│   ├── includes/           # Reusable template parts
│   ├── layouts/            # Page layouts
│   ├── css/                # Stylesheets
│   ├── images/             # Image assets
│   ├── experience/         # Experience/portfolio entries
│   └── pdfs/               # PDF documents
├── public/                 # Built files (generated)
└── .eleventy.js            # Eleventy configuration
```

## 🔧 Configuration

The site configuration is managed through several files:

- `.eleventy.js`: Main Eleventy configuration
- `src/data/site.json`: Global site data
- `webpack.config.js`: Asset bundling configuration (if applicable)

## 🌟 Features in Detail

### Content Management
- Write content in Markdown
- Support for front matter
- Automatic reading time calculation
- Tag system for content organization

### Development Features
- Hot reloading during development
- Asset optimization for production
- Syntax highlighting for code blocks
- Support for Mermaid diagrams

### Performance
- Optimized asset bundling
- Fast build times
- Efficient static site generation

## 📝 License

[MIT License](LICENSE)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
