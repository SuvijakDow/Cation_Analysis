# Cation Analysis

A summary web flowchart for qualitative cation analysis, designed for browser viewing and A4 landscape printing.

## Project Structure

- `index.html` — Main web page (HTML, CSS, and JavaScript in a single file)

## Usage

1. Open `index.html` in your browser.
2. Use the on-page controls to toggle detail level and chemical equations.
3. To print, click `ปริ้น A4 (Browser Print)`.

## GitHub Push Best Practices

1. Create a dedicated branch for each change, such as `feat/update-flowchart` or `fix/print-layout`.
2. Keep commits concise, clear, and focused on one logical change.
3. Review your diff before every push (`git status` and `git diff --staged`).
4. Push with upstream tracking:
   ```bash
   git push -u origin <branch-name>
   ```
5. Open a Pull Request with:
   - What changed
   - Why it changed
   - How to validate it

## Suggested commit message format

Use Conventional Commits to keep history readable:

- `feat: add compact print controls`
- `fix: correct A4 landscape zoom in firefox`
- `docs: improve github push workflow`
