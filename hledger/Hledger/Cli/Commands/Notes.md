## notes

List the unique notes that appear in transactions.

_FLAGS

This command lists the unique notes that appear in transactions,
in alphabetic order.
You can add a query to select a subset of transactions.
The note is the part of the transaction description after a | character
(or if there is no |, the whole description).

Example:
```shell
$ hledger notes
Petrol
Snacks
```
