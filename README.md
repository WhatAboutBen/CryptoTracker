# CryptoTracker
A spreadsheet to monitor and track cryptocurrency investments
This tracker was created to allow me to manage multiple separate portfolios as individual accounts and also see the combined risk in total.		
Set up		
	Change the headings on the "Portfolio Summary" tab, from Fund 1 etc to whatever you choose.	
	This will update all dropdowns and conditional formatting etc.	
		
Transfers		
	If you do not want your "Cost" to change every time you exchange one crypto for another, use the Tfr- and Tfr+ types on the Transactions tab	
	Rules:	
	Always do the Trf- first, then the Trf+ as the Trf+ picks up the average cost of the disposed crypto.	
	Always do 1 to 1 transfers. Don't try one Trf+ and two Trf-, it won't work.	
		
Additional Cryptos		
	Go to Tools -> Script Editor to see the scripts.	
	At the start there is a list of crypto symbols, add your chosen cryptos to the list. (USE EXACT SAME FORMAT AS OTHER LIST ITEMS e.g. Ardor -> 'ARDR', )	
		
Currency		
	To change from GBP to USD or other currency, you need to update the Currency Cell to USD.	
	If you want to use a non-GBP/USD currency. You need to load up the script editor via Tools -> Script Editor.	
	Edit line 18 and replace it with whichever currency you want.	
		
General use		
	Post all transactions in the "Transactions" Tab.	
	Ensure there is a line for each currency held in each fund in the "Summary" tab.	
	The current trigger is set up to update the rates every 15 minutes.	
