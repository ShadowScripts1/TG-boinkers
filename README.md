
# Auto Claim for Boinkers

**Node.js Version Required**: 18 or 20

🔗 **Get User/Query**: [BOINKERS]


## Functionality

| Feature                      | Supported |
| ---------------------------- | :-------: |
| Auto Claim                   |    ✅     |
| User Query Integration       |    ✅     |
| Proxy Support                |    ✅     |
| Multithreading               |    ✅     |
| Scheduled Claiming           |    ✅     |

## Installation

To set up and run the Boinkers bot, follow these steps:

1. **Clone the Repository**:

   ```shell
   git clone https://github.com/ShadowScripts1/TG-boinkers.git
   cd TG-boinkers
   ```

2. **Install Dependencies**:

   ```shell
   npm install
   npm install luxon
   ```

3. **Run the Bot**:

   ```shell
   node main.js
   ```

### With or Without Proxy

| Run with Proxy                           | Run without Proxy                |
| ---------------------------------------- | -------------------------------- |
| Edit `boinkers.txt` and `proxy.txt`      | Use `boinkers.txt` in `main.js`  |

## [Settings](https://github.com/ShadowScripts1/TG-boinkers/blob/main/.env-example)

| Setting Key      | Description                                                                              |
| ---------------- | ---------------------------------------------------------------------------------------- |
| **QUERY_ID**     | Unique query identifier obtained from DevTools                                           |
| **USER_ID**      | User ID obtained from DevTools                                                           |
| **PROXY_LIST**   | Path to proxy file (Optional)                                                            |
| **AUTO_CLAIM**   | Enables auto claim functionality (True / False)                                          |
| **RANDOM_DELAY** | Interval between auto claims (e.g., `[10,20]` for random delay of 10-20 seconds)         |

> ⚠️ **Note**: To get `query_id` or `user_id`, open the `Application` tab in DevTools.

## 💱 Support Me

If you found this tool useful, consider supporting me:

- EVM: `0x7BeE9994a631523e22A3aB83039c196bFc6BC513`
- SOLANA: `6mbFy6AojWo3J5ksa1SYHHyCWw5Bms4p9McKmaFkCsyW`
