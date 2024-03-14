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

<img width="1301" alt="Graph" src="https://github.com/WaffIee/Gender-Bias-in-Taylor-swift-songs-/assets/76793719/9943ac4d-e3f9-46af-a50a-2bf0d3d2ba92">

## Usage

Run the Python scripts in the order provided to perform the analysis:

1. CSV merging and cleaning.
2. Gender bias analysis.
3. Review the output file for analysis results.

