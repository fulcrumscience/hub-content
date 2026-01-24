# AI4Science Hub Content

This repository contains the curated content for AI4Science Hub — a collection of resources for applying AI and machine learning to scientific research.

The website itself is built from the [hub-site](https://github.com/fulcrumscience/hub-site) repository. This repo contains only the markdown content and metadata files.

## Structure

```
├── biology/          # Protein design, drug discovery, single-cell analysis
├── chemistry/        # Cheminformatics, molecular generation, retrosynthesis
├── earth-climate/    # Climate modeling, environmental research
├── materials/        # Neural network potentials, property prediction
├── physics/          # Physics-informed ML, simulation
├── foundations/      # Programming, ML basics, courses
├── methods/          # GNNs, PINNs, neural ODEs, scientific LLMs
├── tools/            # Software ecosystems, awesome lists
└── _meta.ts          # Navigation metadata
```

Each topic directory contains:
- `index.md` — Topic overview
- `resources.md` — Curated links (courses, tutorials, blogs)
- `datasets.md` — Relevant datasets and benchmarks
- `tools.md` — Software and libraries
- `_meta.ts` — Section navigation config

## Contributing

### Adding a Resource

1. Fork this repository
2. Find the appropriate topic directory and file
3. Add your resource following the existing format
4. Submit a pull request

### Guidelines

- **Quality over quantity** — Only submit resources that are genuinely valuable
- **Prefer open access** — Free, openly available materials are preferred
- **Check your links** — Ensure all URLs work before submitting
- **Include context** — Add a brief description explaining what makes the resource useful
- **Active maintenance** — Resources should be actively maintained (no abandoned projects)

### What Makes a Good Contribution

- Courses from reputable universities or research groups
- Tutorials with working code and clear explanations
- Tools that are well-documented and widely used
- Datasets with clear licensing and documentation
- Blog posts with unique insights or practical guidance

### Pull Request Process

1. Create a descriptive PR title (e.g., "Add AlphaFold tutorial to biology/tutorials")
2. Explain why this resource is valuable in the PR description
3. Ensure your addition follows the existing formatting conventions
4. One resource per PR makes review easier, but batched additions are fine if related

### Reporting Issues

- Broken links
- Outdated information
- Suggestions for new topics or restructuring

Open an issue describing the problem or suggestion.

## Acknowledgments

Inspired by [awesome-learning-digital-chemistry](https://github.com/mlederbauer/awesome-learning-digital-chemistry) by [Magdalena Lederbauer](https://mlederbauer.com/).

## License

MIT License
