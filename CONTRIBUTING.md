# Contributing to Kaal-Pillar

Thank you for your interest in contributing to the Kaal-Pillar concept document!
This is a **text-based project**. We welcome editorial corrections, structural
improvements, and philosophical additions that align with the community's
vision.

## How to Contribute

### 1. Discuss Before Major Changes

If you are planning to make a significant structural or philosophical change,
please open a **Content Proposal** issue first to discuss your ideas with the
community. For minor editorial changes (typos, grammar), feel free to open a
Pull Request directly.

### 2. Trunk-Based Development Flow

We follow a lightweight **Trunk-Based Development** flow for this repository.
This means we prefer small, frequent updates that are merged directly into the
main branch (`main`), rather than long-lived feature branches.

**Example Flow:**

1. **Ensure your local `main` is up to date:**

   ```bash
   git checkout main
   git pull origin main
   ```

2. **Create a short-lived branch for your specific change:**

   ```bash
   # Branch names should be descriptive and concise
   git checkout -b editorial/fix-typo-section-2
   # OR
   git checkout -b content/expand-finance-section
   ```

3. **Make your changes, focusing only on the specific task.** Keep commits small
   and focused.

   ```bash
   git add index.html README.md
   git commit -m "docs: correct typo in section 2 regarding time"
   ```

4. **Push your branch and open a Pull Request:**

   ```bash
   git push origin editorial/fix-typo-section-2
   ```

5. **Merge quickly.** Once approved, the PR should be merged into `main` and the
   branch deleted.

### 3. Formatting Standards

We use **Prettier** to ensure consistent formatting across HTML and Markdown
files.

- Before submitting your PR, please ensure your changes do not violate
  formatting rules.
- If you have Node.js installed, you can format your files by running
  `npx prettier --write .` in the repository root.
- Our CI pipeline will automatically check formatting on all Pull Requests.

### 4. Tone and Style

- Maintain a formal, philosophical, and professional tone.
- Avoid using first-person pronouns ("I", "we") in new additions unless
  absolutely necessary for the founder's perspective.
- Ensure any added HTML follows the existing structural layout (e.g., using
  `<h3>` for subsections, `<blockquote>` for philosophical quotes).

## Code of Conduct

By participating in this project, you agree to abide by our
[Code of Conduct](CODE_OF_CONDUCT.md). Please treat all contributors with
respect, especially during philosophical debates.
