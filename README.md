# EquityUpside
### Equity Analysis Report Generator

<small>

#### **Overview**
When running the query-perplexity-llm-stock-analysis.ipynb notebook with an arbitrary txt list of equities, this automatically generates:

- Individual stock analysis reports with key financial and growth highlights followed by BuccoCapital 13 point analysis framework
- ETF and Mutual Fund analysis with key financial and growth highlights, composition, fees, liquidity, etc in the style of Brian Belsky 
- Analyst ratings and price targets (when available)

This notebook uses Perplexity AI's Sonar Pro model via API. Each report is saved as a formatted Microsoft Word document.6. 

Refer to the 'GettingStarted' document in this repo for additional instructions

#### **Features**
- Batch Processing: Processes multiple stocks, ETF's and mutual funds from a simple text file list of tickers. 
- Smart Skipping: Avoids duplicate API calls by checking for existing reports2. 5-year price performance vs. NASDAQ
- Markdown Formatting: Converts AI-generated markdown to professional Word formatting1. Stock ticker and generation date
- Comprehensive Analysis: Includes price performance charts, financial metrics, and analyst ratingsEach report includes:
- Date Stamping: Automatically timestamps each report## Output Format

#### **Requirements**
- Perplexity API Key- easy and pretty cheap
- Input Text file with stock tickers (one per line)  
- Python 3.7+ (suggest installing this at or near your root level: https://www.anaconda.com/docs/getting-started/miniconda/install)
- An application VS Code with jupyter notebook plug-in to run the notebook (hit run all)
- Folder structure locally to get inputs (like equity list) and store outputs (like individual equity reports) Look at getting started .txt file for the right structure and files you need.
- Create an environment file (.env file from text) with your API key and specific folder locations of inputs (like equity list) and outputs (for individual reports).  Look at the getting started .txt file for the right way to structure and create your .env file.  

#### **Output**
- Analysis word document for each equity

#### **Repository**
Feel free to clone, contribute to or fork the repository which has MIT license.
Caveat - this is a quick V1

