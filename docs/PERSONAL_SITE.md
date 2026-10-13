# Haoyu Wang — al-folio Personalization Notes

This repository uses the upstream [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme. The original template build system, GitHub Actions and dependencies are retained.

## Editorial direction

This is a research homepage, not a paper results page or a job résumé. Frame content as **motivation / research questions** followed by **ideas / possible approaches**. In underwater robotics, perception, control, and self-evolution are the research focus; reinforcement learning (such as PPO), Koopman models, and MPC are possible methods. AI agent interests center on harness design, memory, retrieval, and multi-agent coordination. Do not publish experimental scores or unverified capabilities at this stage.

## Maintained pages

- `_pages/about.md` — homepage and biography
- `_pages/research.md` — motivation, research questions, and possible approaches
- `_pages/projects.md` + `_projects/{text2ifc,weagent,easykoopman}.md` — concrete research explorations
- `_pages/experience.md` — education and two completed internships
- `_config.yml` — site identity, domain, display options and sample-content exclusions
- `_data/socials.yml` — public social links
- `_bibliography/papers.bib` — no publication entries until verified

## Deliberate exclusions

The initial al-folio template ships with example Einstein publications, placeholder projects, sample posts, fictional profile data, and demo pages. These are not the site owner's work. The `exclude:` section of `_config.yml` prevents example projects, posts/news, CV, publications, teaching and several other demo pages from being published. The example source files are retained upstream in Git for reference; do not present them as personal work.

## Future updates

- Add a verified profile photo, email and specific internship dates.
- Add WeAgent source, architecture and demo once reviewed.
- Add an actual CV PDF only after finalizing the job-search résumé.
- If research notes are ready, remove `_posts/` and `_pages/blog.md` from exclusions and enable blog navigation.
- When publications are confirmed, add properly verified BibTeX entries and enable the publications page.
- The site URL is `https://770122whrt.github.io` and `baseurl:` must remain empty.
- GitHub Actions builds the site and publishes to the `gh-pages` branch; configure GitHub Pages to serve that branch.

Project pages are intentionally motivation- and method-oriented. Publication and evaluation claims can be added when independently verified.
