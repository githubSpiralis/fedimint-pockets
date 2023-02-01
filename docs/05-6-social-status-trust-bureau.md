# Social Status/Trust Bureau

**Objective/Context:** Andrea is a girl who is in the final phase of her university studies. In order to conclude she needs to pay, among other documentation, her title. For this, Andrea needs to ask the Community Savings and Credit Cooperative, a society belonging to the community where she lives, for an economic loan, which is given based on the social status of the person who needs it.

In order for a loan to be granted, the Community Savings and Credit Cooperative holds a vote, where each member casts their vote on whether or not Andrea should be granted the loan.

Aspects such as education, income, occupation, property ownership and participation in social and cultural activities are taken into account when granting the loan.

This same protocol is applied by the community when voting on issues such as jobs, contract allocation, position appointments, etc.

**Federation Composition** - Community Members + Internal Storage Provider

Emma and Judith are members of the Federation and play the role of Guardians. They also will lend their phones to storage the voting system data in an encrypted form.

![social-custody-diagram](./assets/will-schema-diagram.png)

##### Solution

Each member of the Community Savings and Credit Cooperative will mint their vote into the Federation using an Internal Storage Provider with a contract that specifies:

- Members of the Community Savings and Credit Cooperative will mint their vote through their "My FM Wallet".
- Every vote must be stored in an anonymous, secure and encrypted form using an Internal Storage Provider Schema.
- When results are ready and the % of Guardian's keys required is complete, each member of the Community Savings and Credit Cooperative as well as Andrea, will be able to see the verdict by redeeming their pockets.

###### Continue with [Technology Diagram](./06-technology-diagram.md)

###### Got to [Menu](../README.md)
