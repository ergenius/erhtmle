# erhtmle
Erlang library for URL encoding and escaping HTML entities

## Motivation

The need for erhtmle arose while writing various Erlang web applications. Strangely enogh I discovered that there is no Erlang project dedicated to this subject outhere. The comunity copy and paste various implementations from well known projects like Mochiweb or use complex applications sometimes with the sole purpose of excaping HTML or URL entities.

## Security

This library was build with security in mind. Mature well tested implementations in other programming languages where studied in the process of creating erhtmle as well as all related RFC, including:
- https://www.rfc-editor.org/rfc/rfc1866.html
- https://www.rfc-editor.org/rfc/rfc3986.html

## Features

- Well documented and easy to use.
- Support encoding data used in a query part of a URL.
- Support encoding data according to RFC3986.
- Support converting ALL applicable characters to HTML entities.








