# Wikidef - One-line Wikipedia summary fetcher

A dead-simple bash script that fetches the first meaningful paragraph from a Wikipedia article and shows it in the terminal.

## Features

- Takes any word/phrase as argument
- Fetches the lead section of the corresponding Wikipedia page
- Shows only the first long enough paragraph (≥ 60 characters)
- Clean output with colors
- Shows direct link to the full Wikipedia article
- Graceful error handling for non-existing pages

## Usage

```bash
./wikidef quantum
# or
./wikidef "Black_hole"
# or
./wikidef photosynthesis
