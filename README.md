
# Caesar Cipher Decryption Tool

This is a Flask-based web application that allows users to decrypt messages encoded using the Caesar Cipher. The tool prompts users to guess the shift value (key) used to encrypt the message.

## Features

- Interactive Caesar Cipher decryption where users guess the shift value.
- Handles non-alphabetic characters, leaving them unchanged during decryption.
- The input ciphertext remains on the screen after each attempt for easier interaction.
- Includes a copyright notice at the bottom of the page.

## Usage

### Prerequisites

Make sure you have Python installed on your system. You'll also need `Flask` and `gunicorn`, which you can install via pip:

\`\`\`bash
pip install Flask gunicorn
\`\`\`

### Running the Application

1. Clone this repository:

   \`\`\`bash
   git clone [https://github.com/yourusername/caesar-cipher-decryption-tool.git](https://github.com/theparadox7/Caesar_cipher_Tool.git)
   cd caesar-cipher-decryption-tool
   \`\`\`

2. Install the required dependencies:

   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

3. Run the Flask application:

   \`\`\`bash
   python app.py
   \`\`\`

4. Open your web browser and navigate to \`http://127.0.0.1:5000/\` to start using the tool.

### Deployment

You can deploy this application on platforms like Heroku, AWS, or a VPS. Instructions for deploying to these platforms are provided in the project's documentation.

## Future Enhancements

- **Option to toggle between light and dark modes:** This feature will enhance user experience by allowing users to switch between light and dark modes depending on their preference.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   \`\`\`bash
   git checkout -b feature/your-feature-name
   \`\`\`
3. Make your changes.
4. Commit your changes:
   \`\`\`bash
   git commit -m "Add your message here"
   \`\`\`
5. Push the branch to your fork:
   \`\`\`bash
   git push origin feature/your-feature-name
   \`\`\`
6. Open a pull request on the original repository.

Please make sure to follow the project's coding style and write clear, concise commit messages. If you're adding a new feature, consider including tests to ensure it works as expected.
