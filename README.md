# asalroudbari.github.io

Personal website for Asal Roudbari. One static page, no build step.

## Put it online (GitHub Pages)

1. On GitHub, create a public repository named exactly `asalroudbari.github.io`.
2. Upload everything in this folder (keep the `images/` and `files/` folders as they are).
3. In the repository, open Settings, then Pages, and set the source to the `main` branch, root folder.
4. After a minute or two the site is live at https://asalroudbari.github.io/

Each section has its own link: `/#about`, `/#research`, `/#experience`.

## Updating the site

Everything is in `index.html`, and each part is marked with a comment.

- **News**: search for `NEWS:`. Copy one `<li>` line to the top of the list and edit the date and text.
- **Publications**: search for `class="pub"`. Copy one `<li class="pub">` inside the right thread
  (scoliosis, phenotyping, or earlier). Author names are written in full.
- **Experience**: copy one `<li>` inside the Research, Leadership, Education, or Awards list.
- **Photo**: replace `images/profile.jpg` (portrait crop, 4:5).
- **CV**: replace `files/Asal_Roudbari_CV.pdf`, same file name.
- **Banner drawing**: search for `COHORTS` in the script. Each entry is one option in the "Cohort" control;
  copy an entry (and add a matching button in the HTML) to add another disease or feature.
- **Colours and fonts**: the variables at the top of the `<style>` block.

## Still to add

- `images/logos/nodet.png` (about 200 px, square-ish). Until it exists, the initial "N" shows.
- Paper and code links for the NeurIPS workshop paper: search for `ARXIV_URL`.

## Logos

- `ai4opt.png`, `ai4opt-mark.png`, `shriners.png`: taken from your own posters.
- `crosslabs.png`, `aalto.png`: cut from the images you sent.
- `gatech.png`, `sharif.png`, `tehran.png`: taken from public GitHub repositories. Consider replacing them with
  the current files from each institution's brand page, keeping the same file names.

## Typeface

Three pairings are loaded so you can compare them with the "Typeface" control in the footer.
Once you choose, set `data-font` on the `<html>` tag (`modern`, `editorial`, or `classic`), delete the
"PREVIEW ONLY" row in the footer, and trim the unused families from the Google Fonts link.
