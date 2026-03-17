# Website Builder Skill

Build beautiful, minimal personal websites using the [Clean and Personal](https://github.com/debgotwired/clean-and-personal) template collection.

## Features

- **61 templates** across design styles, professional roles, and use cases
- **Data import** from LinkedIn PDFs, resumes, Twitter profiles
- **Conversational customization** - change colors, fonts, layouts through chat
- **Deployment guidance** - step-by-step Vercel deployment

## Installation

```bash
npx skills add debgotwired/website-builder-skill
```

Or install manually:

```bash
# Clone this repo
git clone https://github.com/debgotwired/website-builder-skill.git

# Copy skill to Claude Code
cp -r website-builder-skill/skills/website-builder ~/.claude/skills/
```

## Usage

1. Clone the template collection:
   ```bash
   git clone https://github.com/debgotwired/clean-and-personal.git
   cd clean-and-personal
   ```

2. Start Claude Code and say:
   - "I want to build a personal website"
   - "Help me create a portfolio site"
   - "Build me a dark mode developer website"

3. Claude will:
   - Ask about your profession and preferences
   - Recommend 2-3 templates
   - Help customize colors, fonts, and content
   - Guide you through deployment

## Template Categories

| Category | Templates | Description |
|----------|-----------|-------------|
| Core | 01-10 | Founder, Developer Dark, Scholar, Minimal, Blog, Resume, etc. |
| 2026 Design Trends | 11-21 | Bento Grid, Glassmorphism, Y2K Retro, Brutalist, Swiss, etc. |
| Professional Portfolios | 22-30 | Software Engineer, UI/UX Designer, Freelancer, etc. |
| Layout Innovations | 31-40 | One-Page Scroll, Split Screen, Timeline, Masonry Grid, etc. |
| Purpose-Driven | 41-50 | Job Seeker, Startup Founder, Podcast Host, Newsletter, etc. |
| Premium Designs | 51-61 | Signature Minimal, Scrollytelling, AI Founder, Knowledge Base, etc. |

## Example Workflow

```
You: I want to build a personal website

Claude: What's your profession and do you prefer light or dark mode?

You: I'm a software engineer, prefer dark mode

Claude: I recommend 02-developer-dark - terminal aesthetic with neon green on black.
Should I set it up?

You: Yes! And here's my LinkedIn PDF

Claude: I extracted your info. Ready to customize - what would you like to change?

You: Make the green brighter and add my GitHub projects

Claude: Done! Ready to deploy to Vercel?
```

## Links

- [Clean and Personal Templates](https://github.com/debgotwired/clean-and-personal)
- [Live Demo](https://clean-and-personal.vercel.app)

## Author

[@debgotwired](https://github.com/debgotwired)

## License

MIT
