# Orangine

![image](https://github.com/seclerp/orangine-theme/assets/20597871/58e547be-9be5-41bc-9420-820485723a89)


My personal minimalistic theme for oh-my-posh. Please feel free to modify and redistribute.

## How to use

1. Install Oh-my-posh ([**Windows**](https://ohmyposh.dev/docs/installation/windows) | [**MacOS**](https://ohmyposh.dev/docs/installation/macos) | [**Linux**](https://ohmyposh.dev/docs/installation/linux))
2. Either use the config directly from upstream:
   ```bash
   oh-my-posh init SHELL_NAME --config https://raw.githubusercontent.com/seclerp/orangine-theme/main/orangine.omp.json
   ```
   Or download and use local copy:
   ```bash
   oh-my-posh init SHELL_NAME --config ~/shell/orangine.omp.json
   ```

## Segments
Left-side
- Working directory (shortened when reaches 15 characters)

Right-side
- Git branch (if applicable)
- Last command status (if non-zero)
- Execution time (if greater than 500ms)
