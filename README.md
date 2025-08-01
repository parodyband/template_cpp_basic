# C++ Template

A simple C++ "Hello, World!" template using CMake.

## First-Time Setup on Windows

This template is configured to use the g++ compiler. For the VS Code linter (`clangd`) to work correctly on Windows, you must tell it where to find your g++ compiler.

1.  Open the `.vscode/settings.json` file.
2.  Find the `"[windows]"` section.
3.  Replace the placeholder path `C:/PATH/TO/YOUR/gcc/bin/g++.exe` with the absolute path to your `g++.exe`.
4.  Restart VS Code.

## Building and Running

1.  **Create a build directory:**
    ```bash
    mkdir build
    cd build
    ```

2.  **Configure the project:**
    ```bash
    cmake ..
    ```

3.  **Build the project:**
    ```bash
    cmake --build .
    ```

4.  **Run the executable:**
    ```bash
    ./my_project
    ```
