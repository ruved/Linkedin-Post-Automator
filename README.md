# LinkedIn Post Generator
LinkedIn Post Automator is a versatile tool designed to generate content using OpenAI's GPT.

# Project Structure
# Main Component:
main.py: This file is the central hub of the project. It seamlessly integrates web scraping, ChatGPT processing, and LinkedIn content generation. Once initiated, it operates in a continuous loop, relying on an internal scheduler to roll out content at user-defined intervals.
How to Run
Install the required Python packages:
pip install -r requirements.txt
Rename example_config.json to config.json.
Populate the config.json file with your details and preferences.
Start the automation with:
python main.py
# Internal Scheduling
Equipped with an internal Python scheduler, the tool ensures automated content generation at user-defined intervals, enhanced by random offsets for variability. No external cron configurations are required.
