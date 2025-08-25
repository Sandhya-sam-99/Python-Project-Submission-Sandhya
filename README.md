🎬 Movie Genre Scraper 📌 Project Description

This project is a Movie Genre Scraper built with Python. It allows users to interactively select a movie genre from a graphical user interface (GUI) and automatically fetch the top 30 movies of that genre from IMDb .

The application uses Selenium WebDriver to automate browser actions, navigates to the IMDb search page, and scrapes movie details such as:

Movie Name (cleaned without serial numbers)

Genre (selected by the user)

Release Year

Movie Length/Runtime

IMDb Rating

Description/Plot summary

Once the scraping process is complete, the program saves the extracted data into a CSV file on the user's Desktop. The file is named after the selected genre (e.g., Action_movies.csv).

The program is designed with a user-friendly GUI using Tkinter, which makes it accessible for non-technical users as well. The GUI includes radio buttons for genre selection, a submit button to start scraping, and status messages to inform users about progress and success.

The scraper is optimized to:

Handle cookie pop-ups on IMDb.

Run in headless mode (without opening the browser window).

Gracefully handle missing fields (e.g., if year, rating, or description is unavailable).

Provide feedback in case of errors.

This tool can be useful for:

Movie enthusiasts wanting quick access to top movies by genre.

Students or researchers collecting data for analysis.

Automation learners exploring Selenium and Tkinter integration.

⚙️ Technologies, Software & Libraries Used

Python 3.x (Programming Language)

Selenium (Web scraping and browser automation)

Geckodriver (Required for running Selenium with Firefox)

Firefox Browser (Target browser for automation)

Tkinter (Built-in Python library for GUI development)

CSV module (For exporting scraped data to CSV)

OS module (For file and path handling)

Time module (For wait/sleep during scraping)

Re (Regular Expressions) (For cleaning and extracting text like movie names and years)

🚀 How It Works

Launch the program. (inside the dist file, we have .exe application)

A window appears asking the user to select a movie genre.

When the user clicks Submit, the scraper opens IMDb in a headless Firefox browser.

The script selects the chosen genre, clicks "See Results," and scrapes the top 30 movies.

Data is saved to a CSV file on the Desktop.

A success message appears once the file is created.

📂 Output Example (CSV Columns)

Name

Genre

Year

Length

Rating

Description
