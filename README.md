# RASA Week 1 Research Core

## Project Overview
This project is focused on developing a research-centered application utilizing the RASA framework. It aims to facilitate research efforts by providing tools and components necessary for efficient data gathering and processing.

## Folder Structure
```
- `data/` - Contains raw and processed data for analysis.
- `scraper/` - Houses the research paper scraper module.
- `models/` - Stores trained models.
- `config/` - Configuration files for RASA.
```

## Installation Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/bobtech-IIT/rasa-api.git
   ```
2. **Navigate into the project directory**
   ```bash
   cd rasa-api
   ```
3. **Install necessary dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Usage Instructions for the Research Paper Scraper
To use the research paper scraper, follow these steps:
1. Ensure you are in the project directory.
2. Run the scraper script:
   ```bash
   python scraper/paper_scraper.py
   ```

## Output CSV Format Documentation
The output from the research paper scraper is saved in a CSV format with the following columns:
- `title` - The title of the research paper.
- `authors` - A list of authors associated with the paper.
- `abstract` - A brief summary of the paper's contents.
- `url` - The link to access the paper.
- `publication_date` - The date of publication.