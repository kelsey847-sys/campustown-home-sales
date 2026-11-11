# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```

## 2026-11-10: Build and polish the housing dashboard

- **Asked:** "Read AGENTS.md and docs/data_description_sheet.md first.

Build a simple, clean College Town Housing Market Dashboard using data/college_town_home_sales.csv.

The website should:

1. Show the median home sale price for each of the 18 cities and towns.
2. Include a horizontal bar chart comparing median prices.
3. Include a table with city names and median sale prices.
4. Exclude sales below $10,000 from the median calculations and clearly explain this rule on the page.
5. Format all prices in whole US dollars.
6. Have a professional, easy-to-read design.

Use plain HTML, CSS, and JavaScript, and keep the website compatible with GitHub Pages.

Do not modify the original files in the data/ folder. Keep the implementation simple and explain the changes you made."
- **Asked:** "can you make the site look a bit more profressional or will that mess stuff up:"
- **Agent produced:** A CSV-driven dashboard with a horizontal price chart, table, $10,000 sale-price cutoff, rounded whole-dollar prices, and a responsive visual redesign. The first draft used the data sheet's $1,000 cutoff; the assignment prompt specified $10,000, so the calculation was updated to match.
- **Checked or changed:** Confirmed the project instructions and data sheet were read, and the five original data files remain unchanged. The earlier dashboard commit went directly to `main` instead of through a pull request; this style and log update is being submitted as a pull request for review.
