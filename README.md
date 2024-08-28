# QuoteBox: A Dockerized Random Quote Generator

QuoteBox is a simple web application that displays random inspirational quotes. It's built using Python Flask and containerized with Docker, making it easy to deploy and run on any system with Docker installed.

## Features

- Displays a random inspirational quote
- Simple and responsive design
- Easy to deploy using Docker

## Prerequisites

- Docker
- Docker Compose (optional, but recommended)

## Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/quotebox.git
   cd quotebox
   ```

2. Build and run the Docker container:

   Using Docker Compose (recommended):
   ```
   docker-compose up --build
   ```

   Or using Docker directly:
   ```
   docker build -t quotebox .
   docker run -p 5000:5000 quotebox
   ```

3. Open your web browser and navigate to `http://localhost:5000` to see the application in action.

## Project Structure

- `app.py`: The main Flask application
- `templates/index.html`: The HTML template for the web page
- `Dockerfile`: Instructions for building the Docker image
- `docker-compose.yml`: Configuration for Docker Compose
- `README.md`: This file, containing project information and instructions

## Customization

To add or modify quotes, edit the `quotes` list in `app.py`. The application will automatically use the updated list of quotes.

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional features.

## License

This project is open source and available under the [MIT License](LICENSE).
