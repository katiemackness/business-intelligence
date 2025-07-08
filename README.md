# Business Intelligence
A repository of practice materials for business intelligence tools.

## Objective
The main goal of this project is to practice Python tools for business intelligence.

## Key Features

- Containerized environment using Docker Compose for reproducibility
- Interactive analysis with JupyterLab preconfigured for Python
- Integrated MongoDB service for structured data workflows
- Modular folder structure for notebooks and configuration
- Preloaded Python libraries for data analysis and visualization (`pandas`, `seaborn`, `matplotlib`)
- Notebook-based queries against MongoDB using `pymongo`


## Installation and Setup

This repository provides a reproducible data science environment using Docker Compose and JupyterLab, suitable for business intelligence workflows involving MongoDB and Python.

### Prerequisites

Before beginning, ensure that one of the following is available:

- GitHub Codespaces access (recommended), or
- A local system with the following installed:
  - [Docker](https://docs.docker.com/get-docker/)
  - [Git](https://git-scm.com/)
  - [Python 3.8+](https://www.python.org/downloads/) (only if running locally without containers)


### Clone the Repository

To begin, clone the repository and navigate into the project directory:

```bash
git clone https://github.com/your-username/business-intelligence.git
cd business-intelligence
```
## Usage Instructions
Once the environment is set up, you may begin exploring and analyzing data within the provided notebook.

### Launch JupyterLab in Codespaces

1. Open the repository in GitHub Codespaces
2. Wait for the container to initialize
3. Navigate to the `notebooks/` directory
4. Open `business-intelligence.ipynb`

All required libraries are pre-installed and ready for use. MongoDB will be accessible via the service name `mongodb` on port `27017`.

### Local Usage with Docker

1. Start the environment locally:

```
bash
docker compose up
```

2. After the containers initialize, access the JupyterLab interface by opening a browser and visiting: `http://localhost:8888`

3. If prompted, use the authentication token displayed in the terminal during container startup.

4. Navigate to the `notebooks/` directory and open `business-intelligence.ipynb` to begin working with data.

5. MongoDB is preconfigured and accessible at: `mongodb://mongodb:27017/`

6. This address should be used for all MongoDB connections within the notebook environment.


## File Struture
```
business-intelligence/
├── .devcontainer/
│   ├── devcontainer.json
│   └── docker-compose.yml
├── notebooks/
│   └── business-intelligence.ipynb
├── README.md
└── .gitignore
```

## Contributing
...

## License
...

## Contact
...
