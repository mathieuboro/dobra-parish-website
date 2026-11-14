# Dobra Parish Website

This is the website of the Parish of the Nativity of the Blessed Virgin
Mary in Dobra, a town near Turek in Greater Poland. I made it for the parish,
and it's live at
**[parafianmp-dobra.pl](https://parafianmp-dobra.pl/)** (in Polish).

The source code lives in a private repository on the parish's GitHub
account, so this repository only describes the project: what the site
does and why it looks the way it does.

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/415c413d-28be-4a39-9239-7ee3259f8591"
    alt="Desktop homepage with a drawing of the parish church above the week's liturgical calendar"
    width="720"
  />
  <br>
  <sub>The homepage on a computer: the parish church above this week's liturgical calendar.</sub>
</p>

## Who it's for

People come to a parish website to check when Mass is, what was in this
week's announcements, when the office is open or what they need for a
sacrament. They are of all ages, and not all of them are comfortable
online, so the design puts readability and quick answers first:

- Headings are big, so you can tell where you are on the page at a glance.
- The type is easy to read and has plenty of space around it.
- Dates, times and places stand out most, especially for Masses, services
  and announcements.
- The colours stay quiet: warm backgrounds, dark text and gold accents.
  The calendar is the exception, because each day shows its liturgical
  colour.
- The church at the top of the homepage is a drawing of the real church
  in Dobra.
- On a phone everything gets simpler. The calendar becomes a row of days
  with the chosen day open below it, and links and information are
  rearranged to fit a narrow screen.

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/22ab73dc-8eff-4beb-a30a-85cd52acb16e"
    alt="Mobile liturgical calendar with a row of days and the selected day's details"
    width="280"
  />
  <br>
  <sub>On a phone: pick a day to see its Masses and readings.</sub>
</p>

## What's on the site

The homepage has what people check most often: the liturgical calendar,
Mass times, the parish office, the latest announcements and news.
Everything else has its own page:

- Masses, services and confession
- Parish announcements and Mass intentions
- News and community events
- The sacraments and how to prepare for them
- Parish office hours and contact details
- The parish, its history and local traditions
- The parish cemetery

## Interactive details

- The church is an animated SVG drawing, and the clock on its tower
  shows the real time.
- Click the church doors and they open onto a photo of the real interior.
- Pick any day in the calendar to see its Masses and a link to that day's
  readings.
- The parish office hours show whether the office is open right now.
- Announcement scans open full screen and can be zoomed in.
- For some celebrations the site changes its look and shows a notice, as
  it did for All Saints' Day.

## Updating content

Parish staff edit announcements, news and the rest of the content in
Pages CMS, without touching the code. The content is stored in GitHub.
When something changes, a Node.js build script turns it into static pages
and Cloudflare Pages publishes them.

## How I built it

I made the site with the help of AI tools for exploring designs, writing
code and testing. My part was:

- deciding what the site needs and what matters most
- setting the visual direction and the structure of the content
- reviewing the proposed designs and interactions, and refining them
- collecting feedback from the parish
- deploying the site and keeping it up to date

I still work on it. Some changes come from the parish's feedback, and
some from my own ideas for making the site clearer and easier to use.

## Technology

- HTML, CSS and JavaScript
- Node.js to generate the static site
- Pages CMS for editing content
- GitHub for the source code and content
- Cloudflare Pages for hosting and deployment
