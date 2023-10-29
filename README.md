# Phonetic Alphabet Converter

This Python script is a simple tool for converting words into the NATO phonetic alphabet code. It reads a CSV file containing the NATO phonetic alphabet data and allows the user to enter a word, which is then converted into the corresponding phonetic code words.

## Prerequisites

Before using this script, you will need to have Python and the pandas library installed on your system. You can install pandas using pip:

```shell
pip install pandas
```

## Usage

1. Clone the repository or download the `nato_phonetic_converter.py` script.

2. Make sure you have a CSV file named `nato_phonetic_alphabet.csv` in the same directory as the script. The CSV file should contain two columns: 'letter' and 'code', with each row representing a letter and its corresponding NATO phonetic alphabet code.

3. Run the script by executing the following command in your terminal:

```shell
python nato_phonetic_converter.py
```

4. You will be prompted to enter a word. Type in the word you want to convert to the NATO phonetic alphabet code and press Enter.

5. The script will display the phonetic code words for each letter in the input word.

## Customize the Data

You can customize the data in the `nato_phonetic_alphabet.csv` file to include different alphabets or code words. Make sure the CSV file structure remains consistent with two columns: 'letter' and 'code'.

## Acknowledgments

- This script uses the pandas library for data manipulation.
- NATO phonetic alphabet data source: [Wikipedia](https://en.wikipedia.org/wiki/NATO_phonetic_alphabet)

Please report any issues or contribute to the project by creating a pull request.
