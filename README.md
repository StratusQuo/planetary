# Planetary - A P Language Build Manager

Planetary is a command-line tool designed to simplify the management and building of P projects. It provides a streamlined approach to initializing, templating, and checking P projects, making it easier for developers to get started and maintain their codebase.

## Features

* **Project Initialization:** Quickly set up a new P project with the necessary directory structure and configuration files.
* **Template Generation:** Create a template for an existing P project, allowing for consistent project organization.
* **Error Checking:** Perform basic error checking on P projects to identify potential issues early on.
* **User-Friendly Interface:** Simple and intuitive command-line interface for ease of use.

## Installation

1. **Prerequisites:** Ensure you have the following installed:
   * OCaml
   * Dune
   * Spectrum (for colored output)

2. **Build and Install:**
   
   ```bash
   dune build @install
   ```

## Usage

```
Planetary - P Language Project Manager

Usage:
  planetary init <project_name> [-s <folder>] - Initialize a new P project
  planetary template <project_name> - Generate a template for an existing project
  planetary help - Display this help message

Options:
  -s <folder> - Skip creating the specified folder (can be used multiple times)
```

**Examples:**

* **Initialize a new project named "my_p_project":**
  ```bash
  planetary init my_p_project
  ```

* **Generate a template for an existing project named "existing_project":**
  ```bash
  planetary template existing_project
  ```

* **Initialize a project while skipping the PSPEC folder:**
  ```bash
  planetary init my_p_project -s PSPEC
  ```

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.

## License

This project is licensed under the [LICENSE] license.
