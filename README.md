# Start-up-Prediction
# Introduction
Startup refers to a company that is in their first stages of operations. Startups can be founded by one or more entrepreneurs who are working on developing a product or service. Startups normally have very high cost and limited revenue. As they require a lot of capital to take it off the ground, they look for capital from a lot of sources like venture capitalists.

Startups go through multiple rounds of funding to raise capital. The different funding rounds that let outside investors the opportunity to invest cash in exchange of equity or partial ownership of the company. Other types of investments are debt, convertible note, stock or dividends. Startups can start off with “seed” funding or angel investor funding at the beginning. The next funding rounds can be followed by Series A, B, C and so on. Goal of most startups is to get acquired by a different company or become a publicly traded company.

90% of startups fail due to bad product market fit, marketing problems, team problems or other issues. They also fail within the first few years. This makes startup investment very risky. Historically only venture capitalists could invest in startups but due to the recent trend in crowdfunding sites, an average investor can easily grab a piece of an exciting startup.

# Dataset
To train the machine learning model, we used investment data about startup companies available on Kaggle. The data has been collected from Crunchbase which is a leading website for company insights from early stage startups to Fortune 1000.

The data had around 54k rows and 39 columns. The dataset had company information such as name of the company, url, market, country, state, region, city, founded date, first funding date, last funding date. It also had data on different investment types such as seed, venture equity crowdfunding, undisclosed funding, convertible note, debt financing, angel, grant, private equity, post ipo equity, post ipo debt, secondary market, product crowdfunding, round A-H series funding. Status of the companies were also available and segmented by acquired, operating and closed.

🚀 Startup Success Prediction Model
This project trains a RandomForestClassifier to predict whether a startup will succeed or fail based on historical Crunchbase data.

📂 Dataset
The dataset contains 54,000 rows and 39 columns collected from Crunchbase.
Key features used:
funding_rounds: Number of investment rounds the startup has gone through.
total_funding_usd: Total funding received in USD.
status: Target variable (Acquired, Closed, or Operating).
