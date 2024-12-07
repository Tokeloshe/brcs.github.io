# BRCS Coin

Welcome to the official repository for **BRCS Coin**! BRCS Coin is a Stellar Lumens (XLM) based token designed to represent and facilitate economic collaboration among the BRICS nations (Brazil, Russia, India, China, and South Africa).

## 🏛️ About BRCS Coin

**BRCS Coin** serves as a bridge for economic cooperation and growth among the BRICS nations. Built on the Stellar network, BRCS Coin leverages Stellar's fast and low-cost transactions to enable seamless financial interactions between these emerging economies.

### 🌟 Key Features

- **Interoperability:** Seamlessly integrates with the Stellar ecosystem, allowing for easy transfers and transactions.
- **Low Fees:** Enjoy minimal transaction fees, making it cost-effective for both small and large transactions.
- **Fast Transactions:** Benefit from Stellar's rapid transaction processing times, ensuring your transactions are completed quickly.
- **Security:** Utilizes Stellar's robust security protocols to safeguard your assets and transactions.

## 🔗 How to Use BRCS Coin

### 1. **Create a Stellar Wallet**

To interact with BRCS Coin, you first need a Stellar wallet. Here are some popular options:

- **StellarTerm:** Access StellarTerm by visiting `https://stellarterm.com/`. StellarTerm is a web-based Stellar wallet that allows you to manage your Stellar assets securely.
- **Solar Wallet:** Download Solar Wallet from `https://www.solarwallet.io/` for a mobile-friendly experience.
- **StellarX:** Visit `https://stellarx.com/` to use another web-based wallet option.

### 2. **Add BRCS Coin to Your Wallet via Trustlines**

BRCS Coin is an asset on the Stellar network, which means you'll need to establish a trustline to hold it in your wallet. Follow these steps:

1. **Open Your Stellar Wallet:**
   - Navigate to your chosen Stellar wallet (e.g., StellarTerm, Solar Wallet).

2. **Locate the Trustlines Section:**
   - In StellarTerm, go to the **"Assets"** tab.
   - In Solar Wallet, find the **"Manage Assets"** or **"Add Asset"** option.

3. **Add a New Trustline:**
   - Enter the following details to add BRCS Coin:
     - **Asset Code:** BRCS
     - **Issuer:** GBBWWZQDSIBY4RVA2X3RCOMSWMYM3OOMOVISYQ2JNJWUTSL5GATEDRKL

4. **Confirm the Trustline:**
   - Submit the request to establish the trustline. This may require a small amount of XLM to cover the transaction fee.

5. **BRCS Coin is Now Available:**
   - Once the trustline is established, BRCS Coin will appear in your wallet's asset list, allowing you to send, receive, and manage your BRCS Coin holdings.

### 3. **Where to Purchase BRCS Coin**

BRCS Coin can be purchased on the following platforms:

- **StellarTerm Exchange:** Visit `https://stellarterm.com/` to trade Stellar Lumens (XLM) for BRCS Coin directly.
- **CoinMarketCap:** Check `https://coinmarketcap.com/` for a list of exchanges where BRCS Coin is listed.
- **CEX.IO:** Access `https://cex.io/` to buy BRCS Coin using various payment methods.

*Please ensure you are using reputable exchanges to purchase BRCS Coin to safeguard your investments.*

## 🔍 Stellar.toml Configuration

For platforms like StellarTerm to recognize and display BRCS Coin with its custom logo, the `stellar.toml` file must be correctly configured and hosted. You can view the `stellar.toml` file [here](https://brcs.github.io/.well-known/stellar.toml).

### 📄 Example `stellar.toml`

```toml
# stellar.toml

# Documentation Section
[DOCUMENTATION]
ORG_NAME = "BRCS Project"
ORG_URL = "https://brcs.github.io"
ORG_DESCRIPTION = "BRCS Coin is a representative token for the BRICS nations, fostering economic collaboration and growth."

# Asset Information
[[CURRENCIES]]
code = "BRCS"
issuer = "GBBWWZQDSIBY4RVA2X3RCOMSWMYM3OOMOVISYQ2JNJWUTSL5GATEDRKL"
display_decimals = 7
name = "BRCS Coin"
desc = "A representative token for BRICS nations, symbolizing economic collaboration and growth."
image = "https://brcs.github.io/images/logo.png"
