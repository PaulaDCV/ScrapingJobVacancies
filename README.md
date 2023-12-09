# Scraping_Job_Vacancies
Project scraping different sites to obtain a variety of job vacancies
## Running the script


To run the script the following parameters are needed:

- Position(List of strings): List including one or more positions to search for.
  
- Location(String): Location of the job listings to be searched.
  
- CSV(String, Default = "Search Result"): The name for the CSV file.
  
<u>E.g:</u>
Run a cell with:

**main(["data analysis", "software development"], "London",)**

    Returns job postings for <u>data analysis</u> and<u> software development</u> in <u>London</u>. A CSV     file named "SearchResults.csv" is generated.

**main(["Healthcare"] "Brighton","Search1)"**

     Returns job postings for <u>healthcare</u> positions in Brighton. A CSV file named     "Search1.csv" is generated.

## Output

Once all the data is processed, the data is saved as a CSV file containing the following columns:

- Title: Name of the job
  
- Href: Url for the job posting
  
- Location: Job Location
  
- Company: Company posting the Job

- Site: The site where the job was found. (Currently will always be Indeed)
  
- Position Search: The position parameter used when the job was found
  
- Location Search: The location parameter used when the job was found
