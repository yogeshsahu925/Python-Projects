# Story Word Replacement Script

This Python script allows users to dynamically replace placeholders in a story file with custom input. Placeholders in the story are denoted by angle brackets (`<placeholder>`).

## How It Works

1. The script reads a text file named `story.txt`.
2. It identifies placeholders within the story, defined as text enclosed in `<` and `>`.
3. Users are prompted to provide a replacement for each placeholder.
4. The script replaces the placeholders with the user-provided words and prints the updated story.

## Example

### Input File (`story.txt`)
```text
Once upon a time, there was a <character> who loved <activity>. One day, <character> decided to <action>.
