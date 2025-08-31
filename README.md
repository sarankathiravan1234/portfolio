# Angular Contact Form Application

This is an Angular application that implements a contact form. Users can fill out their name, email, subject, and message, which will be sent to a specified email address.

## Project Structure

The project is organized as follows:

```
angular-contact-app
├── src
│   ├── app
│   │   ├── app.component.ts        # Main application component
│   │   ├── app.component.html      # HTML template for the main component
│   │   ├── app.component.css       # Styles for the main component
│   │   ├── app.module.ts           # Root module of the application
│   │   ├── contact
│   │   │   ├── contact.component.ts # Contact form component
│   │   │   ├── contact.component.html # HTML template for the contact form
│   │   │   ├── contact.component.css  # Styles for the contact form
│   │   │   └── contact.service.ts     # Service for handling form submission
│   │   └── models
│   │       └── contact-form.model.ts  # TypeScript model for contact form data
│   ├── assets                        # Directory for static assets
│   ├── environments
│   │   ├── environment.ts           # Development environment settings
│   │   └── environment.prod.ts      # Production environment settings
│   └── index.html                   # Main HTML file for the application
├── angular.json                     # Angular CLI configuration file
├── package.json                     # npm configuration file
├── tsconfig.json                    # TypeScript configuration file
└── README.md                        # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd angular-contact-app
   ```

3. Install the dependencies:
   ```
   npm install
   ```

## Usage

To run the application, use the following command:
```
ng serve
```
Then open your browser and navigate to `http://localhost:4200`.

## Features

- User-friendly contact form
- Input validation
- Responsive design

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.