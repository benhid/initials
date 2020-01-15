## [initials]()

> This project is based on the -beautifully crafted- **gwern** website. Check out his [blog](https://www.gwern.net/About#implementation-details) to read more about this implementation. 

*Beautiful drop caps to your website*.

Available fonts:

* [goudy initialen](https://tug.org/FontCatalogue/goudyinitialen/)
* [deutsche zierschrift](https://www.dafont.com/deutsche-zierschrif.font)
* [cheshire initials](https://www.dafont.com/cheshire-initials.font)
* [kanzlei initialen](https://www.dafont.com/kanzlei.font)

#### How to

Include the following lines to the `<head>` element:

```
<link rel="stylesheet" type="text/css" href="initials.css">
<style>
    p.initials::first-letter {
        font-family: goudy initialen;
        text-transform: uppercase;
        float: left;
        font-size: 7em;
        line-height: 1;
        margin: 0 0.02em -0.25em 0;
    }
</style>
```

Full example [here](index.html).

#### License

This project is licensed under the terms of the GNU GPLv3 - see the [LICENSE](LICENSE) file for details.