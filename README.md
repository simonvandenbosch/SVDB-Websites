# SVDB Websites — static site

Plain static site, no build step. Deploy on Cloudflare Pages with:

- Build command: (empty)
- Build output directory: `/`

Settings in `index.html` (search for `const CFG`):

- `formKey`: Web3Forms access key for the contact form
- `psiKey`: Google PageSpeed Insights API key for the website check (restrict it to the PageSpeed API and to svdbwebsites.com)
