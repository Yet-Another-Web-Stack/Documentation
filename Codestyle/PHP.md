# PHP Coding Rules
Currently the following PSR-Standarts are meant to be used:

* [[PSR 1: Basic Codestyles]](http://www.php-fig.org/psr/psr-1/)
* [[PSR 2: Detailed Codestyles]](http://www.php-fig.org/psr/psr-2/)
* [[PSR 3: Logging]](http://www.php-fig.org/psr/psr-3/)
* [[PSR 4: Autoloading]](http://www.php-fig.org/psr/psr-4/)
* [[PSR 6: Caching]](http://www.php-fig.org/psr/psr-6/)

Additional the following rules are meant to be followed:
* php may only be used with the long tags (<?php ?>)
* class properties must be in lowerCamelCase
* files may not mix php with none-php content, there are templating engines for that
* properties must not be prefixed with an underscore as a visibility hint
* magic methods besides __construct and __destruct should not be used
* classes must not declare their type(Controller,Abstract,View,etc.) in their name, but in their namespace
* constants and functions should not be used
* configuration should not be handled via constants, but with additional, human-readable files(json or ini)