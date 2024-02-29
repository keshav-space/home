# Home Configurations

## Enable Client Side Git Hooks
1. Set a symbolic link to `~/githooks` from `./githooks`
    ```bash
    ln -s ~/<Full Path>/home/githooks ~/githooks
    ```

2. Config Git to globally use ~/githooks
    ```bash
    git config --global core.hooksPath ~/githooks
    ```
> [!Note]
> To bypass hooks use --no-verify flag while committing and pushing.


