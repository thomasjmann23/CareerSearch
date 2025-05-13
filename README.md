# Career Search Application

This application assists with career searches by allowing users to query job listings based on company names and keywords. The app fetches career pages, processes the data using web scraping techniques, and generates a list of relevant job opportunities. It provides an interactive, user-friendly interface with filtering options and CSV export functionality.

## Features

- Load a CSV file with company information or start with an empty request.
- Generate new company entries using AI models based on existing data.
- Validate and confirm career page URLs (Valid, Invalid, or Human Needed).
- Use AI models to query career pages and filter job listings based on job title keywords.
- Allow users to bookmark and view saved job listings.
- Filter out job titles based on specified keywords.
- Download results as a CSV file with company, career page URL, and query parameters.
- Authentication via email submission for tracking usage (optional).
- No long-term storage is required.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/thomasjmann23/CareerSearch.git
   cd CareerSearch
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use 'venv\Scriptsctivate'
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

5. Open your browser and go to the provided local URL.

## Technologies

- **Python** for backend logic and processing.
- **Streamlit** for building the user interface.
- **BeautifulSoup** and **Selenium** for web scraping and extracting job data.
- **Pandas** for data manipulation and CSV generation.
- **Gemini & OpenAI** for generating new companies and querying job listings.
- **Email tracking** for user identification.
- **GitHub** for version control and collaboration.

## Usage

1. Load a CSV file or start a new session.
2. Generate a list of new companies using the AI model.
3. Confirm career page URLs (mark as Valid, Invalid, or Human Needed).
4. Use job title keywords to filter listings.
5. Bookmark or favorite listings for later review.
6. Filter job listings by title keywords.
7. Download the results as a CSV file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
