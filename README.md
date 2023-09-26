
## Step 1: Clone Reposistory

`git clone https://github.com/DhruviTMBS/nautilus_trading_scanner.git`


## Step 2: Create a Virtual Environment

`python -m venv venv`


## Step 3: Activate the Virtual Environment
- On Windows:
`venv\Scripts\activate`

- On macOS and Linux:
`source venv/bin/activate`


## Step 4: Install Dependencies from requirements.txt

`pip install -r requirements.txt`


## Step 5: update requirements.txt

`pip freeze > requirements.txt`


## Step 6: Run main.py
1. Replace IB_GATEWAY_OR_TWS_USERNAME and IB_GATEWAY_OR_TWS_PASSWORD with your IB credentials
2. IBG_HOST with your server host
3. IBG_PORT with your server port
4. IBG_ACCOUNT_ID with your account_id of IB gateway/TWS

5. `python main.py`
