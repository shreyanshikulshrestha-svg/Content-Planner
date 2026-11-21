# ITI Content Planner

A simple web app to plan Instagram posts, track them through a review workflow, and measure how they performed. I built it from my one-month Digital Marketing internship at S. P. Upadhyay I.T.I. (ITI College), Agra, where I designed posts in Canva and shared them on Instagram.

## Why I built it

During the internship, every post followed the same cycle: plan, create, review, publish, document and analyse. This tool puts that workflow in one place, so posts are not lost and results can be compared.

## Features

- **Calendar view:** see all planned posts by date, tap a day to view or add posts.
- **Workflow board:** four stages (Draft, In review, Approved, Posted) with one-click "Move to next stage".
- **Post details:** title, date, format (Poster, Reel, Story, Carousel), who checked it, and caption notes.
- **Performance tracking:** for posted content, enter reach, likes, comments and link clicks.
- **Analysis:** total reach, average engagement rate, reach per post, and the best-performing format.
- **Report summary:** copy a ready-made summary into an internship report.
- **Light and dark mode:** follows your device theme.
- **Works on mobile:** the layout adapts to phone screens.

Engagement rate is calculated as `(likes + comments) ÷ reach × 100`.

## Tech stack

| Part | Technology |
| --- | --- |
| Structure | HTML5 |
| Styling | CSS3 (grid, flexbox, custom properties) |
| Logic | Vanilla JavaScript (no frameworks or libraries) |
| Storage | Browser `localStorage` |

## How to run

1. Download or clone this repository.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox).

No installation, server or internet connection is needed. Fonts load from Google Fonts when online, and a default font is used offline.

```bash
git clone https://github.com/<your-username>/iti-content-planner.git
cd iti-content-planner
# then open index.html in your browser
```

## How to use

1. Click **New post**, enter the title, date and format, and save.
2. Open the **Board** tab and move the post from Draft to In review to Approved as it is checked.
3. After publishing on Instagram, move it to **Posted** and enter the numbers from Instagram Insights.
4. Open the **Performance** tab to see results and copy the summary.

When you first open the app, it shows example posts with made-up numbers. Click **Clear examples** to start with your own data.

## Project structure

```
iti-content-planner/
├── index.html    # the whole app (HTML, CSS and JavaScript in one file)
└── README.md
```

## Limitations

- Data is stored only in your browser, so it does not sync between devices and is lost if site data is cleared.
- Instagram numbers are entered by hand. The app does not connect to Instagram.

## Future improvements

- User login and a database (for example, Firebase or MySQL) so data is saved online
- Exporting posts and performance data to Excel or PDF
- Pulling numbers automatically from the Instagram API
- Reminders for upcoming post dates
- Charts of reach over time

## Author

**Shreyanshi Kulshrestha**
BCA, Sharda University, Agra
Digital Marketing Intern, S. P. Upadhyay I.T.I. (ITI College), Agra (1 to 30 June 2026)

GitHub: [@your-username](https://github.com/your-username)
