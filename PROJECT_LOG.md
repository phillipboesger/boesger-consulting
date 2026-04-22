# Project Log

Most recent entries appear first. Older entries may be moved to PROJECT_LOG_ARCHIVE.md.

---

<!-- entries below -->

## 2026-04-22 — Updated About/Services website copy and removed the mistaken PDF-export path

**Branch**: copilot/update-website-for-portfolio
**What was done**: Rewrote the actual website content pages to reflect the new positioning around Bösger Digital, Polarion consulting, AI orchestration and "More AI, less manual work." after clarifying that the requested result was a website update, not a generated PDF. Removed the temporary PDF export implementation and verified that only the intended site changes remain.
**Changed files**:
- `content/about.md` — updated the About page copy to the current positioning and mission
- `content/services.md` — updated the service offering and value proposition copy
- `PROJECT_LOG.md` — recorded the durable outcome of the content migration and cleanup
**New knowledge**:
- Homepage positioning lives in `config.toml`, but About and Services page messaging must be updated in `content/about.md` and `content/services.md`
- A request mentioning a PDF may refer to the source content rather than the desired output format; confirm the target artifact before adding export tooling
**Open / Next steps**:
- Optional: review the remaining visual/content diffs together before committing the branch

---

## 2026-04-22 — Updated profile and resume copy from public LinkedIn signals

**Branch**: copilot/update-website-for-portfolio
**What was done**: Refined the site profile messaging to better match the publicly visible LinkedIn positioning around Polarion expertise, AI orchestration and reducing manual work. Updated the current freelance role, avasis role descriptions, and Polarion/GenAI skill narratives in the central config.
**Changed files**:
- `config.toml` — updated hero tagline/description, current freelance positioning, avasis role descriptions, and Polarion/GenAI skill copy
**New knowledge**:
- Public LinkedIn access for this profile exposes the company, websites, about teaser and post themes, but not the full profile text without sign-in
- The site's profile, career and skill narratives are all sourced from `config.toml`
**Open / Next steps**:
- If exact private LinkedIn wording should be mirrored, the hidden About/Experience text must be pasted manually

---

## 2026-04-22 — Reworked homepage hero around the LinkedIn banner motif

**Branch**: copilot/update-website-for-portfolio
**What was done**: Updated the homepage hero to use the user's AI/network visual language, adopted the banner motto "More AI, less manual work.", and enabled a site-wide background image. Added a dedicated CSS override import to force Hugo/PostCSS to emit the darker background overlay after verifying the live bundle was still serving stale overlay values.
**Changed files**:
- `config.toml` — enabled the background image and aligned the homepage vision copy with the banner motto
- `layouts/partials/hero.html` — replaced the old centered hero with a split layout, stronger messaging, CTA block, banner visual, and profile card
- `layouts/partials/header.html` — improved header contrast for pages using the global image background
- `assets/css/site.css` — adjusted the intended background overlay values for the site image treatment
- `assets/css/styles.css` — imported the dedicated override stylesheet so the CSS entry point changes invalidate the generated bundle
- `assets/css/site-overrides.css` — added the effective dark overlay rules that are now present in the live CSS bundle
**New knowledge**:
- Hugo in this repo serves CSS from `assets/css/styles.css`, not directly from `assets/css/site.css`
- Changing an imported CSS file alone may not invalidate the generated Hugo/PostCSS bundle reliably; changing the entry point import chain does
- Visual validation against the live local bundle was necessary because source edits and rendered CSS temporarily diverged
**Open / Next steps**:
- Optional: fine-tune desktop spacing of the right-side visual card if a more balanced two-column hero is desired on very wide screens

---