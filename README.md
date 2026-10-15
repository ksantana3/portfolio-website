# Kyle Santana — Portfolio Website

Source for my personal portfolio site, live at **[kylesantana.com](https://kylesantana.com)**.

It's a single-page site that introduces who I am as a full-stack developer and data analyst, shows off a selection of software and data science projects, lists my certifications, and gives visitors a way to get in touch.

## What's on the site

### About
A short introduction — a team-oriented full-stack developer with hands-on experience in Python, MERN, and C# stacks, plus a background in data analysis and visualization — with links to my [LinkedIn](https://www.linkedin.com/in/kylesantana/), résumé, [GitHub](https://github.com/ksantana3/), and [DataCamp](https://www.datacamp.com/profile/ksantana3) profiles.

### Software Development Portfolio
Front end, back end, database, and automation projects:

| Project | Stack | Description |
| --- | --- | --- |
| [Activity Planner](https://github.com/ksantana3/Activity_Center) | C#, ASP.NET Core | Registered users can plan activities and join activities created by others. |
| [Pet Shelter](https://github.com/ksantana3/pet-shelter) | React, MongoDB, Node.js, Express (hosted on EC2) | Full-stack CRUD app for managing pet profiles with photo uploads. |
| [Travel Buddy](https://github.com/ksantana3/django_travel_app) | Python, Django | Trip-planning app built on Django's MVC framework. |
| [Django File Structure Creator](https://github.com/ksantana3/django_file_structure) | Python | Automates creating the directory structure for a new Django project. |
| [Task List Tracker](https://github.com/ksantana3/task_list) | React | Simple task-list tracking app. |
| [Receipt Parser](https://github.com/ksantana3/receipt_parser) | Python, Tesseract OCR | Reads receipt images and extracts their contents. |

### Data Science Portfolio
Statistics, data wrangling, analytics, and visualization:

| Project | Description |
| --- | --- |
| [We Rate Dogs](https://nbviewer.jupyter.org/github/ksantana3/Twitter_Analysis/blob/master/we_rate_dogs_analysis.ipynb) | Wrangling and analysis of the @dog_rates Twitter archive. |
| [Red Wine Analysis](http://rpubs.com/ksantana/redwine) | Exploring which variables affect red wine quality (R). |
| Titanic Survivor Analysis | Visualizing passenger survival by class, age, and gender. |
| [Dr. Jekyll vs. Mr. Hyde](https://github.com/ksantana3/Frequency_Analysis/blob/master/Dr_Jekyll_vs_Mr_Hyde_Word_Frequency.ipynb) | Word-frequency comparison of how often each character is named in the novel. |
| [The Stroop Effect](https://github.com/ksantana3/Stroop_Effect/blob/master/Test_a_Perceptual_Phenomenon_Kyle.pdf) | Statistical test of a perceptual phenomenon. |
| [Let's Build a Liquor Store](https://nbviewer.jupyter.org/github/ksantana3/Iowa_Liquor/blob/master/Iowa_Liquor.ipynb) | Using Iowa liquor sales data to find an optimal store location. |

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
