# <center> <u>**Extracting Paragraph and Marking various elements such as tables, images, headings, and lists present in  a PDF file**</u> </center> <br/> <br/>

I have writtern a program that is capable of extracting all the paragrph content that is present in a pdf file and also draws bounding rectangles around the paragrphs of the given PDF file and creates a new processed pdf file.

The program is also capable of marking various elements in the pdf file such as Heading, Figures, Tables and list. 

**Procedure to use the code**
1. Run the above code in the google colab. It is preferred to use google colab or any unix based system with a GPU support. This is so becuase I have used layout parser whcih works upon Detectron2 model and it is difficult to install Dectectron2 on a windows system. Google Colab provides free GPU support becuause of which the latency of the output reduces a lot.
2. After running the above script, the program prompts for PDF file. Provide the address of the PDF file which is to be processed.
3. Now, the program prompts for the element to be extracted. If figures, Tables and Lists are selected only a processed PDF file in which the respective element is marked with orange colour will be displayed as output.
4. If either paragraphs or text is selected then two files will be downloaded as output. One is Processed PDF file in which the respective element is marked and the second one is the text file that contains the text that is bounded by rectangles. All the paragraphs or headings will be extracted and stored in the second text file.  

The processed pdf file in which paragraphs are marked will be as follows
![Screenshot (602)](https://user-images.githubusercontent.com/40739974/125208694-b2b18800-e2b1-11eb-9f1c-fd449fc13b59.png)

The extracted text from the paragraphs will be as follows
![Screenshot (603)](https://user-images.githubusercontent.com/40739974/125208711-ce1c9300-e2b1-11eb-8427-07448ddcce82.png)

