# selfbot-command-runner
Discord SelfBot that will use slash commands for you!

# Author

This was created by `shwp` on [Discord](https://discord.com/users/1014174658179899503)

You can support his main Xbox-based bot called Guh by [buying guh bot a coffee!](https://buymeacoffee.com/guh_bot)

# Setup

1. Make sure you have Node.js installed on your local machine (install here: https://nodejs.org/en/download/prebuilt-installer)

2. Fill in required `config.json` values:
    - token (Authentication for the account)
    - server_id (Server ID of the server the bot will be used in)
    - botid (User ID of the bot)
    - channelid (Channel ID of where the bot will use slash commands)

Optional values to mess with will be listed further below

3. Clone the repository at https://github.com/NoVa-Gh0ul/selfbot-command-runner

4. Open the terminal and run `npm install`

5. Run `node .`

# Config Values

Optional Values Include:

- status: `dnd` | `online` | `idle` | `invisible`
- device_spoof: `phone` | `pc`
- wait_time: integer value supported by `setTimeout()` (Currently set to every 2 hours and 5 minutes)

**Extra Info:**

- wait_time is how long you want the bot to wait before using the command again. You can calculate millisecond values here: https://www.omnicalculator.com/conversion/milliseconds-converter

- loop value *must not* be changed.
