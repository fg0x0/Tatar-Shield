# Translation needed — Mongolian

A worklist, not a translation. **Nothing here has been machine-translated**, and
nothing should be: the Mongolian in this repo is written, and a transliterated
stand-in would be worse than an honest gap.

Generated 2026-09-30 by classifying every tracked `.md` as entirely English,
bilingual (has a `Монголоор` half), or mixed.

**Priority is about who reads the file.** This repo is unusual in the Tatar
family: its users are **Mongolian-speaking members of the public**, not
operators. A non-technical user who hits a false alarm on their own bank and
wants to report it should not meet an English form.

---

## High — end-user facing

| Section | File | Words | Note |
|---|---|---:|---|
| *(whole file)* | `.github/ISSUE_TEMPLATE/bug_report.md` | 74 | The path a real user takes to report "my bank's site shows a red warning". Short, and the highest-value 74 words in the repo — the people most likely to file this report are the least likely to read English comfortably. |
| *(whole file)* | `.github/ISSUE_TEMPLATE/feature_request.md` | 69 | Same audience: "please also cover this bank". |

**Subtotal ≈ 143 words.** Consider a bilingual template (both languages in one
file) rather than a separate Mongolian one, so GitHub's template picker stays
simple.

## Low — contributor-facing

| Section | File | Words | Note |
|---|---|---:|---|
| *(whole file)* | `.github/PULL_REQUEST_TEMPLATE.md` | 75 | Only someone opening a PR sees it. |
| Our Pledge / Our Standards / Enforcement Responsibilities / Scope / Enforcement / Attribution | `CODE_OF_CONDUCT.md` | 313 | **Do not hand-translate this.** It is the Contributor Covenant, which has an official Mongolian translation — use that rather than writing a second, divergent wording of a document whose exact phrasing is the point. |

---

## Deliberately *not* a gap

- **`docs/permissions.md`** (134 words) is written **for Chrome Web Store
  reviewers**, who read English. Translating it would serve nobody. It is
  English on purpose.
- **`docs/store-listing-en.md`** is the English store listing and has a
  Mongolian counterpart in `docs/store-listing-mn.md`.
- **`README.md` and `PRIVACY.md`** already carry a Mongolian half.
  `scripts/check-readme-parity.js` gates the README's two halves structurally in
  CI, so drift there is caught automatically.
- **`CONTRIBUTING.md`, `CHANGELOG.md`, `docs/recording-guide-mn.md`** are
  already Mongolian or mixed.

## If you translate one thing

The two issue templates — 143 words total, and they sit directly between a
worried user and the report that tells you a real bank is being flagged.
