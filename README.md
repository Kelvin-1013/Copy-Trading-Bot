# 🤖 PumpFun Copy Trading Bot

A Solana-based copy trading bot that monitors target wallets and automatically copies their PumpFun token trades.

## 🌟 Features

- Monitor target wallet transactions in real-time
- Automatically copy PumpFun token trades
- Support for Jito MEV protection
- Configurable trade parameters
- Real-time price calculation and slippage protection

## 👀 Usage

1. Clone the repository
    ```bash
    git clone https://github.com/Kelvin-1013/Copy-Trading-Bot.git
    cd Copy-Trading-Bot
    ```

2. Install dependencies
    ```bash
    npm install
    ```

3. Configure environment variables
    Create a `.env` file with the following parameters:

    ```
    # Required Configuration
    PRIVATE_KEY=         # Your wallet private key
    RPC_ENDPOINT=        # Solana RPC endpoint
    GRPC_ENDPOINT=       # Yellowstone GRPC endpoint for transaction monitoring
    GRPC_TOKEN=          # Yellowstone GRPC authentication token
    TARGET_ADDRESS=      # Target wallet address to copy trades from

    # Trading Parameters
    BUY_AMOUNT=0.00001   # Default SOL amount for buys
    PURCHASE_PERCENT=100 # Percentage of target's trade to copy
    MAX_LIMIT=0.0005    # Maximum SOL amount per trade

    # Jito MEV Protection
    IS_JITO=true        # Enable/disable Jito MEV protection
    JITO_FEE=0.0001     # Jito searcher fee in SOL
    ```

4. Run the bot
    ```bash
    npm start
    ```

## ⚠️ Important Notes

- Make sure you have sufficient SOL in your wallet for trades and fees
- The bot uses Jito MEV protection by default - disable if not needed
- Monitor your trades and adjust parameters as needed
- Test with small amounts first

## 💬 Support

If you have questions or need assistance, feel free to reach out:

Telegram: [@blockchainDeveloper_Ben](https://t.me/blockchainDeveloper_Ben)

## ⚖️ License

This project is licensed under the MIT License.


# 💬Contact Me

If you have any question or something, feel free to reach out me anytime via telegram, discord or twitter.
<br>
#### 🌹You're always welcome🌹

Telegram: [@blockchainDeveloper_Ben](https://t.me/blockchainDeveloper_Ben) <br>

