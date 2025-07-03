# Financial Decision Making AI System

A comprehensive AI-powered financial analysis system that leverages multiple specialized agents to provide intelligent stock investment recommendations. This system uses CrewAI to orchestrate a team of AI agents that analyze various aspects of stock investments to help users make informed financial decisions.

## 🚀 Features

- **Multi-Agent Analysis**: Utilizes 5 specialized AI agents for comprehensive stock analysis
- **Real-time Market Data**: Analyzes live market data and current stock performance
- **Risk Assessment**: Comprehensive risk evaluation with mitigation strategies
- **Sentiment Analysis**: Analyzes market sentiment from news and social media
- **Regulatory Compliance**: Ensures investments meet legal and regulatory standards
- **Personalized Recommendations**: Tailored advice based on risk tolerance and investment capital
- **Interactive Interface**: User-friendly input system for personalized analysis

## 🤖 AI Agents

### 1. Stock Performance Analyst
- **Role**: Analyzes live market data and predicts future performance
- **Expertise**: Technical analysis, fundamental analysis, and machine learning
- **Focus**: Price trends, volume analysis, moving averages, RSI, and financial metrics

### 2. Portfolio Risk Strategist
- **Role**: Evaluates investment risks and recommends mitigation strategies
- **Expertise**: Value at Risk (VaR) modeling, scenario analysis, portfolio optimization
- **Focus**: Stress testing, volatility assessment, risk mitigation

### 3. Regulatory Compliance Officer
- **Role**: Ensures compliance with legal and regulatory standards
- **Expertise**: SEC, FINRA, MiFID II regulations, compliance frameworks
- **Focus**: Regulatory adherence, compliance auditing, legal risk assessment

### 4. Sentiment Analysis Specialist
- **Role**: Analyzes market sentiment from various data sources
- **Expertise**: Natural Language Processing (NLP), sentiment analysis
- **Focus**: News articles, social media, earnings calls, market perception

### 5. Investment Decision Advisor
- **Role**: Synthesizes all analyses to provide final investment recommendations
- **Expertise**: Portfolio management, strategic decision making
- **Focus**: Buy/Hold/Sell recommendations with actionable insights

## 📋 Prerequisites

### Required APIs
- **OpenAI API**: For AI agent capabilities
- **Serper API**: For web search and data collection

### Python Libraries
```bash
pip install crewai
pip install crewai-tools
pip install warnings
```

## 🔧 Setup Instructions

### 1. API Configuration
Before running the system, you'll need to obtain API keys:

1. **OpenAI API Key**:
   - Visit [OpenAI Platform](https://platform.openai.com/)
   - Create an account or sign in
   - Generate an API key from the API section

2. **Serper API Key**:
   - Visit [Serper.dev](https://serper.dev/)
   - Sign up for an account
   - Get your API key from the dashboard

### 2. Environment Setup
The system will prompt you to configure your API keys in the notebook environment variables:
- `OPENAI_API_KEY`
- `SERPER_API_KEY`
- `OPENAI_MODEL_NAME` (set to "gpt-4o")

### 3. Installation
1. Clone or download this repository
2. Open the Jupyter notebook: `financial_decision_making.ipynb`
3. Install required dependencies
4. Configure your API keys
5. Run the notebook cells sequentially

## 🎯 How to Use

### Step 1: Input Your Investment Parameters
The system will prompt you for:
- **Stock Symbol**: The stock you want to analyze (e.g., AAPL, TSLA, MSFT)
- **Initial Capital**: Your investment amount in USD
- **Risk Tolerance**: Low, Medium, or High
- **Trading Strategy**: Day Trading, Swing Trading, or Long-term Investing

### Step 2: AI Analysis Process
The system automatically:
1. Analyzes current stock performance and technical indicators
2. Evaluates investment risks and scenarios
3. Checks regulatory compliance status
4. Analyzes market sentiment and news impact
5. Generates final investment recommendation

### Step 3: Review Results
Receive a comprehensive report including:
- **Performance Analysis**: Technical and fundamental insights
- **Risk Assessment**: Identified risks and mitigation strategies
- **Compliance Report**: Regulatory status and compliance issues
- **Sentiment Analysis**: Market perception and sentiment trends
- **Final Recommendation**: Clear Buy/Hold/Sell decision with reasoning

## 📊 Sample Output

The system provides detailed reports for each analysis phase:

### Stock Performance Report
- Current price trends and technical indicators
- Growth potential based on fundamental analysis
- Short-term, mid-term, and long-term predictions

### Risk Assessment Report
- Identified risks (market, liquidity, regulatory)
- Stress test results and worst-case scenarios
- Recommended mitigation strategies

### Compliance Report
- Regulatory adherence status
- Compliance issues or red flags
- Corrective action recommendations

### Sentiment Analysis Report
- Key sentiment trends (bullish/bearish)
- Public perception of recent events
- Potential impact on stock performance

### Final Investment Decision
- Clear Buy/Hold/Sell recommendation
- Detailed reasoning and supporting data
- Next steps and portfolio adjustment suggestions

## ⚠️ Important Disclaimers

- **Not Financial Advice**: This system is for educational and informational purposes only
- **Do Your Research**: Always conduct additional research before making investment decisions
- **Market Risks**: All investments carry risk, and past performance doesn't guarantee future results
- **API Costs**: Using OpenAI and Serper APIs may incur costs based on usage
- **Data Accuracy**: Ensure your API keys have access to current market data

## 🔒 Security Notes

- Keep your API keys secure and never share them publicly
- Consider using environment variables or secure vaults for API key storage
- Regularly rotate your API keys for security
- Monitor your API usage to avoid unexpected costs

## 🛠️ Customization

### Adding New Agents
You can extend the system by:
- Creating additional specialized agents
- Modifying existing agent roles and capabilities
- Adding new analysis tools and data sources

### Modifying Analysis Parameters
- Adjust risk assessment criteria
- Customize sentiment analysis sources
- Modify compliance check parameters
- Add new technical indicators

## 📈 Future Enhancements

Potential improvements and features:
- Real-time portfolio tracking
- Multiple stock comparison analysis
- Historical performance backtesting
- Integration with brokerage APIs
- Advanced visualization and reporting
- Mobile app integration
