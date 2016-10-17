# Program # X
Name:  
Cosc 5730

Description:  (how to run the program, phone/emulator screen size, android version ie 7.0)

Run App phone-nexus 5x api 24 1080*1920;420dpi android version-6.0

Anything that doesn't work:




# Grade

* Transactions: 20/30
  * Add: Not working. The transaction is not listed after adding it. -5
  * Delete: Working.
  * Update: Not working, also, see problems below. -5
  * Query: Working.
* Categories: 0/20
  * Add: No way to know if it is working as categories are not listed anywhere, and are not validated. -5
  * Delete: No way to know if it is working as categories are not listed anywhere, and are not validated. -5
  * Update: No way to know if it is working as categories are not listed anywhere. -5
  * Query: Not working, there is no spinner nor list of categories. -5
* Other problems: -5
* **Total: 15/50**

# Problems: -5

1. When adding/updating a transaction, there is no validation about the existance of the category.
1. Editing the transaction is cumbersome, the user may not want to change every field of the transaction. Also, the user needs to remember the ID of the transaction they want to edit.
1. Updating a transaction makes it disappear from the list of transactions. Follow these exact steps: Load the sample data with the provider, go to the "Update transactions" and select "Savings", write an "a" in fileds 1,2,3,5, and a 1 in field 4. Write the id of the transaction to be edited and click Update. Now go to the main screen and display the transactions from savings. The transaction now must be gone.
1. Adding a transaction requires the user to input the id of the category, isntead of its name. Even better will be to have a Spinner.
1. Transfering money doesn't seem to be working, I don't see a transaction in either account.
