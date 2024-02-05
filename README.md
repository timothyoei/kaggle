# Kaggle

## Setup
Start and attach to the container (e.g., VSCode Dev Container: open folder in container). Then, activate the virtual environment:
```
micromamba activate venv
```

Then, attach the virtual environment's kernel to the jupyter notebook (e.g., using Python: select interpreter)


## Teardown
Clean up containers
```
docker compose down -v --rmi all
```