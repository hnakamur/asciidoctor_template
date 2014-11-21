asciidoctor_template
====================

my template for creating asciidoc documents using asciidoctor-fopub

## setup

```
bundle install --jobs 4 --path vendor/bundle --binstubs vendor/bin
```


## make html

```
bundle exec rake html
```


## make pdf

```
bundle exec rake pdf
```


## file watch mode

```
bundle exec rake watch
```

Whenever you save `*.adoc` file, `*.pdf` file will be generated.


```
bundle exec rake watch TARGET=html
```

Whenever you save `*.adoc` file, `*.html` file will be generated.
