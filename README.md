# compile LaTeX

To generate a pdf `main.pdf` from `main.tex` with bibliography references:
```
./compile.latex --file main
```

When compiling, temporary files are generated like `main.log`, `main.nav`, etc...
To remove these files:
```
./compile.latex --clean
```
