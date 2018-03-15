# Presentation Template

## System Requirements

### On Ubuntu

```
sudo apt-get install latexmk
sudo apt-get install julia
```

## Usage

* Edit `slides.Rmd`

* `make all` _twice if necessary_

### Columns

~~~ latex
\begincols
\column{0.48\textwidth}

Column 1

\hfill\column{0.48\textwidth}

Column 2

\stopcols
~~~
