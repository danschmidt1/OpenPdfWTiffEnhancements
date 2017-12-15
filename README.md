This is a repository to hold updates that I made to the openPDF Project (https://github.com/LibrePDF/OpenPDF).
The code provided here will allow the OpenPDF project to work with certain, highly corrupted tiffs. 
This project (as of now) cannot be built on its own: what you need to to: take TiFFFaxdecoder.java from this project 
and incorporate it into openPDF, and rebuild openPDF. 
You will have to refactor the package name to fit the openPDF structure, but other than that it should go right in. 
Once this update is incorporated into the general openPDF project, I will delete this.
