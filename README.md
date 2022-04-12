# A Ferret scripts

> A collection of web scrapping scripts written in Ferret's domain scripting language FQL

## Scripts

- Hackernews
- Soundcloud
- Github
- Google
- Amazon
- Instagram

## Usage

Install [Ferret](https://www.montferret.dev/docs/installation/) and install the `jq` command for pretty-printing the JSON output from Ferret. Then after cloning this repo, run the example command below:

```bash
ferret exec -l debug --param user:\"account_name\" --param pass:\"12345678\" --param profiles:[\"account_name1\",\"account_name2\"] 8_instagram.fql | jq
```

## Disclaimer

I don't take any responsibility for any actions made from running these scripts.
