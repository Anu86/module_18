# module_18
Simulate  blockchain ledger to allow partner banks to conduct financial transactions that is, to transfer money between senders and receivers and verify the integrity of the data in the ledger.

1. Created a data class called Record that takes in sender data , reciever data & transaction amount . 
2. The data class Block includs an object of Class Record, Creator_id, previous hash, timestamp & nounce ( number used once) 
3. The blockchain difficulty slider helps adjusts difficulty ( no of zeros th ehash should start with)
4. Nounce is adjusted to change the hash of the block. This is logic is defined as part of proof_of_work .
5. The block is validated by looking into the previous hash value. 

-- Sample logs from the Terminal 
Initializing Chain
Wining Hash 003f7121695a78cc4061dbd5f58af9958c5aa2abfc328838217e5aa6e9566179
Wining Hash 00a067229dd3362303cf383c135de1113b8bd8de35cdec394d0c87a90c287e44
Wining Hash 00df32fe08b149578e6e8499f8b27b6cad02d66852a6d822a7756e137b767fa1
Blockchain is Valid
Blockchain is Valid
Blockchain is Valid
Blockchain is Valid
Blockchain is Valid
Wining Hash 00db1217d0ebd80b74988e56f238c2d49024898762b84c2fa2653b08a648e65b
Wining Hash 005a747e4b707d5fe8e6725db19299e91dd918ad1372e2bc8a75c027e4a4ff2a
Wining Hash 00302bd92a6f1a8943fadea4cf4c2f9debd5dac9da8c601af61cc0d2b4699471
Blockchain is Valid
Blockchain is Valid
Blockchain is Valid
Blockchain is Valid