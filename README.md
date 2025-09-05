# Multi Touch Attribution using AI Agents

This project implements AI Agents (using Agno) to choose attribution strategies and review the performance of those strategies on current data. The strategies implemented are first-touch, last-touch, linear, and algorithmic. The algorithmic strategy implements an A/B simulation based revenue lift for each channel. The channels considered here are social, email, referral, organic search, paid search, and display.

## Getting Started

### Prerequisites
There are two prerequisites apart from the Python packages:
1) Streamlit: The UI is built on local streamlit platform, so the system shoiuld be able to host it and run it locally on the web browser.
2) OpenAI API key: The UI asks for your OpenAI API key at the start. The key is not stored and there is a button in the UI to remove the key manually.


### Installing

There are two CSVs included in the repository for a demo run. 

Step 0 (Optional): Generate two CSVs using the synthetic_data_generator notebook. The two datasets represent the historical data, and the current data. Edit the channel list to add or change the channels. The dates for the data can be changed as well.

Step 1: On a terminal, run 
```
streamlit run frontend_st.py
```

Step 2: Follow the instructions on the UI. It starts with providing your OpenAI API key and then uploading both the CSVs. The results should load below it shortly. There's a reset UI button to regenerate the results, and reset key button to remove the API key.

## Links
LinkedIn: https://www.linkedin.com/in/pb1807/
Website: https://preeyonuj.github.io/
Medium: https://medium.com/@preeyonujb1
