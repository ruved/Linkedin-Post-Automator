# LinkedIn Post Generator

**LinkedIn Post Automator** is a versatile tool designed to generate content using OpenAI's GPT. 

##  Project Structure

### Main Component:
- **main.py**: This file is the central hub of the project. It seamlessly integrates web scraping, ChatGPT processing, and LinkedIn content generation. Once initiated, it operates in a continuous loop, relying on an internal scheduler to roll out content at user-defined intervals.


## How to Run

1. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
2. Rename `example_config.json` to `config.json`.
3. Populate the `config.json` file with your details and preferences.
4. Start the automation with:
    ```bash
    python main.py
    ```

## Internal Scheduling
Equipped with an internal Python scheduler, the tool ensures automated content generation at user-defined intervals, enhanced by random offsets for variability. No external cron configurations are required.

