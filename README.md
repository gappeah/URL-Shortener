# URL Shortener

This is a simple URL shortener application built using Flask, which allows users to shorten long URLs into shorter ones.

## Features

- Shortens long URLs into unique short URLs.
- Stores shortened URLs in a JSON file.
- Redirects users from short URLs to their original long URLs.

## Setup

1. Install Python if not already installed.
2. Clone the repository to your local machine.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Run the Flask application by executing `python main.py`.
5. Access the application in your web browser at `http://localhost:5000`.

## Usage

1. Access the home page of the application.
2. Enter the long URL that you want to shorten into the input field.
3. Click the "Shorten" button.
4. The application will generate a unique short URL for the entered long URL.
5. Copy and share the generated short URL.

## Files

- `main.py`: Contains the Flask application code.
- `index.html`: HTML template for the home page.
- `urls.json`: JSON file to store shortened URLs.

## Dependencies

- Flask
- Python (>=3.6)

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
