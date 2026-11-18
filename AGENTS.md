# Project guidelines

These instructions apply to every page of Balázs Pozsgay's research website.

## Design and content

- Use an absolutely minimal design throughout the website.
- Keep every background plain white. Use black text and links, with no accent colors, background images, gradients, or decorative elements.
- Include text only when necessary. Do not add filler, promotional copy, or invented content.
- The Welcome page is the home page and should contain only a few lines of text supplied or requested by the user.
- Provide simple text navigation at the top of every page. Welcome must always be first.
- Navigation links must have no underlines or bold styling, including the current page.
- Separate the top navigation from the page content with a thin horizontal black line.
- The current navigation contains exactly Welcome and AIrepo, in that order.
- Later, the website may have two or three special pages. Add them only when requested.
- The initial Welcome text is "research website of Balázs Pozsgay, upcoming".
- The initial AIrepo text is "AIrepo for Balázs Pozsgay, upcoming".
- Keep the implementation simple: static HTML and shared CSS, without a framework or JavaScript unless a requested feature needs it.

## AIrepo content and maintenance

- The AIrepo index lists topics. Each topic has its own page with a document list linking to document descriptions on that same page.
- At the top of each topic page's main content, show an italic "Project:" label, followed by the project heading on a separate line.
- After the project heading, show an italic "List of documents:" label before the numbered document list.
- At the bottom of each topic page, include a "back to main" link to the AIrepo index, separated from the content by generous spacing and a thin black horizontal line.
- Do not number topics in the AIrepo index or in project headings. Use numbered lists for documents within each topic, and repeat each document's number in its detail heading. Document numbering starts at 1 within each topic; keep the list and heading numbers consistent.
- Each document has a stable section anchor, the user's exact web title and short description, and a single "PDF" link to open its PDF. Do not add a separate download link. Store PDFs with the corresponding topic page.
- The agreed status labels are "Raw AI output", "Human guided draft", and "Manuscript". Use only the status supplied by the user.
- Prefix each document's status with "Status:", its addition date with "Date added:", and its description with "Description:". Set these prefixes in italics, keeping all text black.
- Record the actual local date when a document is first added, in YYYY-MM-DD format, unless the user supplies a different addition date. Preserve this date when editing an existing entry.
- Lean verification is separate from the document status. Add verification details and links only when supplied; a missing certificate does not establish a verification status.
- A document's web title is allowed to differ from its internal PDF title. This is explicitly accepted for "Square-root law for continuous time evolution" (`xxz_operator_entanglement_lower_bound.pdf`). Preserve the supplied PDF without editing it, and do not mention the title difference on the public page.
- Do not invent abstracts, version numbers, verification claims, or document dates. The user supplies the content; "Date added" records the actual addition date as described above.

## Working agreement

- Make changes only when the user specifically requests them.
- Keep website source in this directory, connected to `balazs-pozsgay/balazs-pozsgay.github.io`.
- Commit and publish only when the user explicitly asks. Pushing to `main` updates the live GitHub Pages website.
