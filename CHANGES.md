## 0.2.1 (2023-02-15)
* tls.lwt is now tls-lwt

## 0.2.0 (2018-04-08)
* client authentication support
* fix warnings
* require lwt 3.0.0
* Better error message when `--cert` or `--key` files do not exist

## 0.1.3 (2016-03-22)
* tls-0.7.1 compatibility (do not depend on Tls.Printer)

## 0.1.2 (2016-02-11)
* HAProxy protocol support (version 1, via --haproxy1 flag), #22 contributed by @cfcs

## 0.1.1 (2015-07-02)
* log RFC3339 compatible, using UTC
* log exceptions in read_write
* avoid reusing the read/write buffer

## 0.1.0 (2015-05-05)
* Initial public release
