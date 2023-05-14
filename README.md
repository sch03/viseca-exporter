# viseca-exporter

Little helper to get transactions from Viseca One and print them in CSV format.

## Usage

1. Log in to [one.viseca.ch](https://one.viseca.ch) in Chrome.
1. Save the card ID from the path (between `/v1/card/` and `/transactions`) and use it as arg.

1.  ```
    go run viseca-exporter.go -a "$CARDID" > data/export.csv
    ```



