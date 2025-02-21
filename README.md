# Taskfiles

Taskfiles - test some cookbook as remote include.

> This repo is under-heavy modification, not to use in production and at your own risk.

## How-to

### Cook a recipe

This branch "main" is for create new recipe. For debug it, you can:

```bash
source .env
task --version
# task --download -y && task test-sample
```

### Quick-Start

```bash
git clone --depth 1 -b use https://github.com/nnosal/Taskfiles mysuperproject
```

### Manually

Simply add this sample `Taskfile.sample.yml` (+edit) as `Taskfile.yml` to your project. 

**💡 Don't forget to [install Taskfile](https://taskfile.dev/installation/) and enable experimental-mode**: `export TASK_X_REMOTE_TASKFILES=1` or `echo "TASK_X_REMOTE_TASKFILES=1" >> .env`.
