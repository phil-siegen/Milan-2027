# Process Metaphysics and Biology – Milan 2027

Website of the summer school and workshop, 6–10 September 2027, Università degli Studi di Milano.
Static HTML site hosted on GitHub Pages – no build step, no Jekyll.

## Editing text
Each page is one HTML file. Open it on github.com, click the pencil icon, change the text
between the tags (e.g. `<p>…</p>`), then "Commit changes". The site updates within 1–2 minutes.

| Page | File |
|---|---|
| Home | `index.html` |
| Summer School (incl. schedule, application, scholarships) | `summer-school.html` |
| Workshop (incl. schedule) | `workshop.html` |
| Speakers & Teachers | `speakers.html` |
| Venue & Travel | `venue.html` |
| Photos | `photos.html` |
| Contact | `contact.html` |
| Imprint / Privacy | `imprint.html`, `privacy.html` |

- Menu and footer appear in every file – a change there has to be made in all nine files.
- Schedule tables: each slot is `<td class="slot"><span class="what">Lecture</span><span class="who">Teacher tba</span></td>`.
  Replace "Teacher tba" with the name and "Lecture" with the title.
- Speakers/teachers: each person is a `<div class="person">…</div>` block in `speakers.html`.
  Put a square portrait into the repository root and reference it as `<img src="name.jpg" alt="Name">` inside `<div class="photo">`.
- Photos: upload JPGs into the repository root (next to index.html) and add a `<figure>` block in `photos.html` (copy an existing one).
- Dates are written as `6<sup>th</sup>` for the superscript ordinal.

## Design
Colours, fonts and layout live in `style.css`. Paper texture: `paper.jpg`; home-page artwork: `artwork.jpg`.
