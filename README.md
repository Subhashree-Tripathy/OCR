# OCR
We have used easy-ocr to convert pdf to text for Hindi language.
The pdf that we wanted to convert is split in two halves vertically as shown below.

<p align="center">
<img src="./Assets/pdfim.png" height="300px" width ="300px" class="center"/>
</p>


First convert each page of the pdf to image and remove white spaces from the border. After that, we split the image vertically into two equal halves and then apply easy-ocr on it. 

The entire code to the above steps is present in the OCR_hin.ipynb notebook.

After getting the text, we put it into a final document which is present in the output folder as shown below.

<p align="center">
<img src="./Assets/docu.png" height="300px" width ="300px" class="center"/>
</p>


