<h3 align="center">Prodigy JSON Server</h3>

<div align="center">

[![Status](https://img.shields.io/website?url=https://dredyne.github.io/Prodigy-Manager)](https://dredyne.github.io/Prodigy-Manager)
[![GitHub Issues](https://img.shields.io/github/issues/dredyne/Prodigy-Manager.svg)](https://github.com/dredyne/prodigy-json-server/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/dredyne/Prodigy-Manager.svg)](https://github.com/dredyne/prodigy-json-server/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 🌱 This repository provides a fake JSON server based on the <a href="https://github.com/typicode/json-server">json-server</a> package. It is used to simulate a product management API for testing purposes with the <b><a href="https://github.com/dredyne/Prodigy-Manager">Prodigy Manager application</a></b>.
</p>

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How to Use with Prodigy Manager](#how_to_use)
- [Contributions](#contributions)
- [License](#license)

## 🌟 Features <a name = "features"></a>

- **Fake REST API**: Simulates a REST API with endpoints for managing product data (CRUD operations).
- **No Configuration Needed**: The server runs using the default configuration from `json-server`.
- **JSON Database**: Store product data in a simple JSON file.
- **Easy Setup**: Quickly set up a local server to test the Prodigy Manager app.

## 🛠️ Installation <a name = "installation"></a>

1. Clone this repository:

   ```bash
   git clone https://github.com/dredyne/prodigy-json-server.git
   ```

2. Navigate to the project directory:

   ```bash
   cd prodigy-json-server
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the JSON server:

   ```bash
   npx json-server -p 3030 ./json/database.json
   ```

5. The server will be running at `http://localhost:3030`. You can now interact with the API and use it for testing the Prodigy Manager application.

## 📚 Usage <a name = "usage"></a>

Once the server is running, you can:

- Access the product data via `http://localhost:3030/products`.
- Use the endpoints to GET, POST, PUT, and DELETE product data.

## 🚀 How to Use with Prodigy Manager <a name = "how_to_use"></a>

To use this fake JSON server with Prodigy Manager:

1. Clone the [Prodigy Manager repository](https://github.com/dredyne/Prodigy-Manager).
2. Follow the instructions in the Prodigy Manager README to set up the app.
3. Make sure the Prodigy Manager app points to `http://localhost:3030` for API requests.

## 🤝 Contributions <a name = "contributions"></a>

Feel free to contribute by submitting issues or pull requests. Your contributions are always welcome!

## 📜 License <a name = "license"></a>

This project is open-source and available under the MIT License. See the [LICENSE](/LICENSE) file for more information.
