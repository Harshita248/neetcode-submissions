# 🤝 Contributing to `neetcode-submissions`

> *Every solution counts. Every language welcome.*

Thank you for taking the time to contribute! Whether you're adding your first solution or your fiftieth — you belong here. This guide walks you through everything you need to get your contribution merged cleanly.

---

## 📜 Code of Conduct

By contributing, you agree to keep this a welcoming space for everyone:

- Be respectful and constructive in reviews and comments
- No plagiarism — submit only solutions you've written and understood
- If you referenced an editorial, video, or post, credit it in your comment block
- Full guidelines: [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)

---

## 🚀 How to Contribute

### Step-by-step with git commands

**1. Fork the repository**

Click **Fork** at the top-right of this page to create your own copy.

**2. Clone your fork locally**

```bash
git clone https://github.com/<your-username>/neetcode-submissions.git
cd neetcode-submissions
```

**3. Create a branch**

Use this naming format: `add/<problem-name>-<language>`

```bash
git checkout -b add/two-integer-sum-python
```

**4. Add your solution in the correct folder**

Follow the folder structure — see [File Naming Convention](#-file-naming-convention) below.

**5. Commit your changes**

```bash
git add .
git commit -m "add: two-integer-sum solution in python"
```

**6. Push and open a Pull Request**

```bash
git push origin add/two-integer-sum-python
```

Then go to your fork on GitHub and click **Compare & pull request**.

---

## 🗂️ File Naming Convention

| Rule | Detail |
|---|---|
| **Follow existing pattern** | Files must be named `submission-0.<ext>`, `submission-1.<ext>`, etc. |
| **Problem folder** | Use the exact NeetCode problem slug (e.g., `two-integer-sum`, `binary-search`) |
| **Topic folder** | Must match an existing folder exactly — do **not** create new topic folders |
| **No restructuring** | Do not rename, move, or restructure any existing folders or files |

**Valid folder path example:**
```
Data Structures & Algorithms/two-integer-sum/submission-0.py
```

**Existing topic folders:**
- `Data Structures & Algorithms`
- `Python For Beginners`

> When in doubt, match the folder name exactly as it appears in the repo.

---

## ✅ Solution Quality Guidelines

### Code must be accepted

Your solution should pass on [NeetCode.io](https://neetcode.io) or [LeetCode.com](https://leetcode.com). Include your runtime/memory stats in the comment block if available — it's helpful context.

### Required comment block

Add this at the top of **every** solution file. Adapt the syntax to your language (e.g., `//` for Java/C++, `#` for Python).

```python
# Problem: Two Integer Sum
# Difficulty: Easy
# Time Complexity: O(n)
# Space Complexity: O(n)
# Approach: Use a hash map to store seen values and check for complement on each iteration.
# Runtime: 57ms | Memory: 16.4MB  (optional but appreciated)
```

### On AI-generated code

Do not submit code you haven't read, understood, or can explain. Reviewers may ask questions about your approach in the PR — that's a normal part of the process, not gatekeeping.

---

## 🏷️ PR Title Format

```
[ADD] <Problem Name> - <Language>
```

**Examples:**
- `[ADD] Two Sum - Python`
- `[ADD] Binary Search - TypeScript`
- `[ADD] Merge K Sorted Lists - Java`

---

## 📋 PR Description Template

Paste this into your PR description and fill it out:

```markdown
## Problem
<!-- Link to the NeetCode or LeetCode problem -->

## Language
<!-- Python / JavaScript / TypeScript / Java / C++ / C# / Go / Rust / Kotlin / Swift / SQL -->

## Approach
<!-- Brief explanation of your solution strategy -->

## Complexity
- Time: O(?)
- Space: O(?)

## Checklist
- [ ] Solution is accepted on NeetCode / LeetCode
- [ ] File placed in the correct topic and problem folder
- [ ] Comment block added at the top of the file
- [ ] Branch is named correctly (`add/<problem-name>-<language>`)
- [ ] No existing files were modified or renamed
```

---

## 🚫 What NOT to Do

- **Don't submit untested code** — unaccepted solutions will not be merged
- **Don't modify other contributors' solutions** — open a new `submission-N` file instead
- **Don't add a duplicate solution in the same language** unless it's a genuinely different approach — if so, mention it clearly in the PR description
- **Don't paste the problem statement** — that's copyrighted content; a link is enough

---

## 🌱 First Time Contributing to Open Source?

No worries — this is the perfect repo to start with. Small, structured, low-risk.

These resources will help:
- [First Contributions Guide](https://firstcontributions.github.io/) — a beginner-friendly walkthrough
- [How to Fork a Repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo) — GitHub's official guide

You've got this. Open that first PR. 🙌

---

## 🏆 Recognition

All contributors are listed in [README.md](./README.md#-contributors) and appear in [GitHub's contributor graph](https://github.com/Harshita248/neetcode-submissions/graphs/contributors).

Your work is visible, credited, and appreciated — every merged solution is part of the record.

---

*Questions? Open an issue or drop a comment in your PR. Happy grinding!*
