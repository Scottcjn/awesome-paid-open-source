# Contributing to Awesome Paid Open Source

Thanks for helping improve this collection of resources about paid and
sustainable open source development. Contributions should keep the list useful,
curated, and easy to scan.

## What to Contribute

Good contributions include:

- Articles, talks, or essays about funding open source maintenance.
- Donation, grant, sponsorship, or payment platforms used by open source
  projects.
- Examples of open source projects with clear paid support, hosting, licensing,
  training, or sponsorship models.
- Foundations, programs, references, and definitions that help readers compare
  sustainability models.
- Corrections for broken links, outdated project names, spelling, or unclear
  descriptions.

Avoid adding pure advertising, referral links, unrelated startup directories, or
projects where the paid/open source relationship is not clear from the linked
source.

## Before Opening a Pull Request

1. Search `README.md` to make sure the link is not already listed.
2. Choose the most specific existing section for the entry.
3. Keep descriptions short and factual.
4. Prefer canonical project, article, or documentation URLs over tracking links.
5. For new categories, add a matching entry to the table of contents.

If you are unsure whether a resource belongs in the list, open an issue first so
the maintainers can discuss it.

## Entry Style

- Use Markdown bullets that match nearby entries.
- Start each entry with the resource name as a link.
- Include the author, organization, license, or project context when it helps the
  reader understand why the resource is relevant.
- Keep capitalization and punctuation consistent with the surrounding section.
- Do not add long commentary; this repository is a curated index, not a review
  site.

Example:

```markdown
- [Example Project](https://example.com) (MIT) offers paid hosting while keeping
  its self-hosted project open source.
```

## Local Setup

Install the Node dependencies before running the list checks:

```bash
npm install
```

The existing test script runs `awesome-lint`:

```bash
npm test
```

For documentation-only fixes that do not change list structure, also run:

```bash
git diff --check
```

## Pull Request Checklist

- The link resolves and points to the intended resource.
- The entry belongs in the selected section.
- The table of contents is updated if a new heading was added.
- `npm test` passes, or the pull request explains why it could not be run.
- `git diff --check` reports no whitespace errors.

Small, focused pull requests are easier to review. Keep unrelated link additions,
copy edits, and category changes in separate pull requests when possible.
