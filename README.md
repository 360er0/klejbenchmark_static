# KLEJ Benchmark Static Site

This is a static HTML version of the [KLEJ Benchmark website](https://klejbenchmark.com/) designed for hosting on GitHub Pages.

## About KLEJ Benchmark

The KLEJ benchmark (_Kompleksowa Lista Ewaluacji Językowych_) is a set of nine evaluation tasks for the Polish language understanding.

Key benchmark features:
- Contains a diverse set of tasks from different domains and with different objectives
- Most tasks are created from existing datasets but also includes new sentiment analysis dataset from e-commerce domain
- Includes tasks which have relatively small datasets and require extensive external knowledge to solve them
- Promotes the usage of transfer learning instead of training separate models from scratch

## Project Structure

```
├── index.html              # Main landing page
├── tasks/                  # Tasks page
│   └── index.html
├── leaderboard/           # Leaderboard page
│   └── index.html
├── submit/                # Submit page
│   └── index.html
├── static/                # CSS and assets
│   ├── style.css
│   ├── icon.png
│   └── allegro_logo.svg
├── _config.yml           # Jekyll configuration for GitHub Pages
└── README.md             # This file
```

## Deployment to GitHub Pages

1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose "main" branch
5. The site will be available at `https://yourusername.github.io/repository-name/`

## Original Content

This static site is based on the original KLEJ Benchmark website. For the most up-to-date information and to submit results, please visit:
- **Original site**: https://klejbenchmark.com/
- **Paper**: https://arxiv.org/abs/2005.00630
- **Code**: https://github.com/allegro/klejbenchmark-baselines

## Contact

KLEJ benchmark was created at Allegro. Contact: klejbenchmark@allegro.pl