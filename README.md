# ASU CIC Demo Open Source Project

![Build](https://github.com/apxxrv/demo-opensource/actions/workflows/ci.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

> A model open-source repository demonstrating best practices for Arizona State University's Cloud Innovation Center (CIC) in collaboration with AWS.

## 📘 Overview

This project serves as a reference template for open-source projects within ASU CIC. It includes:

- ASU-standardized repository layout
- Contributor guidelines
- Automated CI/CD setup with GitHub Actions
- Community engagement tools and templates

## 📁 Project Structure

```
├── docs/                  # Design guides and architecture
├── src/                   # Application code
├── tests/                 # Unit and integration tests
├── public/                # Static assets
├── .github/               # Issue, PR templates and workflows
├── .env.example           # Sample environment config
├── README.md              # Project overview
```

## ⚙️ Prerequisites

- Node.js ≥ 14.x or Python ≥ 3.10
- Git + GitHub
- Docker (optional for container-based development)

## 🚀 Getting Started

```bash
git clone https://github.com/apxxrv/demo-opensource.git
cd demo-opensource
npm install            # or pip install -r requirements.txt
cp .env.example .env
npm start              # or python -m src.main
```

## 📂 Configuration

Sample `.env`:

```env
PORT=3000
DATABASE_URL=postgres://user:pass@localhost:5432/demo
API_KEY=your_api_key_here
```

## 🧪 Testing

Run tests:
```bash
npm test               # or pytest
```

Lint check:
```bash
npm run lint           # or flake8 / black
```

## ⚙️ CI/CD

This project uses GitHub Actions:

- `ci.yml`: installs dependencies, runs tests
- `lint.yml`: enforces code style
- PRs are required to pass all checks before merging

## 💡 Contributing

We welcome all contributors! Please review:

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [SECURITY.md](SECURITY.md)

Make sure to create a branch, open a PR, and fill out the template.

## 🐛 Issue Templates

Use the "New Issue" button on GitHub to access:

- Bug Reports
- Feature Requests
- Security Reports
- Ask a Question via Discussions (if enabled)

If issue forms aren't showing, visit `.github/ISSUE_TEMPLATE/` directly.

## 📄 License

Licensed under the [MIT License](LICENSE).

## 🙌 Acknowledgements

- ASU Cloud Innovation Center
- GitHub Open Source Guides
- Community contributors

## 📬 Contact

**Maintainer:** Apoorv Singh  
📧 apoorvsingh.dev@gmail.com

---

*Built with ❤️ for the ASU CIC community*
