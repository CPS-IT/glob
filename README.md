The Webmozart Glob API Documentation
====================================

This repository contains the API documentation of the [Webmozart Glob] package. 
The documentation is rendered at https://cps-it.github.io/glob/docs/ thanks 
to [GitHub Pages].

Updating the Documentation
--------------------------
Checkout the `gh-pages` branch and run

```bash
composer install
bin/apigen generate vendor/cpsit/glob/src --destination docs
```

Issues
------

Report any bugs or issues you find on the [issue tracker].

License
-------

The documentation is licensed under the [MIT license].

[Webmozart Glob]: https://github.com/CPS-IT/glob
[GitHub Pages]: https://pages.github.com
[issue tracker]: https://github.com/CPS-IT/glob/issues
[MIT license]: LICENSE
