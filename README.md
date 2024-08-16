### README.md

# Kadena Blockchain Explorer

## Community Requested Functionality

### Summary Screen/Page:
- **Price** (including historical data)
- **Volume** (including historical data)
- **Transactions Per Second**
- **Daily Transaction Volume** (including historical data)
- **Average Transaction Time**
- **Hashrate** (including historical data)
- **Difficulty**
- **Most Active Tokens** on the Kadena Blockchain (including price/volume)
- **All Applicable Information** (supply, max, etc)
- **Twitter Feed**
- **Links to all Wallets**
- **Links to Discord/Telegram**
- **Direct Links to Whitepapers**
- **AMA with an AI**

### Additional Data Points:
- **Blockchain Size Growth**: Tracking the total size of blockchain data (GB/TB) over time.
- **Individual Block Size and Average Block Time**: Analyzing the size of each block and the average time taken to mine them.
- **Average Transaction Gas Fee/Size**: Calculating the average gas fee per transaction size, which relates to the maximum possible transactions per second metric.
- **Miner Stats**: Investigating statistics on miners or mining pools, such as who mined how many blocks (in %).
- **Mempool Status**: Monitoring the 'fullness' of the mempool with pending transactions.

### Standard Metrics:
- **Number of Addresses**
- **Number of Transactions**

## Project Setup

### Requirements:
- Python 3.8+
- Flask (or other web framework)
- Requests (for API calls)
- Pandas (for data manipulation)
- Matplotlib (for data visualization)
- Any additional packages as needed

### Installation:
Clone the repository:
```bash
git clone https://github.com/Tanner-Ray-Martin/Chainweb-Explorer.git
cd Chainweb-Explorer
```

Install the required packages:
```bash
pip install -r requirements.txt
```

### Running the Project:
```bash
python app.py
```

## Task List for Completion

1. **Project Setup:**
   - [ ] Initialize Git repository and upload README.md
   - [ ] Set up the project structure
   - [ ] Install necessary Python packages and create requirements.txt

2. **Data Collection:**
   - [ ] Implement API calls to collect price, volume, transactions, hashrate, etc.
   - [ ] Create functions to fetch and store historical data
   - [ ] Implement data collection for additional data points like blockchain size growth, mempool status, etc.

3. **Backend Development:**
   - [ ] Set up Flask (or other web framework)
   - [ ] Create API endpoints for each data point
   - [ ] Implement data processing and storage

4. **Frontend Development:**
   - [ ] Design the summary screen/page
   - [ ] Implement data visualization (graphs, charts) using Matplotlib
   - [ ] Integrate Twitter feed and external links
   - [ ] Develop UI for additional data points

5. **Integration and Testing:**
   - [ ] Integrate all components
   - [ ] Write unit and integration tests
   - [ ] Perform thorough testing to ensure functionality

6. **Deployment:**
   - [ ] Decide on deployment method (standalone site, cloud, Flux, etc.)
   - [ ] Set up deployment pipeline
   - [ ] Deploy the application

7. **Documentation:**
   - [ ] Write comprehensive documentation for the project
   - [ ] Create a user guide for the application

8. **Community Feedback:**
   - [ ] Gather feedback from the community
   - [ ] Implement suggested improvements and new features

9. **Maintenance:**
   - [ ] Monitor the application for any issues
   - [ ] Regularly update the application with new data and features

Feel free to contribute to the project by submitting issues and pull requests. Your feedback is invaluable in making this explorer a comprehensive tool for the Kadena community.
