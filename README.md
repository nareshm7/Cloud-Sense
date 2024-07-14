
# Climate Sense

Climate Sense is a weather API built using Next.js. It provides real-time weather data for various locations worldwide.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Project](#running-the-project)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- Real-time weather data
- Supports multiple locations
- Easy-to-use API endpoints
- Built with Next.js for fast performance

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- Node.js (v14 or later)
- npm (v6 or later) or yarn (v1.22 or later)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/climate-sense.git
    cd climate-sense
    ```

2. Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    ```

### Running the Project

To start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

To use the API, make GET requests to the endpoints as described below.

### API Endpoints

#### Get Weather Data

```
GET /api/weather?location={location}
```

- **Parameters:**
  - `location` (required): The name of the city or geographical coordinates.

- **Response:**

  ```json
  {
    "location": "City, Country",
    "temperature": "25°C",
    "humidity": "60%",
    "description": "Clear sky",
    "windSpeed": "10 km/h"
  }
  ```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
