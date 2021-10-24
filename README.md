# Get domain expiration date

Use the whois command to get the expiration date of the domain.

## Installation

```bash
curl -L https://raw.githubusercontent.com/horatjp/expire-domain/master/expire-domain -o /usr/local/bin/expire-domain
chmod +x /usr/local/bin/expire-domain
```

## Usage

```bash
expire-domain google.com
```

Date Format
```bash
expire-domain -f +%Y/%m/%d google.com
```

Day left
```bash
expire-domain -d google.com
```


## Check

```
# google.com
# google.uk
# google.mx
# google.cz
# google.pl
# google.ru
# google.fr
# google.it
# google.kr
# google.in
# google.cn
# google.com.br
# google.jp
# google.co.jp
```
