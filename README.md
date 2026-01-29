# Pengfei Cui - Academic Homepage

Personal academic website of **Pengfei Cui**, Faculty at the College of Metropolitan Transportation, Beijing University of Technology.

🌐 **Live Site**: [https://pengfeicui99.github.io](https://pengfeicui99.github.io)

## About

I am a Faculty member at the College of Metropolitan Transportation, Beijing University of Technology (BJUT). My research focuses on urban traffic safety, spatio-temporal modeling, interpretable machine learning, and multi-source data integration (e.g., street-view semantic visual features).

### Research Interests

- **Urban Traffic Safety** - Crash frequency/severity modeling and risk analysis
- **Spatio-temporal Modeling** - Dynamic learning and spatio-temporal forecasting
- **Spatial Statistics & Heterogeneity** - Spatial inequity analysis and heterogeneous effects
- **Interpretable Machine Learning** - Explainable spatial ML for transportation safety
- **Street-view Imagery** - Semantic visual feature extraction and multi-source fusion

### Education

- **Ph.D. in System Science** (Sept. 2021 – Jun. 2025), Beijing Jiaotong University
- **M.Eng. in Transportation Planning and Management** (Sept. 2019 – Jun. 2021), Beijing Jiaotong University
- **B.Mgmt. in Traffic Management** (Sept. 2015 – Jun. 2019), Dalian Maritime University

### Research Highlights

- Published research in leading transportation journals (e.g., *Transportation Research Part C*, *Accident Analysis & Prevention*, *Transport Policy*, *Transportmetrica A: Transport Science*).
- Research keywords: spatial heterogeneity; injury severity modeling; equity analysis; multi-source urban data fusion.

## Website Structure

This website is built using [Jekyll](https://jekyllrb.com/) and the [Academic Pages](https://academicpages.github.io/) theme. It includes:

- **Home/About** - Personal introduction and research overview
- **News** - Latest updates and achievements
- **Research** - Detailed research projects and methodologies
- **Publications** - Complete list of journal articles, conference papers, and preprints
- **CV** - Academic curriculum vitae
- **Posts** - Blog posts and personal updates

## Local Development

### Prerequisites

- [Ruby](https://www.ruby-lang.org/) (with bundler)
- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/) (optional, recommended)

### Using Docker (Recommended)

The easiest way to run the site locally is using Docker:

```bash
docker compose up
```

The site will be available at `http://localhost:4000`. Changes to Markdown and HTML files will automatically rebuild.

To restart the container:

```bash
docker compose restart
```

### Manual Setup

1. **Install dependencies**:
   ```bash
   bundle install
   npm install
   ```

2. **Run Jekyll server**:
   ```bash
   bundle exec jekyll serve -l -H localhost
   ```

   Or with auto-reload:
   ```bash
   bundle exec jekyll serve -l -H localhost --watch
   ```

3. **Access the site**: Open `http://localhost:4000` in your browser

### Building for Production

```bash
bundle exec jekyll build
```

The generated site will be in the `_site/` directory.

## Contact

- **Phone**: +86-13722119206
- **Email**: [pengfeicui@bjut.edu.cn](mailto:pengfeicui@bjut.edu.cn)
- **Google Scholar**: [Pengfei Cui](https://scholar.google.com/citations?user=4EGD9vsAAAAJ&hl=en&oi=ao)
- **GitHub**: [@PengfeiCui99](https://github.com/PengfeiCui99)

## License

This website is built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which is based on the [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/).

The content of this website (text, images, publications) is © Pengfei Cui. All rights reserved.

---

**Last Updated**: 2026
