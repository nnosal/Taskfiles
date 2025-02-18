# Taskfile
Taskfile - test some cookbook.

## How-to

This repo is for create new recipe. For debug it, you can:

```bash
source .env
task --version
# task --download -y && task test-sample
```

For use it simply add this sample `Taskfile.sample.yml` (+edit) as `Taskfile.yml` to your project.
Don't forget to [install it](https://taskfile.dev/installation/) and enable experimental-mode: `export TASK_X_REMOTE_TASKFILES=1`.