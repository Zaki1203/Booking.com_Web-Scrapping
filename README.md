# Booking.com_Web-Scrapping

Sure! Here's a rewritten version of your project overview that makes it sound like it's your own creation, while maintaining a professional and polished tone:

---

### 🧾 Project Overview

I developed a web scraping tool that automates the extraction of hotel details from Booking.com. This application collects vital information such as hotel names, prices, locations, ratings, review counts, and direct booking links based on user-specified search criteria (city and date range). The collected data is then saved as a CSV file for easy access and further analysis.

---

### 🎯 Project Goals

* **Automate Hotel Data Collection**: Simplify and speed up the process of gathering hotel information from Booking.com.
* **Flexible Input Options**: Allow users to enter a custom Booking.com search URL and choose their desired output filename.
* **Structured Data Storage**: Export all scraped hotel details into a well-formatted CSV file.
* **Efficient & Ethical Scraping**: Use custom headers and randomized sleep intervals to prevent server overload and mimic natural browsing behavior.
* **Command-Line Friendly**: Ensure the script runs smoothly through terminal input for a hassle-free user experience.

---

### 🔧 Tools & Technologies

* **Python 3.x**
* **BeautifulSoup4** – For parsing and navigating HTML content.
* **Requests** – To send HTTP requests to Booking.com.
* **CSV** – For saving extracted data in a tabular format.
* **LXML** – To boost HTML parsing performance.

---

### 📂 Key Features & Workflow

1. Users input a Booking.com search URL along with a preferred filename.
2. The scraper retrieves and processes the page content.
3. It extracts essential hotel details including:

   * 🏨 **Hotel Name**
   * 💰 **Price**
   * 📍 **Location**
   * ⭐ **Rating**
   * 📝 **Number of Reviews**
   * 🔗 **Booking Link**
4. The extracted data is then saved in a CSV file in the local directory.
5. The script also includes randomized delays between requests to avoid detection and ensure smooth execution.

---

Let me know if you’d like a version for your resume or portfolio as well!
