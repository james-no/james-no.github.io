# James No · Portfolio

Personal portfolio site, hosted with GitHub Pages at https://james-no.github.io

## Files
- `index.html`: the whole site (About, Projects, Skills, Resume, Contact)
- `James_No_Resume.pdf`: downloadable resume

## Adding screenshots
1. Create a folder named `images/` and add PNG screenshots, for example `task-mentor.png`.
2. In `index.html`, inside a project's `<article>`, just above `<div class="evidence">`, add:

```html
<figure>
  <img src="images/task-mentor.png" alt="Task Mentor mentor search page showing filter options and results">
  <figcaption>Mentor search with multiple filters.</figcaption>
</figure>
```
