# MSS Pipelines Guidance

MSS stands for Maintainable, Scalable, and Sustainable. This repository contains the guidance site for building MSS data pipelines using the Diataxis documentation model.

## Site structure

- `index.qmd`: Landing page
- `tutorials/`: Step-by-step learning journeys
- `how-to/`: Task-based guides
- `reference/`: Technical reference
- `explanation/`: Background and rationale

## Live site

https://datasciencecampus.github.io/mss-pipelines-guidance/

## Local preview

Prerequisites:
- Quarto installed: https://quarto.org

Commands:

```sh
quarto render
```

This renders the site to the `_site/` directory.

## Publishing

The GitHub Actions workflow in `.github/workflows/quarto-publish.yml` builds and deploys the site to GitHub Pages from the `main` branch.

## Project policies

- Code of conduct: [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- Security policy: [SECURITY.md](SECURITY.md)

## License

See [LICENSE](LICENSE).

## Contributing

- Keep content aligned with Maintainable, Scalable, and Sustainable (MSS) principles.
- Use the existing Diataxis sections for new content.
- Full contribution guidance: [CONTRIBUTING.md](CONTRIBUTING.md)
