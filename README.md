# CICD

This project hosts a collection of Powershell Scripts used to 


# Promote Solutions into new Environments

This powershell script simulates moving a collection of solutions from one environment to another. It replicates moving solution from Dev to Test, Test to UAT and UAT to Prod. 

The benifit of doing this via a script(s) is the process is repeatable and therefore predictable.

This solution is broken down into two scripts. 

First script Export solution from Dataverse, Unpacks the Solutions, Then commits the solutions into GIT in a new branch and creates a GIT pull request for said branch. 

The second script pulls the latest unpacked solutions from GIT, packs the solution using the Microsoft Solution Packager tool and then imports the solution into the targert environment. 

## Export Script
TBC

### Parameters

### Exports Solutions
TBC

### Unpack Solutions
TBC

### Commit Solution to GIT
TBC

### Pull Solution From GIT
TBC

## Import Script
### Pack Solution
TBC

### Import Solution
TBC
