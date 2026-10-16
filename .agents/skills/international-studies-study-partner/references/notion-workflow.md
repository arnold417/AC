# Notion workflow

## Use the existing workspace

Distinguish a request for advice about Notion, reading a note, saving a new note, editing a named note, or building a database. Mentioning Notion does not authorize reorganizing the workspace. Once the user requests a concrete save or update, carry it out within that scope without a redundant approval round.

Use the exposed Notion connector tools and their current schemas; prefixes vary. Check available tool access once when relevant and reuse the map. Use an available content-search tool with specific terms and a known course/page scope. Do not assume availability of advanced search, filters or multi-database queries; use the current access map.

Fetch supplied page URLs directly. For a named existing target, use the learner-profile links or a bounded search and fetch the matching result. Search matches can be irrelevant; verify title, parent and content. When multiple plausible targets remain, ask one targeted question and finish the draft while placement is pending. Do not overwrite a similar-looking page or create a replacement for an inaccessible named destination.

For a new save with no named destination, use an established, suitable course page. If none is established and current `create_pages` supports private draft mode, create a private draft and report that placement; do not block a requested save on folder selection. Do not move or share it without direction. If writes are unavailable, provide copy-ready content and clearly say it has not been saved.

## Preserve structure and source fidelity

Fetch the target before editing and inspect truncation, unknown blocks and material child pages. Do not rewrite unread sections. Read `notion://docs/enhanced-markdown-spec` through Notion fetch before producing page content; it is a documentation URI, not a web URL.

Use native page mentions for links to existing Notion notes and standard links for external sources according to that specification. A `<page>` block with an existing URL can move a child page; it is not an ordinary reference. Preserve existing child-page/database blocks, synced content and unrelated sections.

Create new notes as children of a confirmed course page, or records under a confirmed data source. For an existing database, fetch its schema and the correct collection/data-source ID; use actual property names, options and relation values. A database ID is not interchangeable with a data-source ID. Do not add properties or change types merely to fit the suggested layout below.

For updates, make the smallest complete targeted edit using current tool support. Append a requested supplement or update a named derived section; do not replace the entire page for a local change. Transformations should preserve the original capture or its link. A request to summarize a page normally produces a separate summary or updates its designated summary section, not a replacement of all source notes.

Before creating a new note, check the intended parent/database for an obvious match using source identity, title and course. Similar titles alone do not prove duplication. If a matching record already serves the exact request, update the requested derived content or clarify a consequential ambiguity. Never delete duplicates automatically.

If an operation times out or returns an uncertain result, check the resulting state before retrying. When a tool returns an asynchronous task, follow its supported status tool to confirmed success before dependent work. Retain successful page IDs and resume only unfinished operations. For a structured edit, read back the page and check headings, tables, links and source preservation. Return the actual page URL and an accurate save status.

Do not create comments or notify collaborators unless asked; a note-save request is not a request to send messages.

## Suggested organization when asked to build it

A simple page hierarchy is sufficient for ordinary notes: one course page with reading notes, lecture notes and synthesis pages underneath. Begin by reusing it. A database is useful if the student wants cross-course filtering or a reading queue; it is optional, not a prerequisite for any of the six roles.

For a requested new database, one **Study Notes** database can hold a coherent note per row. Suggested fields:

| Field | Type and use |
|---|---|
| Name | Title of the note |
| Course | Select using the learner's confirmed course names; add options only when needed |
| Type | Select: Lecture, Reading, Concept, Comparison, Synthesis, Topic idea |
| Source URL | URL to a primary source if available; multiple source links belong in the body |
| Week | Optional number supplied by the user or course materials |
| Needs clarification | Checkbox for an actual unresolved learning question |

Useful views are By course, Reading notes, and Open questions, with filters built from real properties. Additional relations, statuses and formulas should solve an expressed need. Do not infer that a student has read or mastered a source from an AI-generated summary. Do not promise templates or views that the current tools cannot create.

This is a proposed structure, not a database already created or a schema to impose on existing notes. Ordinary study notes are content, not reusable Notion skill pages; do not mark them as skills.
