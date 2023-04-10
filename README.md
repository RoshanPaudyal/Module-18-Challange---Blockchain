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
Once you have completed the updates to the PyChain ledger, you can test the system by running the Streamlit application and entering financial transaction information. You can then view the updated ledger to verify that the transaction has been recorded accurately.

#### Functionality
PyChain allows users to add blocks to the blockchain by inputting the sender, receiver, and amount of a transaction. The blockchain is validated using proof-of-work and the difficulty can be adjusted using a slider. The Streamlit application also includes a block inspector that allows users to select a block and view its details.

##### Screenshot
Here is a screenshot of the PyChain Streamlit application:

PyChain Screenshot

#### Validating the Blockchain
To validate the blockchain, simply click the "Validate Chain" button in the Streamlit application. If the blockchain is valid, the application will display "Blockchain is Valid."

Here is a screenshot of the Streamlit application page displaying "Blockchain is Valid":

Validating the Blockchain

#### Conclusion
PyChain is a powerful blockchain-based ledger system that allows partner banks to conduct financial transactions and verify the integrity of the data in the ledger. With its user-friendly web interface built with Streamlit, PyChain is easy to use and accessible to anyone.
