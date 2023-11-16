# Django Project Setup Script

## Introduction

This script automates the process of setting up a Django project and its associated apps. It creates a project directory, installs Django and sets up the initial project structure.

## Prerequisites

Before running the script, ensure the following prerequisites are met:

- **Python**: Make sure Python 3 is installed on your system.

- **pipenv**: The script uses `[pipenv](https://pipenv.pypa.io/en/latest/)` for managing the virtual environment. If not already installed, the script attempts to install it during execution.
- Supported package manager (apt, yum, pacman, homebrew)

## Functionality

### 1. `projectName`

- Validates and sets the project name.

### 2. `checkPython`

- Checks if Python 3 is installed.

### 3. `checkPackageManager`

- Determines the system's package manager (apt, yum, pacman, homebrew).

### 4. `installPackage`

- Checks and installs a package using the appropriate package manager.

### 5. `installPip`

- Checks and installs `python3-pip`.

### 6. `installPipenv`

- Checks and installs `pipenv`.

### 7. `createDjangoProject`

- Creates a Django project, sets up a virtual environment, and installs required packages.

### 8. `createAppView`

- Creates views for a Django app.

### 9. `createAppUrl`

- Creates URL configurations for a Django app.

### 10. `updateProjectUrl`

- Updates project URLs to include the newly created app.

### 11. `updateProjectSetting`

- Updates project settings to include the newly created app.

### 12. `createDjangoApps`

- Creates multiple Django apps based on user input.

### 13. `activateAndRunServer`

- Activates the virtual environment and runs the Django development server.

### 14. `tree`

- Generates a directory tree and saves it to `tree.txt`.


## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/lordofthemind/djangoSetupScript.git
   cd djangoSetupScript
   ```

2. **Add the script to the local bin(optional)**:

   ```bash
   rgcc djangoSetup
   ```

3. **Run the Script**:

   ```bash
   ./djangoSetup <project_name>
   ```

   From same directory (If not executed second step.)

   ```bash
   djangoSetup <project_name>
   ```

   From anywhere in filesystem

   Replace `<project_name>` with the desired name for your Django project.

4. **Follow the Prompts**:

   The script will prompt you to enter a list of app names, separated by spaces. It will then create these apps and set up basic views, URLs, and settings.

5. **Run the Server**:

   The script will activate the virtual environment and run the Django development server.

## Notes

- If `pipenv` is not installed, the script will attempt to install it using `sudo apt install pipenv`. If this fails, please install `pipenv` manually.

- Ensure that the script has executable permissions:

  ```bash
  chmod +x djangoSetup
  ```

- Else script can be added to local binary file by rgcc command

  ```bash
  rgcc djangoSetup
  ```

- For any issues or additional information, refer to the [Issues](https://github.com/lordofthemind/djangoSetupScript.git) section of the repository.

## License

This script is licensed under the [MIT License](LICENSE).

--- 

## Contributing

Feel free to contribute by submitting bug reports, feature requests, or pull requests. Contributions are welcome!