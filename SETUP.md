# GitHub profile README setup

1. Open https://github.com/Maiylsamy/Maiylsamy (create a **public** repository named exactly `Maiylsamy` if it does not exist).
2. Replace that repository's `README.md` with the supplied `README.md` and commit it to `main`.
3. Upload `.github/workflows/snake.yml` at the same path in that repository.
4. In the repository, open **Settings → Actions → General** and ensure workflows are allowed. Under **Workflow permissions**, allow read/write permissions if the workflow needs them; the workflow declares `contents: write`.
5. Open **Actions → Generate contribution snake → Run workflow** once. After it succeeds, the `output` branch should be created and the snake animation should load in the README.
6. If the animation is not visible immediately, give GitHub a minute and refresh the profile.

Notes:
- GitHub README files support Markdown and externally hosted animated SVG/GIF images, but they do not execute custom JavaScript or CSS animations.
- The stats and typing animations use third-party image services, so they can occasionally be slow or unavailable.
- The README links SecureAuth API to `https://github.com/Maiylsamy/project-one`, based on the repository URL provided.
