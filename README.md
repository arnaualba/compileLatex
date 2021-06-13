# compile LaTeX

To generate a pdf `main.pdf` from `main.tex` with bibliography references:
```
./compileLatex --file main
```

When compiling, temporary files are generated like `main.log`, `main.nav`, etc...
To remove these files:
```
./compileLatex --clean
```
