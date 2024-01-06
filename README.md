# Shopping React App

## Overview

Shopping React App is an intuitive and user-friendly application that allows users to manage their shopping expenses effectively. Designed to simplify budget tracking, this application enables users to add shopping expenses and calculate the total cost seamlessly.

## Features

- **Add Expenses**: Easily input individual expenses and categorize them.
- **Calculate Totals**: Automatically calculate the total of all entered expenses.
- **User-Friendly Interface**: Simple and intuitive design for easy navigation and usage.

## Live Demo

Check out the live demo of the Shopping React App [here](https://reactshoppingappianklein.netlify.app/).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed on your system:

- [Git](https://git-scm.com/downloads)
- [Docker](https://www.docker.com/products/docker-desktop)

### Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/IanKlein6/Shopping-Calculator-App-React.git
    cd shopping-react-app
    ```

2. **Dockerize the application**

    Build the Docker image using the following command:

    ```bash
    docker build -t shopping-react-app .
    ```

    This command builds the Docker image with the tag `shopping-react-app`.

3. **Run the application**

    Once the build is complete, you can run the application:

    ```bash
    docker run -p 8000:80 shopping-react-app
    ```

    This command runs the Docker container and maps the container's port 80 to the local port 8000.

4. **Access the application**

    The app will be running at [http://localhost:8000](http://localhost:8000). Open this link in your browser to start using the Shopping React App locally.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the [MIT License](LICENSE).
