# Gender Bias Analysis in Lyrics

This project involves merging multiple CSV files containing song lyrics, cleaning the data, and analyzing the use of gender-specific pronouns to identify potential biases in song lyrics.

## Files

- `Lyrics_dataset.csv`: Merged dataset from individual CSV files.
- `cleaned_lyrics_dataset.csv`: Dataset after cleaning and preprocessing.

## Preprocessing Steps

1. Merge multiple CSV files into a single CSV file.
2. Remove punctuation and convert text to lowercase to standardize the lyrics for analysis.

## Analysis

1. Count the frequency of male, female, and neutral pronouns across different albums.
2. Group by album and sum the occurrences to get totals for each category.
3. Calculate the percentage of each pronoun type out of the total terms.
4. Save the statistics to a CSV file named `album_gender_bias_stats.csv`.

<img width="1508" alt="Screenshot 2024-03-19 at 00 14 36" src="https://github.com/WafaaBajjouk/Gender-Bias-in-Taylor-swift-songs-/assets/76793719/773fcf71-575d-4dc0-a2cd-ffaf4367ff1a">


## Usage

Run the Python scripts in the order provided to perform the analysis:

1. CSV merging and cleaning.
2. Gender bias analysis.
3. Review the output file for analysis results.

