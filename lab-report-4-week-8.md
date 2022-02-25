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

