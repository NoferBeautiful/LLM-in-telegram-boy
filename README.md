# LLM-in-telegram-bot

Standart statistical language model based on n-grams. Model integrated into Telegram bot via user-friendly UI.

The way to approximate the next token probability is:

$$p(x_t | x_{t-k}, x_{t-k + 1}, \ldots, x_{t - 1}) = \frac{N(x_{t-k}, x_{t-k + 1}, \ldots, x_{t - 1}, x_t) + \alpha}{N(x_{t-k}, x_{t-k + 1}, \ldots, x_{t - 1}) +  \alpha |V|}$$

## Commands:

/help - get the list of all commands.
/start - launch the bot.
