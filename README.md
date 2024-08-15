# NASA APOD Viewer

![NASA APOD](https://apod.nasa.gov/apod/image/2201/CometLeonard_Hubble_960.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
The NASA APOD Viewer is a web application built with React and Vite that displays NASA's Astronomy Picture of the Day. It fetches the APOD data from NASA's APOD API and presents it in a user-friendly interface.

## Features
- Displays the Astronomy Picture of the Day.
- Shows detailed information about the APOD including the title, date, and description.
- Responsive design for both desktop and mobile devices.

## Demo
[Insert link to live demo if available]

## Technologies Used
- React
- Vite
- Fetch
- NASA APOD API

## Getting Started

### Prerequisites
Make sure you have the following installed:
- Node.js
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nasa-apod-viewer.git
   cd nasa-apod-viewer
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file in the root directory and add your NASA APOD API key:
   ```env
   VITE_NASA_API_KEY=your_nasa_api_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

## Usage
- Open your browser and go to `http://localhost:3000` to view the app.
- The app will automatically fetch and display the Astronomy Picture of the Day.

## API
This project uses the [NASA APOD API](https://api.nasa.gov/).

To get your API key, visit [NASA's API portal](https://api.nasa.gov/).

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [NASA APOD](https://apod.nasa.gov/) for providing the API and daily astronomy pictures.
- [React](https://reactjs.org/) for the amazing framework.
- [Vite](https://vitejs.dev/) for the fast development build tool.
