# Weather CLI ☀️

A Go CLI application for weather forecast in your Terminal.

## Usage

Make sure you add .env file with your own API key from https://www.weatherapi.com, like:

```shell
export WEATHER_API_KEY=123456789ABCD
```

Then run:

```shell
go build .
```

Then, move executable to /usr/local/bin if you use MacOS.

Open Terminal, and run `cli-weather` + name of the place (Vienna, AT is default).
