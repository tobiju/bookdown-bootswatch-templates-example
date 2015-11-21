# Bookdown Bootswatch Example

Here you can see how well creating bookdown documentation with beautiful themes work.

# Install

Installation of this library uses composer. For composer documentation, please refer to
[getcomposer.org](http://getcomposer.org/).

run ```php composer.phar install```

# Generate The Book Html


export CSS_BOOTSWATCH=superhero 

run ```export CSS_BOOTSWATCH=superhero && export CSS_PRISM=dark && php vendor/bin/bookdown path/to/book/bookdown.json```

Now you will find the bookdown documentation under the html directory.

# Further Reading

Information about to **change themes** or generate the book via a **docker** container you can find at [bookdown-bootswatch-templates](https://github.com/tobiju/bookdown-bootswatch-templates/blob/master/README.md). 
