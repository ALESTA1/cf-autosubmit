# Codeforces Automation Script

This script automates the process of code submission on Codeforces. It logs in to your Codeforces account, navigates to the specified contest and question, uploads the code file, and submits it. It then retrieves the verdict (result) of the submission.

## Prerequisites

- Python 3.x
- Selenium library
- Chrome WebDriver (ensure it matches your Chrome browser version)

## Installation

1. Clone the repository:

2. Install the required dependencies:

3. Download the appropriate Chrome WebDriver from the official website: [Chrome WebDriver Downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads)

4. Update the `path` variable in the script with the path to your Chrome WebDriver executable.

## Usage

Run the script with the following command-line arguments:


- `<contest_number>`: The contest number on Codeforces.
- `<Quesn>`: The question number.
- `<file_name>`: The path to the code file you want to submit.

For example:
py script.py 1846 B prac2.cpp
## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or questions, please contact [Your Name] at [your-email@example.com].
