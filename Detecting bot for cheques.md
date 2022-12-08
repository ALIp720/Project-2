## Fraud Detection Training Bot<BR>

The objective of this project is to create a fraud detection training bot. 
<BR>
Nowadays, people don't have to go to the bank or go to the ATM to deposit a cheque. All they need to do is take a picture of the cheque and upload it through the mobile banking app or online banking. Sometimes the bank will hold the cheque for a few days until the cheque pass through the positive pay validation. This adds a level of inconvenient to the depositer. Because they have the money in the bank but they can use the money. Sometimes the bank will release the money right away and asked the user to retain the cheque for a long while, in case there's any disputes. Either way, it's not an ideal situation for both the bank and their consumers, including payers and payees. This project is going to provide a solution for this scenarnio. 
<BR>
The first phase of this project is going to train the bot to learn the banks' logo to identify the banks' documents, such as CIBC, BMO and RBC. With OCR technology and Machine learning, the bot is going to be trained on identifing the bank logo. 
<BR>
The second phase of the project is going to train the bot to identify the images of MICR line on the Cheque. Every bank's cheque follows a unique specification. Upon training, the bot shall be able to identify the bank of the checking account. 
<BR>
The third phase of the project is going to identify payer's bank account number. Most of the cheques' MICR lines show the bank account number, which the cheque could be reference and cashed right away. For payers that use Positive pay, retrived bank account number could be used to cross reference check with the positive pay records, upon validation the cheque will be cashed. For some of the payers that use Pseudo numbers will follow the specific bank's formular to retrieve the bank account number and cross reference with the Positive pay records. 
<BR>
When the project completes, we are expecting to have a more efficient and more secure fraud detection feature with this fraud detection training bot. 

<BR>
The steps for phase 1 are as follows:
<BR>
#import data in image files
<BR>
Use Google extension to get capture bank logos and save them in a data file to create a dataset
<BR>
#Convert the images to YOLO format<BR>

#Get YOLO and installed
<BR>
#Update image class: RBC, CIBC, BMO
<BR>
#start training