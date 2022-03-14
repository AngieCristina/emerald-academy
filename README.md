## Chapter 1.0 - Day 1

quest #1
>on my words :) after the bootcamp I'll read this again to see if I was almost right :P 

>The blockchain is data decentralized no mutable that is made by blocks that are extremely secure that cannot be amend , basically used to make transactions without >a third party involved.

>A smart contract is what a developer does in the blockchain through an language as Cadence to give rules to the blockchain determine actions( “if/when...then…” >rules that govern those transactions) that must execute to be certain too all the attendees 

>script   vs   transaccion :

>script is the place where you can view you code and scripts are FREE,  and transcaction is the function the method that is updated in the blockchain.

## Chapter 1.0 - Day 2

What are the 5 Cadence Programming Language Pillars?

1. Safety and Securit
2. Clarity
3. Approachability
4. Developer Experience
5. Resource Oriented Programming

In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?

I think Developer Experience and Safety Security , the first one  because is very important the mental health of the developer, and the second one because with that pillar we could develop a useful and safe smart contract and feel confident with that 

## Chapter 2.0 - Day 1


quest #1

1. Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. Initialize it to "the best" when your contract gets deployed.

![Screen Shot 2022-03-03 at 9 35 41 AM](https://user-images.githubusercontent.com/46632846/156587760-0a0aab85-b6bb-49ed-be78-e8815764a16d.png)

quest #2

2. Check that your variable is actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.

![Screen Shot 2022-03-03 at 9 35 55 AM](https://user-images.githubusercontent.com/46632846/156588047-bc6cadac-0f91-411d-a4ed-03f0004d49d8.png)

## Chapter 2.0 - Day 2

. Explain why we wouldn't call changeGreeting in a script.
> because in flow with candence you can save data in the account and we are going to change that data in the transacion , for that we import our HelloWorld contract > in the transacion template and use AuthAccount

What does the AuthAccount mean in the prepare phase of the transaction?
>we can access the data in our account with the AuthAccount type in the prepare portion of the transaction. The prepare phase: to access the information/data in our >account. 

What is the difference between the prepare phase and the execute phase in the transaction?

>prepare phase: access the data/ information 
>execute phase: can call functions and do stuff to change the data on the blockchain

This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.

. Add two new things inside your contract:

A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber

>![Screen Shot 2022-03-14 at 4 24 17 PM](https://user-images.githubusercontent.com/46632846/158263843-f3629ab5-5281-4543-acae-f5cc67a21f0d.png)

Add a script that reads myNumber from the contract
>![Screen Shot 2022-03-14 at 4 29 33 PM](https://user-images.githubusercontent.com/46632846/158264574-6208a66f-d682-4adc-b28d-4f0f5fbbe05f.png)


Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.
>![Screen Shot 2022-03-14 at 4 42 07 PM](https://user-images.githubusercontent.com/46632846/158266189-37adf1d0-ef76-4147-ae1b-8713e9c310e4.png)


