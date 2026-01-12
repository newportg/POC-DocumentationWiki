# Quarto 
Quarto is an open-source scientific and technical publishing system that allows you to create dynamic content using Markdown and integrate executable code (Python, R, Julia, etc.) into your documentation. 

- GitHub Repo as Storage: Yes, this is Quarto's native approach. Your documentation is authored in plain-text Markdown files (or .qmd files) and stored directly in your GitHub repository alongside your code.
- Workflow: It fully embraces the "docs-as-code" philosophy. You use your standard development tools (VS Code, RStudio, command line) to edit files and the entire process (pull requests, code review, versioning) is managed via Git and GitHub.
- Publishing: Quarto can be published to a variety of destinations, including GitHub Pages, using the quarto publish command or automated with GitHub Actions.
- Best for: Highly technical teams who want documentation to be a seamless part of their existing engineering workflow and codebase, and require a high degree of customisation and the ability to embed code execution results. 