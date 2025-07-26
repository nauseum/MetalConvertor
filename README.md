Download the release 
Edit this line to add your own alloys, sample data doe yellow golds left in the release to explain how it works. 

const csvData = `Item number,Configuration,Product name,Au %,Ag %,Pt %,Pd %;9ct Yellow Gold,37.60,8.39,0.00,0.00;14ct Yellow Gold,58.60,24.13,0.00,0.00;18ct Yellow Gold,75.10,12.10,0.00,0.00;22Y0,000,22ct Yellow Gold,91.70,5.50,0.00,0.00;FGC0,000,Fine Gold Casting Alloy,100.00,0.00,0.00,0.00`;

Configuration == Your internal nomenclature for your alloys ie: 9 Yellow for us is 09Y0,C00.
Product name == The Alloy name you want in the UX
Au %,Ag %,Pt %,Pd % == the relevant fine metal %% content of your alloy in that order 
