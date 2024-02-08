# Time Tracker Application

### Develop a time tracker application that makes it possible for a user to track time they have spent on various tasks.
 I have created the following app within this folder. The damel template can be found in `Timetracker.daml` file in the `daml` directory. 
 The template/model meets the following requirements:
#### Minimal solution
- [x] Daml model that implements:
    - [x] creation,
    - [x] update and
    - [x] deletion of the representation of time spent.*(Note: The template provides for the ability to archive/delete tasks)*

Additionally the following data types have been provided:
- [x] Required data to be stored:
    - [x] Description
    - [x] Start (date)time
    - [x] End (date)time
    - [x] A project identifier to allow higher level organization.
    *(Note: for practical purposes, `text` has been used to represent time values)*

In the same `Timetracker.daml` file you will find the following script:
- [x] A Daml script that can be used to initialize the ledger with at least one user and a few sample records.
- [x] A Daml script that does some testing of the templates.

Finally, using `daml start` from the root of the `timetracker` directory we can start an 'in-memory instance of Canton with a single domain and a single participant` achieving the following objective:
- [x] To showcase, start a minimal Canton ledger (1 participant node, 1 domain node, single config file) and use the Navigator to show how the template can be used.
Configuration for Canton ledger can be found in the daml.yaml file as follows:
```
ledger:
    host: localhost
    port: 6865
```

From the Navigator UI you can create, update, and archive contracts from the Timetracker template. 





   

           
         
      








