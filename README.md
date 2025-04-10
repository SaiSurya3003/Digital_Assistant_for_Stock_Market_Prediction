# 📊 FinalyticsBot

<div align="center">

</div>

## 💰 About FinalyticsBot

FinalyticsBot is a Telegram bot designed to assist users with financial analytics, risk profiling, stock recommendations, and personal finance tips. The project was developed by students at Amrita Vishwa Vidyapeetham, Bengaluru as a final year project.

## ✨ Features

- **Risk Profile Test**: Evaluate your financial risk tolerance and receive personalized recommendations
- **Stock Analysis**: Get detailed information and predictions about stocks
- **Personal Finance Tips**: Receive practical advice on managing your finances
- **Regular Updates**: Subscribe to receive alerts and financial news updates
- **User-Friendly Interface**: Simple and intuitive command system

## 🤖 Bot Commands

### General Commands
- `/start` - Start or restart the bot
- `/help` - View list of available commands
- `/about` - Get information about the bot
- `/contact` - Contact admins for queries or feedback
- `/terms` - View terms and conditions
- `/developers` - Get information about the developers
- `/clear` - Delete chat history
- `/subscribe` - Subscribe to alerts and news updates

### Financial Commands
- `/riskprofiletest` - Take a test to determine your risk profile
- `/acceptedstocks` - View a list of accepted stocks for analysis
- `/stocks` - Get stock predictions and information
- `/tips` - Receive personal finance tips

## 🚀 How to Use

1. **Start the bot**: Open Telegram and search for `@FinalyticsBot`
2. **Begin interaction**: Send `/start` to initiate the bot
3. **Explore commands**: Use `/help` to see all available commands
4. **Take the risk profile test**: Use `/riskprofiletest` to assess your financial risk tolerance
5. **Get stock information**: Use `/stocks -d [stock_symbol]` for details or `/stocks -p [stock_symbol]` for predictions

## 🧠 Technology Stack

- **Python**: Core programming language
- **Telegram Bot API**: Interface for Telegram integration
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning implementation (KNN algorithm)
- **BeautifulSoup**: Web scraping for financial data

## 🛠️ Project Structure

```
FinalyticsBot/
├── FinalyticsBot.py      # Main bot implementation
├── createDataset.py      # Script for creating and updating the stock dataset
├── knn_model.ipynb       # Jupyter notebook for KNN model development
├── stockSuggestion.ipynb # Jupyter notebook for stock recommendation system
├── visuals.py            # Visualization utilities
└── assets/               # Additional resources and documents
    ├── terms and conditions.pdf
    └── stock symbols and names list.pdf
```

## 📊 Risk Profile Analysis

The bot evaluates your risk profile based on:
- Net worth assessment
- Income saving rate
- Dependencies
- Job stability
- Market expertise
- Loss tolerance
- Time horizon for investments

Based on these factors, it categorizes your risk profile as:
- Very Low
- Low
- Moderate
- High
- Very High

## 🔧 Setup for Developers

If you wish to run your own instance of the bot:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/FinalyticsBot.git
   cd FinalyticsBot
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a new Telegram bot via [BotFather](https://t.me/botfather) and obtain your API token

4. Update the `api_token` variable in `FinalyticsBot.py` with your token

5. Run the bot:
   ```bash
   python FinalyticsBot.py
   ```

## 👥 Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://yvsravan2000.github.io/">
        <img src="https://img.shields.io/badge/Sravan%20Kumar-Contributor-blue" alt="Sravan Kumar"/><br />
        <sub><b>Sravan Kumar</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/ajith-pai-237a66171/">
        <img src="https://img.shields.io/badge/Ajith%20Pai-Contributor-blue" alt="Ajith Pai"/><br />
        <sub><b>Ajith Pai</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.facebook.com/profile.php?id=100009412482740">
        <img src="https://img.shields.io/badge/Yeswanth%20Sai-Contributor-blue" alt="Yeswanth Sai"/><br />
        <sub><b>Yeswanth Sai</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.facebook.com/sai.surya.77377">
        <img src="https://img.shields.io/badge/Sai%20Surya-Contributor-blue" alt="Sai Surya"/><br />
        <sub><b>Sai Surya Teja Makarla</b></sub>
      </a>
    </td>
  </tr>
</table>

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<div align="center">
  
### 💡 Financial Wisdom
  
*"A budget is telling your money where to go instead of wondering where it went."* – John C. Maxwell

</div>
