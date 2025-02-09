# CTI_Dashboard

# Cyber Threat Intelligence Dashboard

# Overview
The Cyber Threat Intelligence Dashboard is designed to automate the collection, analysis, and display of cybersecurity threat intelligence from multiple RSS feeds. It helps security analysts track Indicators of Compromise (IoCs), monitor the latest threat intelligence, and reduce mean delta time through automation.

This project leverages scripts developed by the Threat Intelligence team at PHS to enhance efficiency and streamline intelligence gathering.

# Features
✔️ Fetches latest cybersecurity articles from multiple RSS feeds
✔️ Displays IoCs and healthcare-related threats
✔️ Automates intelligence gathering to reduce manual effort
✔️ Live updates when clicking "Latest Articles" or "Update Articles"
✔️ Uses Dash and Python for a responsive UI
✔️ Supports filtering by individual RSS feeds

# Project Scope
The dashboard focuses on Threat Intelligence at PHS and assists team members in automating intelligence collection, minimizing manual work, and enhancing threat monitoring and analysis.
# Installation
    1. Clone the Repository
    git clone https://github.com/yourusername/cyber-threat-intelligence-dashboard.git
    cd cyber-threat-intelligence-dashboard
    2. Install Dependencies
    Create a virtual environment and install required packages:
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    pip install -r requirements.txt
    3. Set Up RSS Sources
    Add your RSS feed URLs to sources.txt in the format:
    FeedName,https://rssfeedurl.com/rss
    4. Run the Dashboard
    python app.py
    The dashboard will be available at:
    ➡️ http://127.0.0.1:8050/
    
# Project Structure
cyber-threat-intelligence-dashboard/
│── app.py            # Main Dash application
│── utils.py          # Functions for fetching and processing RSS feeds
│── sources.txt       # List of RSS feed sources
│── requirements.txt  # Required Python packages
│── README.md         # Project documentation

# Usage
  Start the dashboard (python app.py)
  View the latest articles on the home page
  Click "Latest Articles" to refresh feeds
  Select individual sources from the sidebar
  Analyze threats and IoCs from fetched articles
  
# Dependencies
  Python 3.8+
  Dash
  feedparser
  BeautifulSoup4
  pytz
  dateutil

Contributing
Feel free to contribute! Fork the repo, make changes, and submit a pull request.
License
This project is for internal use at PHS Threat Intelligence Team and follows company policies.

# Author
👤 SABHAVAT PRABHU TEJA
📧 Contact: prabhusabhavat@gmail.com

Future Enhancements
✅ Add real-time API feeds for threat intelligence
✅ Enhance search and filtering capabilities
✅ Integrate IoC tracking and alerts
