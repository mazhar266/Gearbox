# Gearbox, an Async Gearman Example in PHP

An example of running Gearman worker in Async mode in php via socket

## Requirements

- PHP 7 or above
- Gearman job server
- Gearman PECL extension
- Composer
- PHP Ratchet
- PHP WebSocket

## How to run

- Run `composer install` first
- On a window run `php server.php` for opening socket server
- On another window run `php gearman-worker.php` to run the gearman worker
- On another window run `php gearman-client.php` to trigger the jobs

> This Repo is a fork [from the tutorial](https://medium.com/async-php/gearman-in-your-sockets-eefe4f64de2f)
