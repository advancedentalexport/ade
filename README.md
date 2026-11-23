# Advance Dental Export — informational website

A small, responsive, informational website about Advance Dental Export (ADE) and general dental laboratory practice.

This is **not a promotional landing page**. Content is intentionally restrained, with no testimonials, advertisements, lead forms, unsupported metrics, or tracking scripts.

## Website pages

- `index.html` — About ADE, dental laboratory roles and common case-record formats.
- `materials.html` — General notes on zirconia, lithium disilicate, PFM, and implant-supported prosthetics.
- `workflow.html` — Typical case stages, laboratory prescription information, and FAQs.
- `styles.css` — Site design, layout, and mobile styles.
- `favicon.svg` — Simple text-based icon.

## Preview locally

Open `index.html` in any modern browser. No dependencies, package manager, build process, or server are needed.

## Publish using GitHub Pages

1. Create a new GitHub repository (for example, `ade-dental-info`).
2. Upload **the files inside this folder** to the repository root, including `index.html`, `materials.html`, `workflow.html`, `styles.css`, and `favicon.svg`. Do not upload only the ZIP archive.
3. Commit the files to the default branch, typically `main`.
4. Go to **Settings → Pages → Build and deployment**.
5. Set **Source** to **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. When GitHub Pages finishes publishing, the site is generally available at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

All internal links are relative, so this site works in a repository subdirectory on GitHub Pages.

## Editing

- Change page text directly in the `.html` files.
- Change colours, spacing, and typography in `styles.css`.
- Keep factual company details aligned with the official website.
- Update the footer's review date when information is rechecked.

## Information sources

Company details were checked against:

- [ADE official website](https://advancedentalexport.com/)
- [ADE About Us](https://advancedentalexport.com/about-us/)
- [ADE guide to dental impressions](https://advancedentalexport.com/blog/dentists-guide-to-dental-impressions/)

The materials and workflow sections are general educational descriptions, not product-specific clinical instructions or ADE performance commitments. Clinical decisions must account for patient-specific conditions and current manufacturer instructions.

## Notes

- No remote assets or third-party JavaScript.
- Mobile-responsive navigation and layouts.
- Semantic HTML, descriptive page titles and headings, keyboard focus styles, and reduced-motion support.
- No license is included; the repository owner can select a license if desired.
