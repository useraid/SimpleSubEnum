# SimpleSubEnum
Simple wordlist based subdomain enumerator and IP resolver.

## Quick Start

```
./subenum <WORDLIST> <DOMAIN>
```
eg. testing wordlist `subdomain-1000.txt` with domain `google.com`
```
./subenum subdomain-1000.txt google.com
```

Listing out to `stdout` (for pushing into a file)
```
./subenum <WORDLIST> <DOMAIN> --list
```

You can download wordlists from Github or Kali/Parrot repositories <br>
eg. https://github.com/kkrypt0nn/wordlists