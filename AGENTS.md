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

- The AIrepo index shows project codes and linked project titles in a simple, borderless two-column table, without bullets, numbering, or project descriptions. Each topic has its own page with a document list linking to document descriptions on that same page.
- On the AIrepo index, place an italic "List of projects:" label between the AIrepo heading and the project table.
- At the top of each topic page's main content, show an italic "Project:" label, followed by the project heading on a separate line.
- Below each project heading, show an italic "Description of the project" label. Put the user-supplied project description in a separate paragraph on the next line. Leave the text empty until supplied; do not invent project descriptions or add placeholder prose.
- After the project description, show an italic "List of documents:" label before the document list, with each entry prefixed by its permanent document identifier. Keep this structure consistent across all project pages.
- At the bottom of each topic page, include a "back to main" link to the AIrepo index, separated from the content by generous spacing and a thin black horizontal line.
- Include a "View on GitHub" link in the footer of the AIrepo index and each topic page, pointing to the corresponding folder in the GitHub repository.
- Do not number topics in the AIrepo index or in project headings. Assign each document a permanent identifier made from its project code and a number starting at 1: "SZM" for "Boundary modes, strong zero modes", and "OE" for "Operator entanglement in integrable spin chains". Current identifiers are SZM-1, SZM-2, SZM-3, and OE-1.
- Show the same explicit identifier before the title in both the document list and its detail heading, e.g. "SZM-2. Two dynamical boundary spins in the XXX chain". Hide automatic list markers to avoid duplicate numbering. Never renumber or reuse identifiers when reordering or removing entries; a new version of the same document retains its identifier.
- Within descriptions, cite other documents as clickable bracketed identifiers, e.g. "[SZM-1]", linking to their stable HTML section anchors. Use a fragment link within the same project and a relative project-page path plus fragment across projects. Preserve existing anchors even if document titles change; these references point to descriptions, not PDFs.
- Each document has a stable section anchor, the user's exact web title and short description, and a single "PDF" link to open its PDF. Do not add a separate download link. Store PDFs with the corresponding topic page.
- The agreed status labels are "Raw AI output", "Human guided draft", and "Manuscript". Use only the status supplied by the user.
- Prefix each document's status with "Status:", its addition date with "Date added:", and its description with "Description:". Set these prefixes in italics, keeping all text black.
- Add an optional "Acknowledgements:" paragraph below a document's PDF link only when explicitly requested, with the label in italics and the supplied text after it. Omit the entire paragraph when no acknowledgement is supplied.
- Record the actual local date when a document is first added, in YYYY-MM-DD format, unless the user supplies a different addition date. Preserve this date when editing an existing entry.
- Lean verification is separate from the document status. Add verification details and links only when supplied; a missing certificate does not establish a verification status.
- A document's web title is allowed to differ from its internal PDF title. This is explicitly accepted for "Square-root law for continuous time evolution" (`xxz_operator_entanglement_lower_bound.pdf`). Preserve the supplied PDF without editing it, and do not mention the title difference on the public page.
- Do not invent version numbers, verification claims, or document dates. Normally the user supplies document descriptions; draft them from the source documents only when explicitly requested. "Date added" records the actual addition date as described above.

## Working agreement

- Make changes only when the user specifically requests them.
- Keep website source in this directory, connected to `balazs-pozsgay/balazs-pozsgay.github.io`.
- Commit and publish only when the user explicitly asks. Pushing to `main` updates the live GitHub Pages website.
- All further changes are local-only by default. The user must explicitly identify which changes to publish; permission for an earlier publication does not authorize uploading later changes.
