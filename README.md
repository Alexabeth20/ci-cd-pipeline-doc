# CI/CD Pipeline Documentation – AWS Lambda with GitHub Actions

This repository contains a technical documentation project that walks through setting up a Continuous Integration and Continuous Deployment (CI/CD) pipeline using **GitHub Actions** to deploy a **Python-based AWS Lambda function**. It includes procedural documentation formatted for knowledge bases like MadCap Flare and serves as a sample portfolio project for DevOps documentation and automation.

---

## Project Overview

This documentation outlines how to:

- Automate Lambda function deployment using GitHub Actions
- Install Python dependencies with `pip`
- Run tests using `pytest`
- Package the function using `zip`
- Deploy the zipped code to AWS Lambda using the AWS CLI
- Structure documentation clearly using reusable knowledge base templates

---

## Tools & Technologies

- **GitHub Actions** – CI/CD automation platform
- **AWS Lambda + API Gateway** – Serverless function host
- **Python 3.11** – Lambda runtime
- **pytest** – Python test framework
- **MadCap Flare** – Used for structured technical documentation
- **Markdown / HTML** – For portability and readability

---

## Folder Structure

```
├── .github/
│   └── workflows/
│       └── deploy.yml                 # CI/CD pipeline config
├── madcap-html-export/                # Knowledge article HTML output (trial version)
│   ├── index.html
│   └── assets/
├── markdown-version/                  # Clean Markdown version of the article
│   └── ci-cd-article.md
├── screenshots/                       # Supporting visuals (optional)
├── README.md
└── requirements.txt                   # Python dependencies
```
---

## Limitations

Due to limitations of the **MadCap Flare trial version**, the exported HTML may include scrambled or distorted characters.  

The clean, readable version of the documentation is provided in:

- `markdown-version/ci-cd-article.md` (in this repo)
- [My Portfolio](alexabeth20.github.io)

---

## Portfolio Use Case

This repository serves as a real-world example of:

- Writing DevOps documentation
- Structuring knowledge base articles for cloud workflows
- Demonstrating automation skills for technical writer, DevOps, and QA roles

---

## Related Links

- [CI/CD Knowledge Article – Clean Markdown Version](#github-link-to-md)
- [Portfolio Blog Post on This Project](#portfolio-link)

---

## Author

**Alexandra Mayer**
[Portfolio Site](https://alexabeth20.github.io/) | [LinkedIn](https://www.linkedin.com/in/alexandra-mayer-626352354)

---

## License

This repo is intended for demonstration and educational purposes only. All product names, logos, and brands are property of their respective owners.
