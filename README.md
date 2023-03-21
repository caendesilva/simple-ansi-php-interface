# simple-ansi-php-interface
A simple PHP interface providing convenient access to ANSI colours

## Installation

Since this "package" is so simple, it's intended that you simply copy the interface file to your setup. You can do that by copying the included `ANSI.php` file, which is also available as a [Gist](https://gist.github.com/caendesilva/8e3873be292dc7be2ba20b973317fab6), and possibly updating the namespace to suit your needs.

You can also simply copy the code below:

```php
interface ANSI {
    const BLACK = "\033[30m";
    const RED = "\033[31m";
    const GREEN = "\033[32m";
    const YELLOW = "\033[33m";
    const BLUE = "\033[34m";
    const MAGENTA = "\033[35m";
    const CYAN = "\033[36m";
    const WHITE = "\033[37m";
    const RESET = "\033[0m";
}
```

## Usage

The interface provides constants for the ANSI colour codes. You can use them like this:

```php
echo ANSI::RED . 'This is red' . ANSI::RESET;
```

## Screenshot

![image](https://user-images.githubusercontent.com/95144705/226581249-0ba8b5e0-bb92-4d49-99c1-f20e51642a1c.png)


## License

This package is licensed under the MIT license. See the [LICENSE](LICENSE.md) file for more information.
