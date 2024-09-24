# TypeScript Fetch Project

This project demonstrates the use of **TypeScript** and the **Fetch API** to retrieve data and dynamically generate tables, charts, and other elements in a web application. It includes multiple HTML files and JavaScript files for creating visual components like charts and tables.

## Project Structure

- **HTML Pages**: Several HTML files for different sections of the project:
  - `index.html`: Main page or starting point of the application.
  - `contatos.html`: Contacts-related section.
  - `eventos.html`: Events-related section.
  - Additional HTML pages like `inicio.html` and `loading.html` serve other parts of the app.

- **JavaScript Files**: The project includes various JavaScript files for generating dynamic content:
  - `criarGrafico.js`: Generates a chart with data.
  - `criarGraficoVolume.js`: Handles volume data for chart creation.
  - `criarTabela.js`: Builds tables dynamically with fetched data.
  - `eventos.js`: Manages event-related operations on the page.

## Features

- **Dynamic Data Fetching**: Uses the Fetch API to retrieve and display data from external sources or APIs.
- **Chart Generation**: Creates dynamic charts using JavaScript.
- **Table Creation**: Generates tables based on the fetched data, allowing for interactive and dynamic content updates.
- **Multiple Sections**: Each HTML page serves a different function within the application, making it modular and organized.

## How to Run the Project

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Alan-VSouza/Fetch-API-Web-App.git
```

2. Open the `index.html` file in your browser to start exploring the project.

3. Ensure you are running a local server if the application makes any requests to external APIs, as the Fetch API may require server context.

## Requirements

- A modern browser with support for the **Fetch API** and JavaScript ES6+.
- **Node.js** (optional): If you want to extend the project using TypeScript or package managers.

## Technologies Used

- **TypeScript**: Strongly typed superset of JavaScript (optional).
- **Fetch API**: For making HTTP requests to fetch data dynamically.
- **JavaScript**: Handles the logic for chart and table creation.

