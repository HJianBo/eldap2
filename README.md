# eldap2

Forked from eldap v1.2.2 that contained in **Erlang/OTP 20**

## What different with eldap

- Compiled with erlang.mk
- Always set gen_tcp/ssl to `{active, once}` 

The connection process will be crash, when Socket has closed

## Usage

ref: [Erlang/OTP 20 Doc](http://erlang.org/doc/man/eldap.html)

