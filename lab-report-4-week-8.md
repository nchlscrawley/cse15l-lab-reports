# *Lab Report 4 - Week 8*
**Written by Nicholas Crawley**

## Repositories
* My Repository: [https://github.com/nchlscrawley/markdown-parse](https://github.com/nchlscrawley/markdown-parse)
* *jordan-nishi*'s Repository: [https://github.com/jordan-nishi/markdown-parse](https://github.com/jordan-nishi/markdown-parse)

## Snippet 1
```
`[a link`](url.com)

[another link](`google.com)`

[`cod[e`](google.com)

[`code]`](ucsd.edu)
```
* Output should only produce the second link:
```
[`google.com]
```

## Snippet 2
```
[a [nested link](a.com)](b.com)

[a nested parenthesized url](a.com(()))

[some escaped \[ brackets \]](example.com)
```
* Output should produce the second and third links:
```
[a nested parenthesized url, some escaped [ brackets ]]
```

## Snippet 3
```
[this title text is really long and takes up more than 
one line

and has some line breaks](
    https://www.twitter.com
)

[this title text is really long and takes up more than 
one line](
    https://ucsd-cse15l-w22.github.io/
)


[this link doesn't have a closing parenthesis](github.com

And there's still some more text after that.

[this link doesn't have a closing parenthesis for a while](https://cse.ucsd.edu/



)

And then there's more text
```
* Output should only produce only the second link:
```
https://ucsd-cse15l-w22.github.io/
```
