# Weather CLI ☀️

A Go (golang) CLI application for weather forecast

## Usage

You should no longer encounter the "API key not found" error when you run `cli-weather` from your Zsh shell.

Then run:

```shell
go build .
```

Move executable to /usr/local/bin
Open Terminal, and run cli-weather + name of the place (Vienna, AT is default with no arguments given)

Make sure to set the env varaible globally. For example, on Unix-like systems (including Linux), you can set environment variables in the /etc/environment file or a profile script like ~/.bashrc or ~/.profile. Here's an example of setting it in ~/.bashrc:

```shell
#!/bin/bash
export WEATHER_API_KEY=your_api_key_here
/usr/local/bin/cli-weather
```

If you're using the Zsh shell, you can set environment variables in your Zsh configuration file, which is typically `~/.zshrc`. Here's how you can set the `WEATHER_API_KEY` environment variable in your Zsh configuration:

1. Open your Zsh configuration file in a text editor. You can use a command like `nano`, `vim`, or any other text editor you prefer:

   ```bash
   nano ~/.zshrc
   ```

2. Add the following line to set the `WEATHER_API_KEY` environment variable. Replace `"your_api_key_here"` with your actual API key:

```bash
export WEATHER_API_KEY=your_api_key_here
```

3. Save the file and exit the text editor.

4. Source your updated Zsh configuration to apply the changes:

```bash
source ~/.zshrc
```

Now, the `WEATHER_API_KEY` environment variable will be available in your Zsh sessions, and any command or executable you run from Zsh, including the `cli-weather` executable, will be able to access this environment variable.


