Branch erc20 TODO list:

Logic:
- [ ] Withdraw: Send list of tokens to withdraw, like this the user can pay the price
  of doing only the necessary bet withdraws.

Front
- [ ] Figure what exactly to do with Token decimals (how to compute the right number to send)
- [ ] Withdraw: compute withdraw value according to the selected currency
- [ ] Activate "loading bar" already when Approval request is sent

Bugs
- [ ] When creating a bet: Uncaught (in promise) Error: Invalid number of arguments to Solidity function
- [X] Category icon not showing
- [ ] When Approval doesn't work, the promise resolves anyway and the current JS code thinks it's time to send the real Bet transaction. This should be fixed.