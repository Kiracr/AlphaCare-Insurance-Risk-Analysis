# AlphaCare Insurance Risk Analysis

## Project Overview

This project aims to perform a comprehensive risk and profitability analysis for AlphaCare, an insurance provider. By leveraging exploratory data analysis (EDA) and statistical modeling, we will identify key risk factors, assess portfolio performance, and provide data-driven insights to guide underwriting and pricing strategies.

The initial dataset covers an 18-month period and includes policyholder demographics, vehicle information, and claims data.

---

## Folder Structure

The project is organized to maintain a clear separation of concerns, ensuring reproducibility and scalability.

-   `/.github/workflows/`: Contains GitHub Actions for CI/CD (e.g., automated testing).
-   `/data/`: Stores raw and processed data. This folder is excluded from version control by `.gitignore`.
-   `/notebooks/`: Houses Jupyter notebooks for exploratory data analysis (EDA) and experimentation.
-   `/src/`: Contains all source code, organized into reusable Python modules (e.g., data processing, model training).
-   `/scripts/`: For standalone scripts (e.g., data ingestion, final pipeline execution).
-   `/tests/`: Includes all unit and integration tests to ensure code quality and reliability.
-   `requirements.txt`: Lists all project dependencies.
-   `README.md`: Project documentation.

---

## Getting Started

### Prerequisites

-   Python 3.9+
-   Git

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/AlphaCare-Insurance-Risk-Analysis.git
    cd AlphaCare-Insurance-Risk-Analysis
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage

All exploratory analysis is conducted within the `notebooks/` directory. To start, launch JupyterLab:

```bash
jupyter lab