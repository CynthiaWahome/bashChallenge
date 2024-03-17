# An Automation for Creating Empty Files

This Bash script automates the creation of empty files with a specific naming convention. It generates files with increasing numbers starting from the last or maximum number that already exists in the directory.

## Usage

1. Make sure you have Bash installed on your system.
2. Clone or download the script `create_files.sh`.
3. Run the script using a Bash interpreter.

## Requirements

- Bash

## Script Details

The script utilizes the `touch` command to create empty files. It dynamically generates file names based on the provided naming convention `<yourName><number>`, `<yourName><number+1>`, `<yourName><number+2>`, and so on.

Each time the script is run, it creates the next batch of 25 files with increasing numbers starting from the last or maximum number that already exists in the directory. It achieves this by automating the process of finding the last file, extracting the number from its name, and incrementing it to generate new file names.

## Testing

After running the script, you can validate that the expected files are created by displaying a long list of the directory and its contents using the `ls -l` command.

## Example

```bash
bash create_files.sh
ls -l

License
This project is licensed under the MIT License - see the LICENSE file for details.
