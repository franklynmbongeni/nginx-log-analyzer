#nginx log analyzer

## Description
 This project is a simple shell script to analyze nginx access logs. It extracts and summarizes useful information such as:

    Top 5 IP addresses with the most requests

    Top 5 most requested paths

    Top 5 response status codes

    Top 5 user agents

    ## It’s a lightweight tool to practice shell scripting and command-line text processing using awk, sort, uniq, head, and sed.
## Requirements
    - Bash Shell
    - A log(or .txt) file in a standard nginx format (a sample is already provided) if you want to use your own file your can change the (LOGFILE="nginxsample.txt") 
      in the second line to the name of your file

    ## Run it with   BASH MAIN.SH
