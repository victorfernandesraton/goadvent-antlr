# goadvent-antlr

Examples from my goadvent blog post

```shell
wget http://www.antlr.org/download/antlr-4.7-complete.jar
alias antlr='java -jar antlr-4.7-complete.jar'

antlr -Dlanguage=Go -o parser Calc.g4
```

FOr dowload all libs use
```shell
go get -u
```

## CAUTION

This project need use go module concepts 