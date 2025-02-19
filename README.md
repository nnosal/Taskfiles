# Taskfile

Taskfile - test some cookbook.

> This repo is under-heavy modification, not to use in production and at your own risk.

## How-to

This repo is for create new recipe. For debug it, you can:

```bash
source .env
task --version
# task --download -y && task test-sample
```

For use it simply add this sample `Taskfile.sample.yml` (+edit) as `Taskfile.yml` to your project.
Don't forget to [install it](https://taskfile.dev/installation/) and enable experimental-mode: `export TASK_X_REMOTE_TASKFILES=1` or `echo "TASK_X_REMOTE_TASKFILES=1" >> .env`.
