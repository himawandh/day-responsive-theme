# day-responsive-theme
Responsive Template for Cakephp 4
{
    "name": "day-responsive-theme/day",
    "description": "Day plugin for CakePHP 4",
    "keywords": ["cakephp", "templates", "plugin"],
    "homepage": "https://github.com/day-responsive-theme/day",
    "type": "cakephp-plugin",
    "license": "MIT",
    "authors": [
      {
        "name": "Himawan Djaya Hendra",
        "email": "himawandh@gmail.com",
        "role": "Author"
      }
    ],
    "minimum-stability": "dev",
    "require": {
        "php": ">=7.2",
        "cakephp/cakephp": "~4.2.0"
    },
    "require-dev": {
        "phpunit/phpunit": "^8.5.0"
    },
    "autoload": {
        "psr-4": {
            "Day\\": "src/"
        }
    },
    "autoload-dev": {
        "psr-4": {
            "Day\\Test\\": "tests/",
            "Cake\\Test\\": "vendor/cakephp/cakephp/tests/"
        }
    }
}
