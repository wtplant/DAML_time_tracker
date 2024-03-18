#### This is a DAML app:
DAML is smart contract language for multi party applications. DAML contracts/apps can be deployed to interact with centralized databases as well as select blockchain networks.
DAML syntax is based on and is similar to the Haskell programing language. DAML differes from Solidity smart contracts in many ways, you can read more about how they stack up [here](https://blog.logrocket.com/daml-vs-solidity-choose-smart-contract-language/)

You can access the DAML docs at https://docs.daml.com/. 
Additoinally a good resource for updated information about the platform can befound on their forum [here](https://discuss.daml.com/)

# Time Tracker Application

### This is a time tracker application that makes it possible for a user to track time they have spent on various tasks.
 The daml template can be found in `Timetracker.daml` file in the `daml` directory. 

- [x] This Daml model implements:
    - [x] creation,
    - [x] update and
    - [x] deletion of the representation of time spent.

Additionally the following data types have been provided: Description, Start (date)time, End (date)time, A project identifier to allow higher level organization.

In the same `Timetracker.daml` file you will find the following script:
- [x] A Daml script that can be used to initialize the ledger with at least one user and a few sample records.
- [x] A Daml script that does some testing of the templates.

Finally, using `daml start` from the root of the `timetracker` directory we can start an 'in-memory instance of Canton with a single domain and a single participant` achieving the following objective:
- [x] A minimal Canton ledger (1 participant node, 1 domain node, single config file) that when opening the Navigator shows how the template can be used.
Configuration for Canton ledger can be found in the daml.yaml file as follows:
```
ledger:
    host: localhost
    port: 6865
```

From the Navigator UI you can create, update, and archive contracts from the Timetracker template. 





   

           
         
      








