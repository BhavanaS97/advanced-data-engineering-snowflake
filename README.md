## Maintainer

- [BhavanaS](https://github.com/BhavanaS97)  
- Email: samboju.bhavana19@gmail.com 
- LinkedIn: [(https://www.linkedin.com/in/bhavana-s-3171151b6/)]

## 💼 Project: Declarative Change Management with Snowflake CLI & GitHub Actions

**Description:**
Implemented a declarative deployment workflow to manage Snowflake object changes using `CREATE OR ALTER` statements, Snowflake CLI, and GitHub Actions. Designed automation to promote code from staging to production based on Git branch strategy.

**What I Did:**
- 🔄 Used `CREATE OR ALTER` for safe, repeatable deployment of Snowflake objects.
- ⚙️ Created `main.yml` GitHub Actions workflow to automate deployment on PR merges.
- 🔐 Used **GitHub Secrets** to securely store Snowflake credentials (`account`, `username`, `private key`, `role`, etc.).
- 📦 Integrated Snowflake CLI for executing deployment commands programmatically.
- 🌱 Followed a Git branching model to differentiate staging and production environments.

> ✅ This setup supports **Declarative Change Management (DCM)** and aligns with modern CI/CD practices for secure, scalable Snowflake deployments.

---

## Advanced Data Engineering with Snowflake

#### How to use this repo throughout the course:

To successfully follow along with the instructor during the course, you'll need to make use of the code in this repo. To follow along, you can either:

* Keep the URL to this repo handy, so that you can easily find and use any code referenced by the instructor during the course

* Clone the repo to your local computing environment (required)

> **Note:** There are a couple of exercises that make use of Snowflake's command line interface, Snowflake CLI. To successfully follow along during those exercises, you'll need to have the repo cloned to your local computing environment, so that the Snowflake CLI can make use of files and code within this repo.

#### How to clone the repo to your local computing environment:

1. Fork the repo to create a copy associated with your GitHub Account: https://github.com/Snowflake-Labs/advanced-data-engineering-snowflake/fork

2. Clone your fork:

```bash
git clone https://github.com/<your-GitHub-user-name>/modern-data-engineering-snowflake.git
```

Where `<your-GitHub-user-name>` is replaced by your GitHub user name. This workflow is covered in the course.

You can then open the repo in your preferred code editor. Throughout the course, the instructor will use Visual Studio Code as the code editor.

#### How to navigate this repo

All of the code that you need to successfully complete the course is within this repo. Each folder in this repo corresponds to a module in the online course.

* **module-1** – Corresponds to "Module 1: DevOps with Snowflake" in the course.

* **module-2** – Corresponds to "Module 2: Observability with Snowflake" in the course.

The course instructor will also be sure to reference the exact folder and name of the file to use throughout the course, so that you can follow along.

#### Reporting issues or errata

If you encounter technical issues with this code as you complete the course (i.e. typos, missing code, broken links, etc.), please report those issues in the course through Coursera. Ensure the issue contains sufficient detail so that it can be properly addressed.
