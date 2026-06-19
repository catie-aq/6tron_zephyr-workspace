# Zephyr 6TRON workspace

## Usage

> [!NOTE]
> You can use Dev Containers to develop in a consistent environment. This ensures that all dependencies and tools are correctly set up.

### With DevContainer

- Clone the repository

```bash
mkdir 6tron-workspace
cd 6tron-workspace
git clone https://github.com/catie-aq/6tron_zephyr-workspace 6tron-project
```

- Open the workspace in Visual Studio Code

```bash
code 6tron-project
```

- Open the workspace in the DevContainer: `Ctrl+Shift+P` > `Reopen in Container`
- Choose between the Linux or Windows devcontainer depending on your operating system.
- Initialize the Zephyr workspace

```bash
west init -l 6tron-project
```

- Update workspace

```bash
west update
```

### Without DevContainer

- Initialize the Zephyr workspace

```bash
west init -m https://github.com/catie-aq/6tron_zephyr-workspace 6tron-workspace
```

- Update workspace

```bash
west update
```
