The Movie Genre Scraper is a Python-based desktop automation tool that simplifies the process of collecting movie data from IMDb. With a clean and interactive Tkinter GUI, users can select a movie genre from the interface, and the tool will automatically scrape the top 30 movies in that category using Selenium WebDriver with Firefox (GeckoDriver).

The program gathers important details for each title, including the movie name, genre, release year, runtime, IMDb rating, and a brief description. Once collected, this information is exported into a structured CSV file saved directly on the user’s Desktop, making it easy to access, analyze, or share without requiring technical skills.

The tool is designed to combine the power of web automation with an easy-to-use graphical interface. Instead of manually browsing IMDb, users simply select a genre and click a button. Behind the scenes, the scraper navigates IMDb, handles popups, scrolls to the correct elements, and extracts the required information. This approach saves time and ensures accurate, consistent data.

Another strength of the project is its support for creating a standalone executable (.exe) using PyInstaller. This allows the scraper to run on any Windows system without requiring a Python installation. The executable includes all dependencies, along with GeckoDriver, so users can simply download and run the program.

The project highlights the practical use of Python for automation, GUI development, and data extraction. It is particularly useful for students, researchers, and movie enthusiasts who want to analyze IMDb data across genres. Since the results are exported to CSV, they can be further examined in Excel, Python, or visualization tools to uncover trends and insights.

In summary, the Movie Genre Scraper transforms a tedious manual process into a streamlined, one-click solution, demonstrating how Python can bring together automation and usability in a practical, real-world project.
