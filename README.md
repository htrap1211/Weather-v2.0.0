

# Weather v2.0.0

This is a simple command-line application that provides current weather information for a given city. The application utilizes the OpenWeatherMap API to fetch current weather data.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/htrap1211/Weather-v2.0.0.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Weather-v2.0.0
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory of the project and set your OpenWeatherMap API key as the value for `API_KEY`:

   ```
   API_KEY=<your OpenWeatherMap API key>
   ```

5. You're ready to use the application!

## Usage

To use the application, simply run the `index.js` file with node, passing the name of the city as an argument:

```bash
node index.js <city name>
```

For example:

```bash
node index.js London
```

The application will then output the current weather information for the specified city.

## Contributing

If you'd like to contribute to this project, please feel free to open a pull request.
