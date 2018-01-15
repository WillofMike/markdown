# Node CLI Tool: CSV to JSON Converter

### This Project is designed to Convert CSV (Comma Separated Values) into a JSON (Javascript Object Notation)file.  

1. Fork and clone this project

2. Now npm install for all the of the dependencies.

3. You will want to be specific with the path of the file your looking to convert from.
- Example: The CSV file I'm wanting to convert is /Users/macbook/downloads/csv/testFile.csv
    - You want to be specific with the path otherwise you will get an error
### What not do do (be specific)
- ![alt text](https://github.com/WillofMike/markdown/blob/master/images/Screen%20Shot%202018-01-15%20at%2010.51.30%20AM.png "What not to do!")

- You will also want to make sure that your specific with the file that is be written in the conversion.  
### The ideal way (notice the full paths of the file)
- ![alt text](https://github.com/WillofMike/markdown/blob/master/images/Screen%20Shot%202018-01-15%20at%2010.51.30%20AM.png "The ideal way")

Run the script:
```
$ node csv-to-json.js <yourfile.csv> <filetowrite.json>
```
