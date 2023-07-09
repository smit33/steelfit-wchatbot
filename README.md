# Steelfit-wchatbot

This project is a portfolio website developed using the Django framework. The website serves as an online presence for a company, showcasing their products and services. It includes a responsive front-end design implemented using HTML, CSS, and JavaScript. Additionally, a chatbot feature is integrated into the website to collect user inquiries for products. The chatbot logic is written in JavaScript, and the collected data is sent to the business owner via email.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Mdwij/steelfit-wchatbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repository
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up the database:

   ```bash
   python manage.py migrate
   ```

5. Collect the static files:

   ```bash
   python manage.py collectstatic
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Access the website through your browser at `http://localhost:8000`.

## Configuration

1. Update the Django settings:

   Open the `settings.py` file located in the project's root directory. Modify the following settings according to your needs:

   - `SECRET_KEY`: Replace with a unique secret key for your project.
   - `DEBUG`: Set to `True` during development, and `False` in production.
   - `EMAIL_BACKEND`: Choose an appropriate email backend for sending emails.
   - `EMAIL_HOST`: Specify the hostname of your email server.
   - `EMAIL_PORT`: Set the port number for the email server.
   - `EMAIL_HOST_USER` and `EMAIL_HOST_PASSWORD`: Provide the login credentials for your email account.
   - `DEFAULT_FROM_EMAIL`: Set the email address from which emails will be sent.

2. Customize the website content:

   - Update the HTML templates located in the `templates` directory to match your company's branding and information.
   - Modify the CSS styles in the `static/css` directory to customize the appearance of the website.
   - Update the JavaScript logic for the chatbot located in the `static/js` directory to handle user inquiries appropriately.

## Usage

1. Launch the website:

   Start the development server as described in the installation steps, then access the website through your browser.

2. Explore the portfolio:

   Navigate through the different sections of the website to explore the products and services offered by the company.

3. Interact with the chatbot:

   - The chatbot is accessible on every page of the website.
   - Users can input their inquiries or requests for specific products.
   - The chatbot will collect the user's input and send it to the business owner via email.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add your feature or bug fix"
   ```

4. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature
   ```

5. Open a pull request to the original repository, describing your changes in detail.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgments

- This project was developed using the Django framework (version X.X.X).
- The front-end design was implemented using HTML, CSS, and JavaScript.
- The chatbot logic was written in JavaScript.
- Email functionality was achieved using Python scripts and an appropriate email backend.