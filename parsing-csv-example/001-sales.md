Parsing sales data from a CSV:

```sh
$ sed 1d 001-sales.csv
stripe,2020-09-29 01:10,5900,200,5700,hello@example.com,bsawf
stripe,2020-09-29 05:26,4900,172,4728,zero@cool.com,docker
paypal,2020-08-29 11:17,5900,200,5700,unix@pipes.com,bsawf
```

```sh
$ tail -n +2 001-sales.csv
stripe,2020-09-29 01:10,5900,200,5700,hello@example.com,bsawf
stripe,2020-09-29 05:26,4900,172,4728,zero@cool.com,docker
paypal,2020-08-29 11:17,5900,200,5700,unix@pipes.com,bsawf
```

```sh
$ sed 1d 001-sales.csv | cut -d "," -f 5
5700
4728
5700
```

```sh
$ sed 1d 001-sales.csv | cut -d "," -f 5 | paste -sd+
5700+4728+5700
```

```sh
$ sed 1d 001-sales.csv | cut -d "," -f 5 | paste -sd+ | bc
16128
```

```sh
$ grep ",bsawf$" 001-sales.csv
stripe,2020-09-29 01:10,5900,200,5700,hello@example.com,bsawf
stripe,2020-08-29 11:17,5900,200,5700,unix@pipes.com,bsawf
```

```sh
$ grep ",bsawf$" 001-sales.csv | cut -d "," -f 5 | paste -sd+ | bc
11400
```

```sh
$ grep ",2020-09-" 001-sales.csv | wc -l
2
```

```sh
$ grep ",2020-09-" 001-sales.csv -c
2
```
