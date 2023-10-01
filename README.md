# Resume Generator

This resume generator uses [showdownjs](https://showdownjs.com/) which takes a markdown file and converts it into HTML, and then it allows you to customize the styles to your heart's content.

This can be a good solution for those who use note-taking apps that support Markdown, such as Notion.io, Obsidian, or writing in Markdown in a code editor / IDE. The main advantage is you have more control over styling, and the styling and the content are separate from each other, and the styling stays consistent.

## Workflow

1. You may export your resume from your note taking app as a Markdown file, and then transfer it into the resume folder, naming it `resume.md`.
2. Edit the stylesheet at `resume-styles.css`.
3. Run `npx http-server` and view it in your browser at localhost:8080.
4. Run `cmd` + `p` or `ctrl` + `p` and save as PDF or print from your printer.
