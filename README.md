# Module-18-Challange---Blockchain

## PyChain Ledger
Welcome to the PyChain Ledger project! This project is a blockchain-based ledger system that allows partner banks to conduct financial transactions and verify the integrity of the data in the ledger. This project includes a user-friendly web interface built with Streamlit, which allows users to interact with the ledger system easily.

As a developer on this project, I will make the following updates to the provided Python file for this Challenge:

- Create a new data class named Record. This class will serve as the template for the financial transaction records that the blocks of the ledger will store.

- Change the existing Block data class by replacing the generic data attribute with a record attribute that’s of type Record.

- Create additional user input areas in the Streamlit application. These input areas will collect the relevant information for each financial record that you’ll store in the PyChain ledger.

- Test the completed PyChain ledger.

#### Record Class
The Record class is a data class that serves as the template for the financial transaction records that will be stored in the PyChain ledger. This class has the following attributes:

- sender_address: A string that represents the public address of the sender's wallet.
- recipient_address: A string that represents the public address of the recipient's wallet.
- amount: A float that represents the amount of cryptocurrency being transferred in the financial transaction.

#### Block Class
- The Block class is the basic data structure of the PyChain ledger. Each block contains a record attribute of type Record, which stores the financial transaction information.

#### User Input Areas
The Streamlit application includes several user input areas that allow users to input the necessary information for each financial transaction. These input areas include:

- Sender Address: The public address of the sender's wallet.
- Recipient Address: The public address of the recipient's wallet.
- Amount: The amount of cryptocurrency being transferred in the financial transaction.

#### Testing
The completed PyChain ledger can be tested by adding several blocks to the ledger using the Streamlit application. Once multiple blocks have been added, the integrity of the ledger can be verified by checking that the hash of each block matches the previous block's hash.
Run the Streamlit application by executing the following command in your terminal:
- streamlit run pychain.py
- In the Streamlit application, click on the "Add Block" button to add a new block to the PyChain ledger.
- In the input fields provided, enter the following details for the transaction:
- Sender: The name of the person sending the funds.
- Receiver: The name of the person receiving the funds.
- Amount: The amount of funds being transferred.
- Click on the "Add Block" button again to store the transaction in the ledger.
- Repeat steps 4-5 to add more blocks to the PyChain ledger.

#### Functionality
PyChain allows users to add blocks to the blockchain by inputting the sender, receiver, and amount of a transaction. The blockchain is validated using proof-of-work and the difficulty can be adjusted using a slider. The Streamlit application also includes a block inspector that allows users to select a block and view its details.

##### Screenshot
![image](https://user-images.githubusercontent.com/116679505/230906991-51863276-420d-443b-a36a-f6dfa655b877.png)


PyChain Screenshot

#### Validating the Blockchain
To validate the blockchain, simply click the "Validate Chain" button in the Streamlit application. If the blockchain is valid, the application will display "True"
![image](https://user-images.githubusercontent.com/116679505/230907161-ceb6fbe0-923a-4bf6-816f-b3e8147ead2d.png)


#### Conclusion
PyChain is a powerful blockchain-based ledger system that allows partner banks to conduct financial transactions and verify the integrity of the data in the ledger. With its user-friendly web interface built with Streamlit, PyChain is easy to use and accessible to anyone.
