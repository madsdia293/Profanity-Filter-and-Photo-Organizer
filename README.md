# Profanity Filter and Photo Organizer

This repository contains two Python scripts: a profanity filter and a photo organizer. Each script serves a different purpose and can be used independently.

## Profanity Filter

The profanity filter script (`profanity_filter.py`) checks a text file for rude words and provides a censored version of the file with the detected rude words replaced. It utilizes a predefined list of rude words and scans each line of the specified text file. If a rude word is found, it replaces the word with a bleeped version while preserving punctuation. The script counts the number of rude words found in the file and outputs the results.

### Usage

To use the profanity filter script, follow these steps:

1. Ensure you have Python installed on your system.
2. Download or clone the script file `profanity_filter.py`.
3. Create a text file or specify the path to an existing text file you want to check for rude words.
4. Open a terminal or command prompt and navigate to the directory where the script file is located.
5. Run the script by executing the command: `python profanity_filter.py`.
6. The script will analyze the file, count the number of rude words, and provide the necessary output.

### Dependencies

The profanity filter script has no external dependencies and only requires Python (version 3 or above) to be installed on your system.

### Customization

You can customize the profanity filter by modifying the `rude_words` list in the script. Add or remove words to tailor the list to your specific needs.

### Output

If the file contains no rude words, the script will print the following message:
"Congratulations, your file has no rude words. At least, no rude words I know."

If rude words are found in the file, the script will create a new file named `bleeped_copy.txt` and write the censored version of the file to it. Additionally, it will print the following message:
"Found [rude_count] rude words in your file. See bleeped_copy.txt for a censored copy of your file."

## Photo Organizer

The photo organizer script (`photo_organizer.py`) organizes a directory of photos based on the place mentioned in the photo filenames. It creates separate directories for each unique place and moves the corresponding photos into their respective directories.

### Usage

To use the photo organizer script, follow these steps:

1. Ensure you have Python installed on your system.
2. Download or clone the script file `photo_organizer.py`.
3. Create a directory called `Photos` or specify the path to an existing directory containing the photos you want to organize.
4. Open a terminal or command prompt and navigate to the directory where the script file is located.
5. Run the script by executing the command: `python photo_organizer.py`.
6. The script will organize the photos based on the place mentioned in their filenames.

### Dependencies

The photo organizer script requires Python (version 3 or above) to be installed on your system. There are no additional dependencies.

### Note

Please ensure that you have the necessary permissions to read the photos in the specified directory and write to the directory where the script is located for the photo organizer script to function correctly.

Feel free to provide feedback or contribute to the code.
