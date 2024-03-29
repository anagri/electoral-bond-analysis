# electoral-bond-analysis

## New Data
- pdfs with URN, Prefix and Bond Number
  - [new-purchaser.pdf](new-purchaser.pdf)
  - [new-receiver.pdf](new-receiver.pdf)
- csv data extracted from above pdfs
  - [new-purchaser.csv](new-purchaser.csv)
  - [new-receiver.csv](new-receiver.csv)
- merged purchaser and receiver data on Preix and Bond Number
  - [merged-purchaser-receiver.csv](merged-purchaser-receiver.csv)
- merged analysis
  - [purchased-not-encashed.csv](purchased-not-encashed.csv) 
    - bonds that have been purchased, not encashment details not available based on Prefix and Bond Number
  - [encashed-not-purchased.csv](encashed-not-purchased.csv)
    - bonds that have been encashed, but purchaser details not available based on Prefix and Bond Number
  - [total-donations-to-party.csv](total-donations-to-party.csv)
    - grouped purchaser, receiver, aggregate by total donations, sorted by donations DESC, purchaser ASC, receiver ASC

## Old Data
The repository contains:
- pdfs made available by Election Commission of India related to Electoral Bond scheme
  - [electoral-bond-data-purchaser.pdf](electoral-bond-data-purchaser.pdf)
  - [electoral-bond-data-receiver.pdf](electoral-bond-data-receiver.pdf)
- Jupyter Python Notebooks to extract the data from pdf
  - [analysis-purchaser.ipynb](analysis-purchaser.ipynb)
  - [analysis-receiver.ipynb](analysis-receiver.ipynb)
- Extracted CSV
  - [electoral-bond-purchase.csv](electoral-bond-purchase.csv)
  - [electoral-bond-receiver.csv](electoral-bond-receiver.csv)

## Environment Setup
- `requirements.txt` - libraries to install to run the extraction

