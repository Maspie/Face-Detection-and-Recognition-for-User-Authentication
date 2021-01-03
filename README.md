# Face-Detection-and-Recognition-for-User-Authentication
How to run-
1. Download all files into one directory.
2. Create a "images" folder in the same directory.
3. Create a person named folder inside images folder for example- Robert Downey jr. named folder.
4. Get a pdf of document id and open the extract-image code and change the file = "Toshal_doc.pdf" with location of your pdf file, change  image.save(open (f"images/Toshal/ to  image.save(open (f"images/Robert Downey Jr./ for example.
5. Run the extract-images code and the photo of the person in document id will be extracted in the images folder.
6. Like in same way do for few document ids  and then run the faces-train code to train the images. (you can add more of your images there sp the recognoition has more confidence value)
7. Run the faces.py code to start came and start recognizing your face. If the recognition isnt working perfectly try adding more of your images in your images folder. 
