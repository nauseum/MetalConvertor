Edit the HTML file in text editor of your choice, I recommend Notepad++, to add your own alloys, I left some sample data in it to get you started with your own alloys, look for ~ line 140

const csvData = `Item number,Configuration,Product name,Au %,Ag %,Pt %,Pd %;09Y0,C00,9ct Yellow Gold,37.60,8.39,0.00,0.00;10Y0,C00,10ct Yellow Gold,41.70,7.84,0.00,0.00;14Y0,C00,14ct Yellow Gold,58.60,24.13,0.00,0.00;18Y0,C00,18ct Yellow Gold,75.10,12.10,0.00,0.00;22Y0,000,22ct Yellow Gold,91.70,5.50,0.00,0.00;FGC0,000,Fine Gold Casting Alloy,100.00,0.00,0.00,0.00`;


**_Configuration_** is your metal code you use in our case 9 yellow is "09Y0,C00", if you don't use a code make something up but it does need both to work.

**_Product name_** is the alloy name  you want to show in the menu ex: "9ct Yellow Gold"

**_Au% Ag% Pt% Pd%_** is the content of each of these precious metals in your alloy 

The alloys will show top to bottom in the drop down menu in the order you create them in this long csvData string 

Built by Google Gemini.

![522518278_2816977608491488_315262941121930570_n](https://github.com/user-attachments/assets/89b300f4-4ac6-4421-8c3b-7e1e86157dc3)
