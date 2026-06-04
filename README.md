![Last Commit](https://img.shields.io/github/last-commit/wrab12/wrab12.github.io)
![License](https://img.shields.io/github/license/wrab12/wrab12.github.io)
![Stars](https://img.shields.io/github/stars/wrab12/wrab12.github.io?style=flat)

# Rui Wang — Academic Homepage

Source code for my personal academic website: **<https://wrab12.github.io/>**

I'm an undergraduate student in Computer Science at the University of Minnesota, Twin Cities. My research is in **AI for Science**, with a current focus on generative models (diffusion, optimal transport), geometric deep learning, spatial transcriptomics, and protein/peptide design.

- 📧 Email: [wan03403@umn.edu](mailto:wan03403@umn.edu)
- 🎓 Google Scholar: <https://scholar.google.com/citations?user=DEmcaloAAAAJ&hl=en>
- 💻 GitHub: [@wrab12](https://github.com/wrab12)

## Site structure

The site is static and content-driven: page sections are written as Markdown files and parsed in the browser at load time — no build step required.

```
.
├── contents          # page content (edit these)
│   ├── config.yml        # site title, copyright, header text
│   ├── home.md           # About / Education / Experience
│   ├── news.md           # News timeline
│   ├── publications.md   # Publication list
│   └── awards.md         # Awards & honors
├── static
│   ├── assets/img        # background image & profile photo
│   ├── css
│   └── js
└── index.html
```

## Updating content

1. Edit the relevant file in `contents/`.
2. Adjust title, copyright, and header text in `contents/config.yml`.
3. Replace images in `static/assets/img/` as needed.
4. Commit and push to `main` — GitHub Pages redeploys automatically in 1–2 minutes.

```bash
git commit -am "update content"
git push
```

## Credits & License

Built on the [academic homepage template](https://github.com/senli1073/senli1073.github.io) by **Sen Li**, which is in turn based on [Start Bootstrap — New Age](https://github.com/StartBootstrap/startbootstrap-new-age). Released under the MIT License (see [LICENSE](LICENSE)).

Website content © Rui Wang, 2023–2026.
