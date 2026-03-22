The open source project chosen is called "TradingAgents" by TauricResearch
1) Project Overview
  TradingAgents is a multi-agent trading framework that mirrors the dynamics of real-world trading firms. 
  It does so by deploying specialized LLM-powered agents which function as fundamental analysts, sentiment experts, and technical analysts.
  Moreover, these agents engage in dynamic discussions to pinpoint the optimal strategy.

  The software caters to traders and investors, acting as a recommender and executor on their behalf.

2) Repository Structure
  .
├── assets
│   ├── analyst.png
│   ├── cli
│   │   ├── cli_init.png
│   │   ├── cli_news.png
│   │   ├── cli_technical.png
│   │   └── cli_transaction.png
│   ├── researcher.png
│   ├── risk.png
│   ├── schema.png
│   ├── TauricResearch.png
│   ├── trader.png
│   └── wechat.png
├── cli
│   ├── __init__.py
│   ├── announcements.py
│   ├── config.py
│   ├── main.py
│   ├── models.py
│   ├── static
│   │   └── welcome.txt
│   ├── stats_handler.py
│   └── utils.py
├── LICENSE
├── main.py
├── pyproject.toml
├── README.md
├── requirements.txt
├── test.py
├── tradingagents
│   ├── __init__.py
│   ├── agents
│   │   ├── __init__.py
│   │   ├── analysts
│   │   │   ├── fundamentals_analyst.py
│   │   │   ├── market_analyst.py
│   │   │   ├── news_analyst.py
│   │   │   └── social_media_analyst.py
│   │   ├── managers
│   │   │   ├── research_manager.py
│   │   │   └── risk_manager.py
│   │   ├── researchers
│   │   │   ├── bear_researcher.py
│   │   │   └── bull_researcher.py
│   │   ├── risk_mgmt
│   │   │   ├── aggressive_debator.py
│   │   │   ├── conservative_debator.py
│   │   │   └── neutral_debator.py
│   │   ├── trader
│   │   │   └── trader.py
│   │   └── utils
│   │       ├── agent_states.py
│   │       ├── agent_utils.py
│   │       ├── core_stock_tools.py
│   │       ├── fundamental_data_tools.py
│   │       ├── memory.py
│   │       ├── news_data_tools.py
│   │       └── technical_indicators_tools.py
│   ├── dataflows
│   │   ├── __init__.py
│   │   ├── alpha_vantage_common.py
│   │   ├── alpha_vantage_fundamentals.py
│   │   ├── alpha_vantage_indicator.py
│   │   ├── alpha_vantage_news.py
│   │   ├── alpha_vantage_stock.py
│   │   ├── alpha_vantage.py
│   │   ├── config.py
│   │   ├── interface.py
│   │   ├── stockstats_utils.py
│   │   ├── utils.py
│   │   ├── y_finance.py
│   │   └── yfinance_news.py
│   ├── default_config.py
│   ├── graph
│   │   ├── __init__.py
│   │   ├── conditional_logic.py
│   │   ├── propagation.py
│   │   ├── reflection.py
│   │   ├── setup.py
│   │   ├── signal_processing.py
│   │   └── trading_graph.py
│   └── llm_clients
│       ├── __init__.py
│       ├── anthropic_client.py
│       ├── base_client.py
│       ├── factory.py
│       ├── google_client.py
│       ├── openai_client.py
│       ├── TODO.md
│       └── validators.py
└── uv.lock


  The main folder within the repository is named "tradingagents". The folder contains files regarding different agents (mentioned under point 1), the dataflow within the project, graph nd th llm_clients
  The llm clients houses the different llm providers which the trader can configureas per their need. The trder need to have th llmprovider key in order to do so.
  Apart from the tradingagents folder, other folders contain png files and cli environment for the user to set up locally.

3) Technology used
  The project focuses on building a multiagent software which helps traders and investors. The project is entirely based on python.
  No signs of database usage.
  The software extracts real time stock data from the market using y_finance standing for yahoo finance which is a well known api for extracting real tme market data.
  The requirements forthe software are:
    typing-extensions
    langchain-core
    langchain-openai
    langchain-experimental
    pandas
    yfinance
    stockstats
    langgraph
    rank-bm25
    setuptools
    backtrader
    parsel
    requests
    tqdm
    pytz
    redis
    rich
    typer
    questionary
    langchain_anthropic
    langchain-google-genai


4) The project dosnot have a contributing.md file.
  Most of th issues are utilized for contributing new ideas and features for the software.
  Few of them are used for fixing bugs
  A lot the issues are typedin chinese which i couldn't understand :(


5) The software looks like a typical college project which is extended at a large scale and made open source.
   The workflow is fairly simple from a financial point of view.
   The project emphasizes on AI and agents rather than complex financial strategies.
   
   
  
