# HtmlFundMe

A minimalistic example - [metamask docs](https://docs.metamask.io/guide/create-dapp.html#basic-action-part-1).

# Requirements

-   [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
-   [Metamask](https://metamask.io/)
-   [Nodejs](https://nodejs.org/en/)
-   [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/) instead of `npm`

# Quickstart

1. Clone the repo

```
git clone https://github.com/akshtsng/HtmlFundMe
cd HtmlFundMe
```

2. Run the file.

Optionally:

If running with prettier formatting, or don't have a way to run file in the browser, run:

```
yarn
yarn http-server
```

A small button can be see that says "connect", metamask will pop on clicking it.

# Execute a transaction

To execute a transaction follow this:

Make sure to have the following installed:

1. Need to open up a second terminal and run:

```
git clone https://github.com/akshtsng/HardhatFundMe
cd HardhatFundMe
yarn
yarn hardhat node
```

This will deploy a sample contract and start a local hardhat blockchain.

2. Update `constants.js` with the new contract address.

In `constants.js` file, update the variable `contractAddress` with the address of the deployed "FundMe" contract. It can be seen near the top of the hardhat output.

3. Connect [metamask](https://metamask.io/) to local hardhat blockchain.

In the output of the above command, take one of the private key accounts and [import it into metamask.](https://metamask.zendesk.com/hc/en-us/articles/360015489331-How-to-import-an-Account)

Additionally, add localhost with chainid 31337 to metamask.

5. Reserve the front end with `yarn http-server`, input an amount in the text box, and hit `fund` button after connecting

# Thank you!

[![Akshat Singh Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshtsng/)
