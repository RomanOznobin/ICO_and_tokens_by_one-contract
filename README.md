# ICO_and_tokens_by_one_smart_contract
That example of contract with ICO, tokens and accrual of dividends in ONE smart contract

Most of ICO try to separate contracts of ICO, Token with Dividends calculation and Closed Wallet.
( Closed Wallet is use for money rezervation until ICO will not finish and get softcap level )
That is folow from ER20 contract library - OpenZepelin.
But that is not necessary, for simple token contract. And do it by a one contract will be cheaper for contract load.

So I am introduce an example of full ER20 standart token contract by one contract.
It was implemented for Basis Token ICO.

That contract has time period for PreSale, PreICO Break and ICO. 
The money from tokens sale are closed till softcap level are not reached.
Have softcap and hardcap.
Tokens are mint only when they has been purchased. So you do not need to burn them.
Beneficiar can take money from contract after softcap has reached.
Benificiar can make cast of investor and then calculate dividends.
After that investors can take them dividends from contract wallet.
