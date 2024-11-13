# Scraper Project

## Overview

This project is a web scraper designed to scrape data from [pitwall.app](https://pitwall.app). The scraper is controlled via three API endpoints, providing flexibility and control over the scraping process. Additionally, there is an optional bonus task to process a batch in a queue, enhancing the scraper's capabilities.

The purpose of this project is to test coding skills and problem-solving abilities. Developers are encouraged to be creative and adhere to common scraping principles.

## API Endpoints

1. **Start Scraping**
    - **Endpoint**: `/info`
    - **Method**: `GET`
    - **Description**: Scrape general information about the driver performance.

2. **Get Status**
    - **Endpoint**: `/laps`
    - **Method**: `GET`
    - **Description**: Scrape lap information for a specific driver and location per year.

3. **Stop Scraping**
    - **Endpoint**: `/results`
    - **Method**: `GET`
    - **Description**: Scrape season results for a driver.

*Developers can define the specifics of these endpoints based on their design choices.*

## Input and Output Guidelines

- **input.json**: Provides a guideline for the API server functionality and commands. Use it as a reference for expected input formats.
- **output.json**: Serves as a guideline for the expected output from the scraper.

## Hints

- There are multiple approaches to web scraping, which can be done with or without using a browser.
- The scraping endpoints don’t need to operate synchronously with API requests. If execution time is lengthy, consider starting a separate process to prevent request timeouts. Additional endpoints can be set up to retrieve the results once the scraping completes.

## Bonus Task (Optional)

Implement batch processing by integrating a queue system to handle multiple scraping tasks efficiently.

## Scraping Principles

- **Server Traffic**: Implement rate limiting and polite scraping practices to avoid overwhelming the server.
- **Follow Robots.txt**: Respect the website's `robots.txt` directives (if any).
- **Error Handling**: Ensure robust error handling for network issues and unexpected server responses.
- **Ethical Scraping**: Avoid scraping sensitive data and respect user privacy.

## Getting Started

1. **Set Up Environment**: Install necessary dependencies and configure the development environment.
2. **Run API Server**: Start the server to make the API endpoints available.
3. **Use Endpoints**: Interact with the scraper through the provided API endpoints.
4. **Process Batch (Optional)**: Implement the bonus task to handle batch processing using a queue.

## Outcome

You should create a private repository for the project and share access with Finch Technologies. The repository must include a README file detailing the setup instructions and how to interact with the API endpoints. The README should also outline any specific configurations needed to run the scraper, along with instructions for running the optional batch processing task if implemented.

## Purpose

This project aims to showcase coding proficiency and problem-solving skills. Creativity is encouraged to develop an effective and efficient scraper. Don't worry if you can't implement all of the functionality. We will be assessing your coding ability and your approach to problem solving.

---
