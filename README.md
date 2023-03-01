# Twitter Phishing IoCs to MISP
The project consist of extracting Phishing IoCs (Indicator of Compromise) from Twitter and add them to MISP Instance.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install (pandas, gspread, pymisp, plotly).

```bash
pip install pandas gspread pymisp plotly
```

## Configuration 

1. Create a PowerAutomate Workflow From *'Save a Tweets to a Google Sheet'* Template
![PowerAutomate Workflow](PowerAutomateWorkflow-Phishing.png "PowerAutomate Workflow")

2. Configure a Google Cloud service to interact with the Google Sheet from the Python code.
3. Create an *Authentification Key* bound to the Publisher user. 

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.