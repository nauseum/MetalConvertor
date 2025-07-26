Edit the html to add your own alloys i left some sample data in it to get you started with your own alloys
line 140 at current , 

const csvData = `Item number,Configuration,Product name,Au %,Ag %,Pt %,Pd %;09Y0,C00,9ct Yellow Gold,37.60,8.39,0.00,0.00;10Y0,C00,10ct Yellow Gold,41.70,7.84,0.00,0.00;14Y0,C00,14ct Yellow Gold,58.60,24.13,0.00,0.00;18Y0,C00,18ct Yellow Gold,75.10,12.10,0.00,0.00;22Y0,000,22ct Yellow Gold,91.70,5.50,0.00,0.00;FGC0,000,Fine Gold Casting Alloy,100.00,0.00,0.00,0.00`;


Configuration is your metal code you use (if you need it) in our case 9 yellow is 09Y0,C00, 
Product name is the alloy name  you want to show in the menu 
Au% Ag% Pt% Pd% is the content of each of these precious metals in your alloy 

The alloys will show top to bottom in the menu in the order you create them in this long csvData string 
