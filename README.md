# minimal-safe-bash-template

My Minimal Safe Bash Script Template.

## Usage examples

```
$ ./template-v1.sh -f
flag option set
$ ./template-v1.sh -f -a 535
flag option set
Using -a option -> arg: [535]
$ ./template-v1.sh -f -a "Hello World"
flag option set
Using -a option -> arg: [Hello World]
$ ./template-v1.sh -f -a "Hello World" --abc pi
flag option set
Using --abc option -> arg: [pi]
Using -a option -> arg: [Hello World]
$ ./template-v1.sh -f -a "Hello World" --abc=3.141592
flag option set
Using --abc option -> arg: [3.141592]
Using -a option -> arg: [Hello World]
$ ./template-v1.sh --abc "hello, reader"
Using --abc option -> arg: [hello, reader]
$ ./template-v1.sh --abc "hello, reader" -f
flag option set
Using --abc option -> arg: [hello, reader]
$ ./template-v1.sh --abc "hello, reader" -f -a23
flag option set
Using --abc option -> arg: [hello, reader]
Using -a option -> arg: [23]
$ ./template-v1.sh -a52 -f
flag option set
Using -a option -> arg: [52]

```

## Donation / Sponsorship ❤️ 👍

This code was brought to you by [Leo Gutiérrez](https://github.com/leogtzr) in his free time. If you want to thank me and support the development of this project, please make a small donation on [PayPal](https://www.paypal.me/leogtzr). In case you also like my other open source contributions and articles, please consider motivating me by becoming a sponsor/patron on [Patreon](https://www.patreon.com/leogtzr). Thank you! ❤️
