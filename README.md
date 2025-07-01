This project explores the use of deep reinforcement learning (DRL) for automated stock trading using historical data from the Dow Jones 30. 
Two DRL algorithms, Proximal Policy Optimization (PPO) and Advantage Actor-Critic (A2C) are trained and evaluated on a custom trading environment.

Features:
  - Custom OpenAI Gym environment (SimpleTradingEnv) with 5-day lookback window
  - Uses technical indicators (SMA5, SMA20) as state features
  - Trains PPO and A2C agents on 2018–2025 historical data
  - Compares DRL strategies to a baseline Buy & Hold strategy
  - Visualizes ROI, portfolio value, and cumulative rewards

Results:
DRL agents outperformed Buy & Hold on average in ROI and final portfolio value, with PPO showing the most consistent performance.
