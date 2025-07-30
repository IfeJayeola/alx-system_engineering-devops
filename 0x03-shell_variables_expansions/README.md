# 0x03. Shell, init files, variables and expansions

> This project is part of the ALX Software Engineering program and focuses on Shell scripting with an emphasis on variables, expansions, and environment customization.

---
## 📁 Project Structure

Each script file performs a specific task. All scripts are written for **Bash (GNU Bash v4.3+)** and are executable.

| File | Description |
|------|-------------|
| `0-alias` | Creates an alias `ls` with value `rm *`. |
| `1-hello_you` | Prints `hello` followed by the current user. |
| `2-path` | Adds `/action` directory to the `PATH` environment variable. |
| `3-paths` | Counts the number of directories in the current `PATH`. |
| `4-global_variables` | Lists all environment (global) variables. |
| `5-local_variables` | Lists all shell local and environment variables and functions. |
| `6-create_local_variable` | Creates a local variable `BEST=School`. |
| `7-create_global_variable` | Creates a global variable `BEST=School`. |
| `8-true_knowledge` | Adds 128 to the value of the `TRUEKNOWLEDGE` environment variable. |
| `9-divide_and_rule` | Divides `POWER` by `DIVIDE`, both environment variables. |
| `10-love_exponent_breath` | Raises `BREATH` to the power of `LOVE`, both environment variables. |
| `11-binary_to_decimal` | Converts binary number in `BINARY` variable to decimal. |
| `12-combinations` | Prints all two-letter combinations except `oo`. Max 64 characters. |
| `13-print_float` | Prints a number stored in `NUM` with 2 decimal places. |

---

## 🚀 Usage

To execute any script:

```bash
chmod +x <script_name>
./<script_name>
