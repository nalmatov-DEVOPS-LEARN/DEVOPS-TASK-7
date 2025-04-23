# TASK 6

## FOR RUNNING

### Installing language (Python or NodeJS)

- NodeJS & NPM:

  - ```bash
    curl -sL https://deb.nodesource.com/setup_16.x -o nodesource_setup.sh
    ```

  - ```bash
    sudo bash nodesource_setup.sh
    ```

  - ```bash
    sudo apt install nodejs
    ```

  ***

- Python

  - ```bash
    sudo apt update
    ```

  - ```bash
    sudo apt install python
    ```

---

### Running web application

> [!IMPORTANT]
> Select language and be in its root directory! `cd ./python` or `cd ./nodejs`

> Do step-by-step!

1. Make executable files for docker running!

```bash
chmod +x ci/*
```

2. Start `hello-world` container!

```bash
ci/build_run.sh
```
