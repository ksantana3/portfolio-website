# Kyle Santana — Portfolio Website

Source for my personal portfolio site, live at **[kylesantana.com](https://kylesantana.com)**.

It's a single-page site that introduces who I am as a full-stack developer and data analyst, shows off a selection of software and data science projects, lists my certifications, and gives visitors a way to get in touch.

## What's on the site

### About
A short introduction — a team-oriented full-stack developer with hands-on experience in Python, MERN, and C# stacks, plus a background in data analysis and visualization — with links to my [LinkedIn](https://www.linkedin.com/in/kylesantana/), résumé, [GitHub](https://github.com/ksantana3/), and [DataCamp](https://www.datacamp.com/profile/ksantana3) profiles.

### Software Development Portfolio
Full-stack web apps, automation tools, and OCR work.

| Project | Built with | What it does |
| --- | --- | --- |
| [**Activity Planner**](https://github.com/ksantana3/Activity_Center) | C#, ASP.NET Core, Entity Framework Core, SQLite | Users sign up, create activities, and join activities posted by others. Includes login validation, hashed passwords, sessions, and one-to-many and many-to-many data relationships. |
| [**Pet Shelter**](https://github.com/ksantana3/pet-shelter) | React, Node.js, Express, MongoDB, AWS EC2 | MERN-stack app for managing shelter pet profiles, with photo uploads and full create/read/update/delete over a REST API. |
| [**Travel Buddy**](https://github.com/ksantana3/django_travel_app) | Python, Django, SQLite | Users post travel plans and join trips planned by others. Includes login validation, Bcrypt password hashing, sessions, and related data models. |
| [**Django Project Scaffolder**](https://github.com/ksantana3/django_file_structure) | Python, Batch | Sets up a new Django app's folder structure automatically. It started as a batch script and grew into a Python tool. |
| [**Task List**](https://github.com/ksantana3/task_list) | React | Lightweight to-do app: add and remove tasks, and check or uncheck them. |
| [**Receipt Parser**](https://github.com/ksantana3/receipt_parser) | Python, Tesseract OCR | Takes a photo of a receipt, converts it to text with Tesseract OCR, and runs a custom parser to strip the noise from the result. |

### Data Science Portfolio
Data wrangling, statistical analysis, and visualization.

| Project | Built with | What it explores |
| --- | --- | --- |
| [**We Rate Dogs**](https://nbviewer.jupyter.org/github/ksantana3/Twitter_Analysis/blob/master/we_rate_dogs_analysis.ipynb) | Python, pandas, NumPy, Twitter API | Gathers, cleans, and analyzes the @dog_rates Twitter archive from three sources: the tweet archive, neural-network breed predictions, and retweet and favorite counts from the Twitter API. |
| [**Red Wine Quality**](http://rpubs.com/ksantana/redwine) ([code](https://github.com/ksantana3/R_Red_Wine/blob/master/R_Red_Wine.rmd)) | R, dplyr, ggplot2 | How chemical properties like alcohol content, chlorides, and sulphates relate to a wine's quality rating. |
| [**Titanic Survival**](https://public.tableau.com/profile/kyle.santana#!/vizhome/story_final_6/StoryTitanicsSurvival) | Python, pandas, Tableau | A Tableau story on how ticket class, age, and gender affected survival, using Kaggle's 891-passenger dataset. |
| [**Dr. Jekyll vs. Mr. Hyde**](https://github.com/ksantana3/Frequency_Analysis/blob/master/Dr_Jekyll_vs_Mr_Hyde_Word_Frequency.ipynb) | Python, NLTK, pandas | Word-frequency analysis to see which half of Stevenson's character gets mentioned more. Inspired by Hulk out-screening Bruce Banner in *Thor: Ragnarok*. |
| [**The Stroop Effect**](https://github.com/ksantana3/Stroop_Effect/blob/master/Test_a_Perceptual_Phenomenon_Kyle.pdf) | Python, pandas, NumPy | Hypothesis test of whether people name ink colors more slowly when the word spells a different color (e.g. "RED" printed in blue). |
| [**Let's Build a Liquor Store**](https://nbviewer.jupyter.org/github/ksantana3/Iowa_Liquor/blob/master/Iowa_Liquor.ipynb) | Python, pandas, NumPy | Uses Iowa's public liquor-sales data to recommend the best location for a new store. |

### Certifications
- CompTIA Security+
- CompTIA Network+
- CompTIA A+
- CompTIA Project+
- CompTIA Secure Infrastructure Specialist
- Udacity Data Analyst Nanodegree

### Contact
A contact form and email link for anyone who'd like to talk about a project or opportunity.

## Built with

- HTML, CSS/SCSS, and JavaScript
- [Bootstrap 4](https://getbootstrap.com/), jQuery, Font Awesome, and ScrollReveal
- Gulp for compiling SCSS and minifying assets
- Based on the [Start Bootstrap Agency](https://startbootstrap.com/template-overviews/agency/) theme

## Project structure

```
index.html        # The whole site (single page)
css/              # Compiled styles; changes.css holds my custom overrides
scss/             # Theme source styles
js/               # Site scripts, including the contact form handler
img/              # Project thumbnails, certificates, badges, and icons
mail/             # PHP contact form backend from the template
vendor/           # Third-party libraries (Bootstrap, jQuery, Font Awesome, etc.)
CNAME             # Custom domain for GitHub Pages
```

## Running locally

The site is static, so the quickest way to preview it is to open `index.html` in a browser.

For live reload while editing:

```bash
npm install
npm start
```

This runs `gulp watch`, which serves the site with BrowserSync and reloads on changes. Run `gulp` on its own to rebuild the CSS and JS.

## Deployment

The site is hosted on **GitHub Pages** from the `master` branch, with the custom domain `kylesantana.com` set in `CNAME`. DNS is managed through Cloudflare, and `ksantana.com` redirects to the main domain. Pushing to `master` publishes changes.

## License

The underlying theme is © Blackrock Digital LLC and released under the [MIT License](LICENSE). Portfolio content, images, and project write-ups are © Kyle Santana.
