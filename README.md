# botctl
Bot scripts for controlling discord bots on a server.

## Configuration
The script uses bash variables and functions for configuration. Default configuration and example configuration can be found at the start of the script.

`botctl` first uses its default configuration as defined in the script, and then sources the bash script at `$HOME/.config/botctl` if it exists. Then, `botctl` checks if the bash script `.botctl` exists in the bot directory, and sources it too if it exists.
