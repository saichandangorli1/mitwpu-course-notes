# Contributing to MITWPU – Course Notes Hub

Thank you for your interest in contributing!  
This project is owned and maintained by [`saichandangorli1`](https://github.com/saichandangorli1), with help from the community.

---

## Before you start

- Only add **academic, syllabus-aligned content** for MITWPU courses.  
- Do **not** upload copyrighted books, paid PDFs, or any sensitive personal data.  
- Follow the existing folder structure under `docs/` for programme, department, year, batch, and subject.

If you are unsure where something should go, open an issue or ask the maintainers.

---

## Standard workflow

1. **Fork the repository**

   - Click the **Fork** button on the top right of the GitHub page to create your own copy of this repo.

2. **Create a new branch**

   - In your fork, create a branch with a **descriptive name**, for example:  
     - `fix-typo-in-unit-2`  
     - `add-chapter-5-notes`  
     - `btech-cse-os-unit-3-update`

3. **Make your changes**

   - Navigate to the correct path under `docs/<programme>/<department-or-school>/<year>/<batch>/<subject>/`.  
   - You can add or edit files in the format best suited to the course:  
     - `.md`, `.txt`  
     - `.c`, `.cpp`, `.py`, `.java`, `.php`, `.js`  
     - `.ipynb` or other language / tool specific formats  
   - Keep formatting clean and consistent (headings, lists, code blocks, examples, important questions).

4. **Run your own checks**

   Before opening a Pull Request:

   - Use the templates and helper files in `demo-docs/lib/`:
     - `note-template.md` – copy this when creating a new note file so style stays consistent.
     - `validation-checklist.md` – quickly verify coverage, formatting, and basic quality.
   - You may draft or experiment in:
     - `contributor-only/` – personal or experimental content not yet ready for students.
     - `test/temp-notes/` – temporary or test notes that may be removed at any time.

5. **Submit a Pull Request (PR)**

   - Push your branch to your fork.  
   - Open a PR from your branch to the `main` branch of this repository.  
   - Clearly describe:
     - What you added/changed.
     - Which programme/department/year/subject it affects.
     - Any known gaps or TODOs.

6. **Review and merge**

   - The owner, [`@saichandangorli1`](https://github.com/saichandangorli1), will review your PR.  
   - PRs may be **merged**, **rebased**, or **squashed** into `main` after review.  
   - You might be asked to update your branch (for example, fix formatting, add references, or adjust structure) before approval.

---

## Folder overview for contributors

These folders exist to help you contribute more easily:

- `contributor-only/`  
  - Use for drafts, rough content, or experiments that are not yet ready for students.  
  - Content here is optional and may be cleaned up or deleted periodically.

- `demo-docs/examples/template.md`  
  - Example of a **finished note** file showing recommended structure (headings, sections, examples).

- `demo-docs/lib/note-template.md`  
  - Copy-paste base **template** for new subject/unit notes so that all notes look consistent.

- `demo-docs/lib/validation-checklist.md`  
  - Quick checklist to ensure your contribution is complete and ready (coverage, typos, formatting, links, etc.).

- `test/temp-notes/`  
  - Scratch area for testing structure or content.  
  - Anything here is considered temporary and may be removed or moved into `docs/` once finalized.

---

## Contact

For doubts, suggestions, or larger changes:

- Primary maintainer: [`saichandangorli1`](https://github.com/saichandangorli1)  
- Co‑maintainer: [`Satya-Siba-Nayak`](https://github.com/Satya-Siba-Nayak)

Please prefer opening an issue first for big structural or cross-programme changes.
