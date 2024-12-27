# Python Module Template (Cookiecutter)

This is a cookiecutter template for python module projects.

## ✨ Features

- Cookiecutter
- Python module/package
- Project Structure
- Boilerplate/Template
- Best Practices
- Configuration
- Test
- Build
- Documentation
- Scripts
- Examples
- CI/CD

---

## 🐤 Getting started

### 1. 🚧 Prerequisites

- Install **Python (>= v3.9)** and **pip (>= 23)**:
    - **[RECOMMENDED] [Miniconda (v3)](https://docs.anaconda.com/miniconda)**
    - *[arm64/aarch64] [Miniforge (v3)](https://github.com/conda-forge/miniforge)*
    - *[Python virutal environment] [venv](https://docs.python.org/3/library/venv.html)*

For **DEVELOPMENT** environment:

- Install [**git**](https://git-scm.com/downloads)
- Setup an [**SSH key**](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) ([video tutorial](https://www.youtube.com/watch?v=snCP3c7wXw0))

### 2. 📥 Download or clone the repository

**2.1.** Prepare projects directory (if not exists):

```sh
# Create projects directory:
mkdir -pv ~/workspaces/projects

# Enter into projects directory:
cd ~/workspaces/projects
```

**2.2.** Follow one of the below options **[A]**, **[B]** or **[C]**:

**OPTION A.** Clone the repository:

```sh
git clone https://github.com/bybatkhuu/module.python-template.git && \
    cd module.python-template && \
    git checkout cookiecutter
```

**OPTION B.** Clone the repository (for **DEVELOPMENT**: git + ssh key):

```sh
git clone git@github.com:bybatkhuu/module.python-template.git && \
    cd module.python-template && \
    git checkout cookiecutter
```

**OPTION C.** Download source code from cookiecutter branch.

### 3. 📦 Install cookiecutter

```bash
# Install cookiecutter:
pip install -U cookiecutter
# Or:
pip install -r ./requirements.txt
```

### 4. 🏗️ Generate project with cookiecutter

```bash
# Generate project:
cookiecutter -f .
# Or:
./scripts/build.sh
```

### 5. 🏁 Start the project

```bash
cd [PROJECT_NAME]
# For example:
cd module.python-template
```

👍

---

## 📑 References

- Cookiecutter (GitHub) - <https://github.com/cookiecutter/cookiecutter>
- Cookiecutter (Docs) - <https://cookiecutter.readthedocs.io/en/stable>
