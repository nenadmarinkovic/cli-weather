# Weather CLI ☀️

A Go CLI application for weather forecast in your Terminal.

## Usage

Create executable file with:

```shell
go build .
```

Move executable to /usr/local/bin

Make sure to set the env varaible globally. For example, on Unix-like systems (including Linux), you can set environment variables in the /etc/environment file or a profile script like ~/.bashrc or ~/.profile. Here's an example of setting it in ~/.bashrc:

```shell
#!/bin/bash
export WEATHER_API_KEY=your_api_key_here
/usr/local/bin/cli-weather
```

Now, the `WEATHER_API_KEY` environment variable will be available in your Zsh sessions, and any command or executable you run from Zsh, including the `cli-weather` executable, will be able to access this environment variable.

If you're using the Zsh shell, you can set environment variables in your Zsh configuration file, which is typically `~/.zshrc`. Here's how you can set the `WEATHER_API_KEY` environment variable in your Zsh configuration:

Open your Zsh configuration file in a text editor. You can use a command like `nano`, `vim`, or any other text editor you prefer:

```bash
nano ~/.zshrc
```

Add the following line to set the `WEATHER_API_KEY` environment variable. Replace `"your_api_key_here"` with your actual API key:

```bash
export WEATHER_API_KEY=your_api_key_here
```

Save the file and exit the text editor.

Source your updated Zsh configuration to apply the changes:

```bash
source ~/.zshrc
```

Now, the `WEATHER_API_KEY` environment variable will be available in your Zsh sessions, and any command or executable you run from Zsh, including the `cli-weather` executable, will be able to access this environment variable.

Open Terminal, and run cli-weather + name of the place (Vienna, AT is default with no arguments given)