# modget-bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that GitHub app which regularly checks for updates in the modget manifest repository

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t modget-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> modget-bot
```

## Contributing

If you have suggestions for how modget-bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 NebelNidas <burnerjulian@gmail.com>
