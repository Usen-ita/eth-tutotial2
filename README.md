## learning summary
- I learnt how to interact with the Ganache CL and GUI
- I learnt how to test a smart-contract with truffle and view the transaction locally in the ganache GUI

## testing process
- 1 - compile the contracts
- 2 - instantiate a variable for the contract your want to test
- 3 - type truffle(develop)> 'contract-name.deployed().then((_variable-name) => variable-name = _variable-name);' [this step uses eth]
- 4 - now you can test all functions in 'contract-name'. when text type, truffle(develop)> variable-name.contract-name-function

## emergency safe
- If you get confused - watch this - https://www.youtube.com/watch?v=aRJA1r1Gwu0 