# Osmosis claim script by 0base.vc

Delegate $osmo to [0base.vc](https://www.mintscan.io/osmosis/validators/osmovaloper1n3mhyp9fvcmuu8l0q8qvjy07x0rql8q4d3kvts).


----

## Requirement

* expect

`apt install expect -y`

## Run

`expect claim.exp  "keyname" "password" "mnemonic" "Votable proposal id"`

## Expected error

|Error          |Description|
|---------------|-----------|
|Timeout        |If timeout occurred have to re-run the application to claim all airdrops.|
|Key Duplication|To delete key `osmosisd keys delete [key name] --keyring-backend file --yes`|





