# Pumpski Release 

## Version: 4.0.12
#### Bundler, Volume, Bumps & Comments

<br>

#### Installation Instructions

1. **Download the package** and extract the contents.
2. **Fill in the required details** in the `config.json` file. Do **NOT** change the `BACKEND_PORT` and `FRONTEND_PORT` values, as this will break the backend API.
   - **Example `config.json`**:
     ```json
     {
       "REACT_APP_HELIUS_RPC_URL": "your-rpc-url",
       "REACT_APP_MAIN_WALLET_SECRET": "your-secret-key",
       "BACKEND_PORT": "3001", 
       "FRONTEND_PORT": "3002"
     }
     ```
   - Replace `your-rpc-url` with your actual RPC URL.
   - Replace `your-secret-key` with your main wallet secret key.
   
3. **Run the `install.bat`** file located in the `INSTALL_GUIDE` folder to configure the application.
4. **Run the Pumpski executable** to start the application.
5. **Visit the bot** by opening `localhost:3002` in any modern browser like Chrome, Firefox, Opera, or Brave.

### Contact
- Discord @ dangeracorn
- Telegram @ dangeracorn

### Troubleshooting
- If you encounter any issues, check the logs or reach out me on Telegram @DangerAcorn
- Ensure you are using a modern browser (Chrome, Firefox, Opera, or Brave) to access the bot.
- Do **NOT** modify the `BACKEND_PORT` and `FRONTEND_PORT` values in `config.json`, as it may break the backend API.
