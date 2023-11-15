# Django Project Setup Script

## Introduction

This script automates the process of setting up a Django project and its associated apps. It creates a project directory, installs Django and sets up the initial project structure.

## Prerequisites

Before running the script, ensure the following prerequisites are met:

- **Python**: Make sure Python 3 is installed on your system.

- **pipenv**: The script uses `pipenv` for managing the virtual environment. If not already installed, the script attempts to install it during execution.

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/lordofthemind/djangoSetupScript.git
   cd your-repo
   ```

2. **Run the Script**:

   ```bash
   ./djangoSetup <project_name>
   ```

   Replace `<project_name>` with the desired name for your Django project.

3. **Follow the Prompts**:

   The script will prompt you to enter a list of app names, separated by spaces. It will then create these apps and set up basic views, URLs, and settings.

4. **Run the Server**:

   The script will activate the virtual environment and run the Django development server.

## Notes

- If `pipenv` is not installed, the script will attempt to install it using `sudo apt install pipenv`. If this fails, please install `pipenv` manually.

- Ensure that the script has executable permissions:

  ```bash
  chmod +x setup_django_project.sh
  ```

- For any issues or additional information, refer to the [Issues](https://github.com/lordofthemind/djangoSetupScript.git) section of the repository.

## Contributing

Feel free to contribute by submitting bug reports, feature requests, or pull requests. Contributions are welcome!

---

Adjust the links and placeholders according to your actual repository information. If you have a LICENSE file, consider including a section about it in the README as well.