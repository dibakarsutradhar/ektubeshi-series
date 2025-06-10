# ☕ Ektubeshi

> **A quirky little corner of cyberspace where sense and nonsense sip coffee together**

Welcome to the chaotic-yet-surprisingly-organized repository behind [Ektubeshi](https://ektubeshi.dibakar.me) — a bilingual blog that turns everyday absurdities into caffeinated wisdom.

## 🎯 What is Ektubeshi?

**Ektubeshi** (একটুবেশী) is Bengali slang meaning "a little too much" — and that perfectly captures what this blog is about. We take mundane topics and push them just a little too far into the realm of fascinating, philosophical, and sometimes downright absurd.

### 🌟 Features

- **🌐 Bilingual Content** - English & Bengali (বাংলা)
- **☕ Coffee-Powered Analytics** - Every post comes with coffee consumption metrics
- **🎨 Modern Design** - Built with Hugo Brewm theme
- **📱 Responsive** - Looks great on all devices
- **🔍 Search Enabled** - Find chaos efficiently
- **🎭 Personality-Rich** - Because learning should never be boring

## 🛠️ Tech Stack

- **Generator:** [Hugo](https://gohugo.io/) (v0.147.3+)
- **Theme:** [Hugo Brewm](https://github.com/foxihd/hugo-brewm)
- **Languages:** English + Bengali (বাংলা)
- **Deployment:** Cloudflare Pages
- **CI/CD:** GitHub Actions

## 🚀 Quick Start

### Prerequisites

- Hugo Extended v0.147.3 or higher
- Git
- A dangerous amount of curiosity about random topics

### Local Development

```bash
# Clone the chaos
git clone https://github.com/yourusername/ektubeshi-series.git
cd ektubeshi-series

# Initialize theme submodule
git submodule update --init --recursive

# Serve locally (with coffee)
hugo server

# Visit your local chaos laboratory
open http://localhost:1313
```

### Building for Production

```bash
# Build the site
hugo --minify --baseURL "https://ektubeshi.dibakar.me"

# Output will be in ./public/
```

## 📁 Project Structure

```
ektubeshi-series/
├── content/
│   ├── en/                    # English content
│   │   ├── about/            # About pages
│   │   ├── author/           # Author profiles
│   │   ├── post/             # Blog posts
│   │   ├── _index.md         # Homepage
│   │   ├── slide.md          # Homepage slides
│   │   ├── rss.md           # RSS slide content
│   │   ├── pin.md           # Featured content
│   │   └── footer.md        # Footer content
│   └── bn/                   # Bengali content (same structure)
├── i18n/
│   └── bn.toml              # Bengali translations
├── themes/
│   └── hugo-brewm/          # Theme submodule
├── hugo.toml                # Main configuration
└── README.md               # You are here!
```

## ✍️ Content Creation

### Adding a New Post

```bash
# English post
hugo new content/en/post/your-chaotic-topic.md

# Bengali post
hugo new content/bn/post/your-chaotic-topic.md
```

### Post Template

```yaml
---
title: "Your Brilliantly Bizarre Topic"
description: "A short description that makes people curious"
date: 2025-01-26
lastmod: 2025-01-26
author: ['Dibakar']
coffee: 3                    # How many cups it took to write this
tags: ['chaos', 'wisdom']
categories: ['philosophy']
translationKey: 'your-topic' # Links translations
draft: false
---

Your caffeinated content goes here...
```

### Essential Frontmatter

- **`coffee`** - Number of cups consumed during writing (very important!)
- **`translationKey`** - Links English and Bengali versions
- **`author`** - Array of author names
- **`categories`** - Main topic categories
- **`tags`** - Specific topic tags

## 🌐 Multilingual Setup

The blog supports English and Bengali with the following structure:

- **English:** `/en/` - Default language
- **Bengali:** `/bn/` - Secondary language
- **Auto-switching** - Language picker in navigation
- **Linked translations** - Using `translationKey`

### Language Configuration

```toml
# hugo.toml
[languages]
  [languages.en]
    contentDir = 'content/en'
    languageCode = 'en-GB'
    languageName = 'English'
    
  [languages.bn]
    contentDir = 'content/bn'
    languageCode = 'bn-BD'
    languageName = 'বাংলা'
```

## 🎨 Customization

### Theme Features Used

- **Slides** - Homepage carousel with custom content
- **Pin Shortcode** - Featured content galleries
- **Coffee Stats** - Custom footer with consumption metrics
- **Author Pages** - Detailed author profiles
- **Search** - Pagefind integration

### Custom Modifications

- Enhanced footer with coffee statistics
- Bilingual slide content
- Custom author structure
- Ektubeshi-branded navigation

## 📊 Coffee Analytics

Every post includes coffee consumption data because:

1. **Transparency** - Readers deserve to know the dedication level
2. **Science** - We're collecting data on creativity vs. caffeine correlation
3. **Humor** - Because why not?
4. **Accountability** - Making sure we maintain optimal caffeination

Current stats: **47 cups this week** ☕

## 🚀 Deployment

### Cloudflare Pages (Recommended)

1. Connect your GitHub repository to Cloudflare Pages
2. Set build command: `hugo --minify`
3. Set output directory: `public`
4. Set Hugo version: `0.147.3`

### Manual Deployment

```bash
# Build
hugo --minify --baseURL "https://your-domain.com"

# Deploy the ./public/ folder to your hosting provider
```

## 🤝 Contributing

Found a typo? Have a bizarre topic suggestion? Want to contribute to the chaos?

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/more-chaos`)
3. **Commit** your changes (`git commit -m 'Add more caffeinated wisdom'`)
4. **Push** to the branch (`git push origin feature/more-chaos`)
5. **Open** a Pull Request

### Content Guidelines

- **Be curious** - Ask weird questions about normal things
- **Stay caffeinated** - Include accurate coffee counts
- **Keep it light** - Serious topics with a light heart
- **Bilingual bonus** - Bengali translations are highly appreciated
- **Cite sources** - Even for the most absurd claims

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Some rights reserved. Share the chaos responsibly.

## ☕ About the Author

**Dibakar** - Chaos Curator & Coffee Enthusiast

- 🌐 Website: [dibakar.me](https://dibakar.me)
- 📧 Email: [iamdibakardipu@gmail.com](mailto:iamdibakardipu@gmail.com)
- ☕ Coffee consumption: Professionally excessive

## 🐛 Known Issues

- May cause sudden urges to overthink mundane objects
- Increased coffee consumption (this is actually a feature)
- Inexplicable need to explain rubber duck debugging to confused family members
- Addiction to margin notes and coffee count statistics

## 🙏 Acknowledgments

- **Hugo Team** - For making static sites beautifully simple
- **Hugo Brewm Theme** - For the perfect chaos-friendly design
- **Coffee** - For obvious reasons
- **Rubber Ducks** - For inspiring debugging wisdom
- **Bengali Language** - For giving us the perfect word: একতুবেশী

---

**Warning:** This repository may contain traces of caffeine, existential questions, and an unhealthy obsession with connecting unrelated topics.

*Made with ☕ and অনেক love in the caffeinated corners of cyberspace.* 