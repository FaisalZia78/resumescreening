This script extracts text from a resume PDF file and analyzes it to assess the candidate's skills in various areas related to industrial engineering. It performs the following tasks:

Text Extraction: Utilizes PyPDF2 and textract libraries to extract text from the PDF file.

Text Preprocessing:

Converts all text to lowercase.
Removes numerical digits.
Removes punctuation marks.
Skill Assessment:

Defines key terms for different areas of industrial engineering, such as Quality/Six Sigma, Operations Management, Supply Chain, Project Management, Data Analytics, and Healthcare.
Counts the occurrence of these terms in the extracted text to assess the candidate's expertise in each area.
Visualization:

Creates a pie chart to visualize the candidate's skills in different industrial engineering areas.
Saves the pie chart as a .png file for further reference.
The pie chart provides a quick overview of the candidate's strengths in various industrial engineering domains, aiding in resume screening and candidate evaluation processes.
