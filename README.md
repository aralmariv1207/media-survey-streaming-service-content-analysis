# Media Survey: Streaming Service Content Analysis

## About

This project conducts an exploratory deep-dive into a global streaming service catalog. By leveraging Python and the Pandas library, I analyzed thousands of titles to identify content trends, growth patterns, and genre distributions. This research serves as a tool for understanding how a streaming platform curates its library and balances different content types to maintain subscriber engagement.

## Technical Highlights 

· **Catalog Sanitization**: Performed rigorous data cleaning on the `movies_and_shows.csv` dataset, including standardizing column headers and removing redundant entries to ensure a "single source of truth."

· **Metadata Integrity**: Strategically handled missing values in critical metadata fields—such as `director`, `cast`, and `country`—to maintain the accuracy of regional and creator-based analytics.

· **Content Segmentation**: Developed data slices to compare the volume and release trends of **Movies vs. TV Shows**, providing a macro-view of the platform's content strategy.

· **Growth Trend Analysis**: Examined `release_year` and `date_added` features to visualize the evolution of the catalog and identify peak content acquisition periods.

· **Reproducible Pipeline**: Applied core Python principles (functions, loops, and conditional logic) to build a clean, modular analysis script.
