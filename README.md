# Job Circular Tracker

Track Bangladesh job circulars — government, bank, NGO and private — with a live countdown to every application deadline.

Live demo: https://nafiz-xd.github.io/job-circular-tracker/

## Features

- 10 sample Bangladesh job circulars (BPSC, Bangladesh Bank, Primary Education, Bangladesh Railway, BRAC, Grameen Bank, Square, Biman, Robi and more) with organisation, post name, vacancy, education required, salary in ৳, publish date and deadline
- Live "days left" countdown chips computed in JavaScript from each deadline — chips and the row's left border turn amber under 14 days and red under 7 days
- Category filter: Govt / Bank / NGO / Private, plus a Bookmarked view
- Bookmark (☆/★) toggle on every job, persisted in localStorage
- Click any row to expand full details: salary scale, job location, application fee and circular notes
- Header stats: open circulars, closing within 7 days, and your bookmark count
- Deep navy + teal professional design with dense list rows that slide in on load
- Fully responsive, works from `file://` and GitHub Pages with no build step

## Tech Used

- HTML5
- CSS3 (grid, keyframe slide-in animations)
- Vanilla JavaScript (live date/countdown computation)
- localStorage for bookmarks

Built by Nafiz Bin Azad
