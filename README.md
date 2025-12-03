# IT360-Group-Project

Link to Video: [](https://youtu.be/u1itF6jbqog)

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
3. Run the command: nano 'filename'.sh
4. Copy and paste the script into this file and save it.
5. Run the command: chmod +x 'filename'.sh //to amke it executable
8. Download any dataset or evidence file you want to test the script on (make sure to put the data set in that folder).
9. Run the command: ./'filename'.sh //to run the script
10. When the tool asks for an input file path, type the name of the file path you want to analyze.
