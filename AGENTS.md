# Agents Documentation

Welcome to the `Data-Dunkers/activities` repository. This document outlines the purpose of the repository, the standards for creating and maintaining content, and the workflow for AI agents assisting with this project.

## Repository Purpose

The goal of this repository is to provide a comprehensive set of student-facing Jupyter Notebook activities for the **Data Dunkers** program. These activities teach data science, Python programming, and data visualization using real-world hockey data (from the NHL, AHL, and other sources).

## Content Standards

To maintain consistency and accessibility for students and educators, all notebooks should adhere to the following standards:

### 1. Notebook Structure
Every activity notebook should follow a standard flow:
- **Banner & Navigation**: A top-level markdown cell containing the Data Dunkers banner and "Open in Callysto/Colab" buttons.
- **Objectives**: A clear list of what students will learn in the notebook.
- **Section Headings**: Use the following primary headings to clarify the data pipeline:
    - **Input**: Importing libraries and loading data (usually from a URL).
    - **Process**: Data manipulation, filtering, sorting, or calculations.
    - **Output**: Visualizing the results (graphs, tables, or summary statistics).

### 2. Technology Stack
- **Language**: Python 3.
- **Data Analysis**: [Pandas](https://pandas.pydata.org/) for all data manipulation.
- **Visualization**: [Plotly Express](https://plotly.com/python/plotly-express/) for interactive and accessible charts.
- **Environment**: A `.venv` virtual environment managed via `requirements.txt`.

### 3. Data Sourcing
- Prefer raw URLs from the `Data-Dunkers/data` or `pbeens/Data-Dunkers` repositories.
- Use `pd.read_csv()` or `pd.read_excel()` as appropriate.

### 4. Visual Aesthetics
- Plots should include descriptive titles and labeled axes.
- Maintain a clean, professional appearance with minimal boilerplate code in student-facing cells.

## Developer & Agent Workflow

### Environment Setup
1. Create a virtual environment: `python -m venv .venv`
2. Install dependencies: `./.venv/Scripts/pip install -r requirements.txt` (on Windows)
3. Use the `.venv` as the Jupyter kernel.

### Standards for AI Agents
- **Naming**: Use descriptive, lowercase, kebab-case filenames (e.g., `winnipeg-jets.ipynb`).
- **Traceability**: Ensure all changes are documented in the repository's version control.
- **Verification**: After creating or modifying a notebook, verify the cell flow (Input -> Process -> Output) matches the repository's pedagogical style.

---
*Maintained by the Data Dunkers Team.*
