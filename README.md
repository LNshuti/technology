# U.S. Tech Equities Market Technical Indicator Visualization 

This Python [application](https://leoncensh-energy.hf.space) allows users to visualize stock data and technical indicators **(SMA, MACD, RSI, Bollinger Bands)** for selected companies. The app fetches historical stock data using Yahoo Finance, computes various technical indicators, and displays the plots interactively through a Gradio interface.

This tool provides an intuitive way for business users and analysts to quickly visualize key technical indicators without needing deep expertise in coding or data processing, making stock analysis more accessible and engaging.


**Exhibit 1. Oracle Corporation -- Simple Moving Average**


## Customize this Application with your own Stock List

### Clone this Repository

```bash
git clone https://github.com/LNshuti/energy.git
```

### Setup your Environment
```bash
conda env create --file=environment.yaml
```

### Activate your Environment
```bash
conda activate stock-data
```

### Install Dependencies
```bash 
pip install -r requirements.txt
```

### Run the **app.py** to Launch the Gradio Application
```bash 
python src/main.py
```

**If you found the app useful, please make sure to give us a star!**

![image](https://github.com/user-attachments/assets/0cf41a00-0abb-4223-a8f0-fd3b10bea6d5)


### Customize the Ticker List
You can modify the `COMPANY_TICKERS` dictionary in the Python file to add or remove companies based on your needs.

```python
COMPANY_TICKERS = {
    'Constellation Software ': 'CEG',
    'BP': 'BP',
    # Add more companies here...
}
```

![image](https://github.com/user-attachments/assets/44da4cc5-e26d-4f8c-bbf9-2a1d33cae4c7)


