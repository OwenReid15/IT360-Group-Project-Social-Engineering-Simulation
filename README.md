# IT360-Group-Project

*Add a project Description*

Project Overview:
This project is a digital forensics automation tool built using a Bash script.The tool combines three diffrent tools Hashdeep, Bulk Extractor, and ExifToolo quickly. This tool will be able to analyze large datasets, disk images, and evidence files.Its purpose is to speed up forensic analysis, reduce human error, and provide repeatable, consistent results.

Features:
File Hashing (Hashdeep):
Creates hashes of the input file to support integrity checking.
Artifact Extraction (Bulk Extractor):
Automatically extracts emails, URLs, credit card patterns, and other digital artifacts.
Metadata Collection (ExifTool):
Pulls metadata from the file and from extracted content form bulk extractor.
Automated Workflow:
Combines all three tools into a single script, reducing manual steps.
Output Folder Creation:
Creates an output directory containing all results for easy review.

Set up instuctions:
1. Make sure all required tools are installed on Kali Linux.
2. Run the command: sudo apt install bulk-extractor hashdeep exiftool
3. Create a folder where you want to store your script and files.
4. Download or place your bash script into that folder.
5. Download any dataset or evidence file you want to test the script on (make sure to put the data set in that folder).
6. Run the script by typing: bash ./scriptname.sh
7. When the tool asks for an input file, type the name of the file you want to analyze.
