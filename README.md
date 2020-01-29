# budgy-cli
CLI for Budgy 

## Usage 
In order to use budgy cli you need to first login 
```
budgy login --user <username> --password <password>
```

## Examples
```
budgy add-income dx90 --amount 350 --envelope eli
budgy add-expense fuel --amount 120 --envelope auto
budgy move --from auto --to groceries --amount 31
budgy show-envelope eli
date | name | amount | user
-----|------|--------|-----
asd  | xxx  | 101    | es
```


### Add transaction
To add a new transaction you should provide the following details: 
* Name
* type (deposit/redraw)
* amount
```
budgy transact --redraw --amount 12.5 <name>
```

