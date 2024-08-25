# Application Web Design

## Student Information
- **Name:** Gildardo Rodriguez
- **Registration Number:** [03042096]
- **Degree:** Bachelor's Degree in Software Development Engineering
- **Semester:** 6th

## Subject Information
- **Subject:** [Diseño de aplicaciones web]
- **Professor:** [Jesús Alberto Garza Guerrero]

## What is Markdown?
Markdown is a lightweight markup language with plain text formatting syntax. Its main purpose is to allow users to write in an easy-to-read and easy-to-write plain text format, which can be converted into structurally valid HTML. It is often used for formatting README files, writing messages in online discussion forums, and creating rich text using a plain text editor.

## Markdown Tagging Options

Markdown offers several tagging options to format text, such as:

- **Headings**: Use `#` for headings. The number of `#` signs corresponds to the level of the heading (e.g., `#` for H1, `##` for H2).
- **Bold Text**: Use `**text**` or `__text__` to make text bold.
- **Italic Text**: Use `*text*` or `_text_` to italicize text.
- **Blockquotes**: Use `>` before a line to create a blockquote.
- **Lists**: 
  - **Unordered Lists**: Use `-`, `*`, or `+` followed by a space.
  - **Ordered Lists**: Use numbers followed by a period (e.g., `1.`, `2.`).
- **Code Blocks**: Use backticks `` `code` `` for inline code and triple backticks (```` ``` ````) for code blocks.
- **Links**: Use `[link text](url)` to create a hyperlink.
- **Images**: Use `![alt text](image_url)` to insert an image.

For more detailed documentation on Markdown, refer to the [Markdown Guide](https://www.markdownguide.org/).

## Common Git Commands

Here are some commonly used Git commands and their descriptions:

### Checking the Status of a Local Repository

To see the current state of your repository and any changes that have not yet been committed, use:

```bash
git status

Adding Files to the Staging Area
You can add files to the staging area (index) in Git:

Add an individual file: git add filename

Add all changes globally: git add .

Committing Changes with Comments
After staging your changes, create a commit with a message: git commit -m "Your descriptive commit message"

Pushing Changes to the Remote Repository
To upload your local repository changes to GitHub (or another remote repository), use: git push origin main

Creating, Browsing, and Deleting Branches
Create a new branch: git branch branch-name

Switch to a different branch: git checkout branch-name

Delete a branch: git branch -d branch-name

Rolling Back a Repository to a Specific Commit
To reset your repository to a specific commit, you can use:

Soft reset (keeps changes in your working directory): git reset --soft commit-hash

Hard reset (discards all changes): git reset --hard commit-hash

Conclusion
These commands and Markdown syntax guidelines should help you manage your repositories and documentation effectively. Use this README.md file as a future reference.

### Steps to Update Your README.md

1. **Open your README.md file**: You can use Notepad or any text editor of your choice.
2. **Copy the content above and paste it into your README.md file**.
3. **Save the changes**: Make sure to save the file after editing.
4. **Stage, commit, and push your changes** to the remote repository to update your README on GitHub.

#### Git Commands to Update Your README.md

1. **Stage the README.md file**:

   ```bash
   git add README.md

Commit the changes: git commit -m "Updated README.md with Git command references and Markdown options"

Push to the remote repository: git push origin main

 