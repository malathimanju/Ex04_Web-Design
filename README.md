# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
</head>
<body>
<p style="font-size:30px"><b>Agricultural  Search</b></p>
<h1>wheat</h1>
<a href="https://en.wikipedia.org/wiki/Rice_production_in_India#:~:text=Rice%20is%20the%20basic%20food,a%20kharif%20crop%20in%20India.">
<img style="border:5px solid black;"src="c:\html\wheat.jpeg"width="100" height="100"><br></a>
<br>
<h1>paddy</h1>
<a href="https://farmer.gov.in/m_cropstaticswheat.aspx">
<img style="border:5px solid black;" src="c:\html\paddy.jpeg"width="100" height="100"><br></a>
<br>
<h1>tiller</h1>
<a href="https://www.zzhuayo.com/product/mini-plough/">
    <img style="border:5px solid black;" src="c:\html\tiller.jpeg"width="100" height="100"><br></a>
<br>
<h1>tractor</h1>
  <a href="https://www.zzhuayo.com/product/mini-plough/">
    <img style="border:5px solid black;" src="c:\html\tractor.jpeg"width="100" height="100"><br></a>
<br>
<h1>fertilizer</h1>
<a href="https://en.wikipedia.org/wiki/Fertilizer">
    <img style="border:5px solid black;" src="c:\html\ferti.jpeg"width="100" height="100"><br></a>a
</a>       
</body>
</html>
```


## OUTPUT
![Screenshot 2024-04-25 100716](https://github.com/malathimanju/Ex04_Web-Design/assets/165985843/9ecfb3de-4959-4dd5-a435-608452810388)
![Screenshot 2024-04-25 100741](https://github.com/malathimanju/Ex04_Web-Design/assets/165985843/0898fe3c-acd7-4176-ad7b-c8c53a2aa1d3)
![Screenshot 2024-04-25 100820](https://github.com/malathimanju/Ex04_Web-Design/assets/165985843/8c414184-f704-42d1-8031-f4e26caaf551)




## RESULT
 Images as hyperlinks is implemented successfully.
