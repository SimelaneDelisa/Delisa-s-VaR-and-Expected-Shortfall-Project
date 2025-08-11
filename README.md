# Delisa-s-VaR-and-Expected-Shortfall-Project
Calculating Value at Risk and Expected Shortfall using the parametric method, historical method and Monte Carlo method and backtesting them.
📊 Value-at-Risk & Expected Shortfall — Portfolio Risk Analysis
This project calculates Value-at-Risk (VaR) and Expected Shortfall (ES) for a portfolio of five stocks using:

Parametric Method (Variance-Covariance)

Historical Simulation

Monte Carlo Simulation

It then backtests each method to evaluate accuracy and robustness, identifying which performs best under real market conditions.

🔍 What are VaR and ES?
Value-at-Risk (VaR) estimates the worst expected loss over a specified time horizon at a given confidence level.

Expected Shortfall (ES) measures the average loss in scenarios worse than the VaR threshold, giving a fuller view of tail risk.

📂 Workflow
Data Collection – Historical price data for 5 stocks.

Risk Estimation – Apply all three methods to compute VaR & ES.

Backtesting – Compare predicted VaR against actual losses to test model reliability.

Results – Side-by-side comparison showing Monte Carlo performed best.

⚙ How to Run
bash
Copy
Edit
# Clone this repository
git clone https://github.com/yourusername/VaR-ES-Backtesting-Portfolio.git
cd VaR-ES-Backtesting-Portfolio

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebooks
jupyter notebook notebooks/
📊 Results
Monte Carlo consistently outperformed the other methods in accuracy and reliability during volatile periods.

Example Comparison:

💬 If you’ve ever wondered what quants actually do, let’s connect and share insights!
And to my fellow quants — more projects are coming up as I stay sharp in this niche and fast-evolving field.

