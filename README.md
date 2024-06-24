Job Scraping Application
This Flask web application allows users to search for job listings based on job title and location. The application scrapes job data from multiple sources, including Deloitte, Stripe, SonicWall, and Infosys, and displays the aggregated results on a web page.
<br>
Features-<br>
User Input: Users can input a job title and location to search for relevant job listings.<br>
Web Scraping: The application scrapes job listings from various company websites.<br>
Aggregated Results: The results from all sources are combined and displayed on a single results page.<br>
Web Interface: A simple web interface for user interaction and displaying results.<br>
How It Works-<br>
Input Form: The homepage (index.html) contains a form where users enter the job title and location.<br>
Scraping Functions: The backend consists of scraping functions for each company (Deloitte, Stripe, SonicWall, Infosys) that fetch job listings based on the input criteria.<br>
Results Display: The aggregated job listings are rendered on a results page (results.html).<br>
