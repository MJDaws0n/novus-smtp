# smtp

Simple SMTP client.

This document is auto-generated from the function signatures in this repository. 
It lists every public function the library exposes.

## Install

```sh
nox pull smtp
```

## Import

```novus
import lib/smtp smtp;
```

## Functions

### `base64_encode`

```novus
fn base64_encode(input: str) -> str;
```
_Defined in: `main.nov`_

### `parse_ip_octet`

```novus
fn parse_ip_octet(ip: str, index: i32) -> i32;
```
_Defined in: `main.nov`_

### `smtp_read_response`

```novus
fn smtp_read_response(fd: i32) -> str;
```
_Defined in: `main.nov`_

### `smtp_response_code`

```novus
fn smtp_response_code(response: str) -> i32;
```
_Defined in: `main.nov`_

### `smtp_send_email`

```novus
fn smtp_send_email(host: str, port: i32, username: str, password: str, from_email: str, to_email: str, subject: str, body: str) -> bool;
```
_Defined in: `main.nov`_

### `smtp_send_line`

```novus
fn smtp_send_line(fd: i32, line: str) -> void;
```
_Defined in: `main.nov`_
