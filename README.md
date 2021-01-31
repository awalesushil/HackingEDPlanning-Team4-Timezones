# HackingEDPlanning-Team4-Timezones

## Ghost Teacher Detection

**Algorithm**

Our algorithm is based on the Jaro–Winkler similarity measure to check for spelling errors. Three things are accounted for:

1) Matches - the ith letter in the EMIS name matches the ith letter in the Payroll name.
2) Transposition - The ith letter's location is at least close to its correct location
3) Weight - Matches in the first few letters of the names are given more weight than matches near the end of the name

## Results

[Spreadsheet](https://docs.google.com/spreadsheets/d/1bZB814p4tuV0miguJF7KvIt6YEoWXw7IucIMzhflFkU/edit?usp=sharing)
