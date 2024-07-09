# laravel


## Setup Instructions

1. **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd project
    ```

2. **Ensure the `data` directory is writable by the web server:**

    ```bash
    chmod -R 777 data/
    ```

3. **Open the project in a web server environment:**

    - You can use XAMPP, WAMP, MAMP, or any local server environment that supports PHP.
    - Place the `project` directory in the server's root directory (e.g., `htdocs` for XAMPP).

4. **Access the project in your web browser:**

    ```
    http://localhost/project/
    ```

## Usage

1. **Submit Product Data:**
    - Fill out the form with the product name, quantity in stock, and price per item.
    - Click the "Submit" button.

2. **View Submitted Data:**
    - The submitted data will be displayed in a table below the form.
    - The table shows product name, quantity in stock, price per item, datetime submitted, total value number, and actions.

3. **Edit Data:**
    - Click the "Edit" button next to a row to enable editing of the product data.
    - Make changes and click "Save" to update the data.

4. **Sum Total:**
    - The sum total of all the total value numbers is displayed in the last row of the table.

## Files

- **index.php:** Main file that includes the form and table structure.
- **save.php:** PHP script to save form data to the JSON file.
- **update.php:** PHP script to update the JSON file with edited data.
- **css/styles.css:** Custom CSS styles.
- **js/scripts.js:** JavaScript for handling form submission, data display, and editing functionalities.
- **data/data.json:** JSON file to store the submitted data.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Neha Prasad


