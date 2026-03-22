The open source project chosen is called "TradingAgents" by TauricResearch
1) Project Overview
  TradingAgents is a multi-agent trading framework that mirrors the dynamics of real-world trading firms. 
  It does so by deploying specialized LLM-powered agents which function as fundamental analysts, sentiment experts, and technical analysts.
  Moreover, these agents engage in dynamic discussions to pinpoint the optimal strategy.

  The software caters to traders and investors, acting as a recommender and executor on their behalf.

2) Repository Structure
<img width="395" height="532" alt="Screenshot 2026-03-22 at 7 58 51 PM" src="https://github.com/user-attachments/assets/617704ce-e0ce-4a41-85f5-5cd6cb47432f" />
<img width="472" height="909" alt="Screenshot 2026-03-22 at 7 59 04 PM" src="https://github.com/user-attachments/assets/32491932-3d9a-406d-b07b-6440ea32e855" />
<img width="305" height="334" alt="Screenshot 2026-03-22 at 7 59 12 PM" src="https://github.com/user-attachments/assets/8bdd3d6b-055f-448d-9589-13e379248233" />

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
   
   
  
