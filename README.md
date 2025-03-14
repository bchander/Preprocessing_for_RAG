In this Approach I converted the pages of the input PDF, that contains Tables of defined size/row, into images so that the LLM can process these images along with extrcted text from the rest pages. 

This can help reduce data/information loss from tables when they are extracted using traditional text extraction process (say using fitz, pymupdf etc.)
The code is written such that the criteria for the tables to be considered/ignoed can be customized as per your need. 
