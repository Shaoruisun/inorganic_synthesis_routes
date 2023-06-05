# inorganic_synthesis_routes
This project aims to develop an automated tool for extracting synthesis step information from scientific papers. By leveraging regular expression and information extraction techniques, the tool analyzes the text in research papers to identify descriptions of synthesis steps and extract key synthesis conditions and step sequences.

#Installation

pip install -r requirements.txt

If you encounter missing dependencies while running your code or program, you can use the pip command to install those dependencies. 

#Data Preparation: 

The references for 79 articles are provided in the 'ArticleID.docx' file. You can prepare the PDF full-texts and place them in a folder named 'pdf_79'. Then, run the code in the 'main_code.ipynb' file. Please note that the file 'CPP_true.xlsx' contains manually extracted paragraphs, and 'EntityInformation_true.xlsx' contains manually extracted entities, which are intended for comparison with the results obtained using regular expression extraction.These two files need to be prepared based on the provided article IDs.
