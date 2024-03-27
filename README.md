# Project Name

This project is a Go application that connects to an Ethereum RPC provider and sends a blob transaction based
on the new EIP-4844.

## Prerequisites

- Go 1.22 or later
- An Ethereum RPC provider URL (e.g., Infura, Alchemy)
- A private key for signing transactions

## Installation

1. Clone the repository:

```bash
git clone https://github.com/jeffprestes/blob-tx-go.git
```

2. Navigate to the project directory:

```bash
cd blob-tx-go
```

## Usage

Before running the application, you need to set the following environment variables in the main.go file:

- `ProviderRpcUrl`: The URL of your Ethereum RPC provider.
- `PrivateKeyInHex`: The private key used to sign transactions.
- `Recipient`: The transaction recipient

Then, you can run the application with:

```bash
go run main.go
```

This will connect to the Ethereum network, create a blob transaction, sign it with your private key, and send it to the network.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)