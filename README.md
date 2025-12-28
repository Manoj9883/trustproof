# TrustProof 🔐  
A machine learning–powered tool for detecting Sybil wallets based on wallet activity across Ethereum, Base, and Solana chains.

## 🚀 Objective  
The goal of TrustProof is to classify wallets as human or Sybil (fake) by analyzing blockchain activity data. This will help crypto projects prevent Sybil attacks, ensure fair airdrop distributions, and maintain the integrity of Web3 ecosystems. LETS SEE

## 🧠 What Is a Sybil Wallet?  
A Sybil wallet is typically created by a user pretending to be multiple people in order to manipulate rewards, airdrops, or governance votes. These wallets often follow detectable patterns of behavior.

## 🔬 How It Works  
We use labeled blockchain datasets (Sybil vs human wallets) and extract behavioral features from:

- Ethereum & Base historical transactions  
- ERC-20 token transfers  
- DEX swap data  
- (Coming Soon) Solana activity  

These features are used to train a machine learning model that outputs a Sybil probability score from 0 to 1 for any given wallet.

## 🗂 Project Structure
trustproof/
├── data/ ← Raw datasets (CSV files: txns, swaps, sybil labels)
├── notebooks/ ← Jupyter Notebooks for EDA & feature engineering
├── model/ ← Model training, validation, and saved weights
├── api/ ← Code for backend API (to query Sybil score)
├── frontend/ ← UI for submitting wallet addresses and viewing results
└── README.md ← You're here!
## 🔧 Technologies

- Python, Pandas, NumPy
- Scikit-learn or XGBoost
- Jupyter Notebooks
- GitHub for version control
- (Planned) FastAPI or Flask for backend
- (Planned) React or Glide for frontend

## ✅ Current Status

- ☑ GitHub repo initialized  
- ☑ Folder structure set up  
- 🔄 Uploading and processing labeled data  
- 🔜 Feature engineering in progress  

## 🙋‍♂ Team  
- Sayan Rawl — Developer, CST Dept. @apc roy polytechnic college  
- Manoj Karan — Research, product planning, design  
