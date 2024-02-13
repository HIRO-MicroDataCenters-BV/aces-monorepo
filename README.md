# aces-monorepo
This is the repository for [ACES project](https://cordis.europa.eu/project/id/101093126) microservices. The repository is structured as a monorepo: each directory should contain a separate Python-based microservice. The microservices should be based on the [Python microservice template](https://github.com/HIRO-MicroDataCenters-BV/template-python) provided by HIRO.
The repository structure should look like this:

<details>
  <summary>Sample structure</summary>

  
```
/my-python-project
|
|-- /microservice1
|   |-- /app
|   |   |-- __init__.py
|   |   `-- main.py
|   |
|   |-- /tests
|   |   |-- __init__.py
|   |   `-- test_main.py
|   |
|   |-- /charts
|   |   `-- /app
|   |       `-- Chart.yaml
|   |
|   |-- Dockerfile
|   `-- pyproject.toml
|
|-- /microservice2
|   |-- /app
|   |   |-- __init__.py
|   |   `-- main.py
|   |
|   |-- /tests
|   |   |-- __init__.py
|   |   `-- test_main.py
|   |
|   |-- /charts
|   |   `-- /app
|   |       `-- Chart.yaml
|   |
|   |-- Dockerfile
|   `-- pyproject.toml
|
`-- README.md  (the one you're reading right now)

```


</details>
