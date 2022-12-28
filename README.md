### Telegram-Expense-Bot
A telegram bot to keep track of daily expenses, using Node.JS, AWS DynamoDB and automated expense summaries using AWS Lambda and AWS CloudWatch.

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/PierT20/Expendo101.git
   ```
2. Install NPM packages in /bot directory
   ```sh
   npm install
   ```
3. Configure .env files
   ```sh
   TOKEN=<Telegram Token Here>
   TABLE_NAME=<Table Name of DynamoDB Here>
   ```
4. Run the bot
   ```sh
   node bot.js
   ```
The bot will start and a DynamoDB table will be created with the variable name for "TABLE_NAME"
