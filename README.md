# The High-Performance High Availability Guide

This is a community documentation project aimed at collecting best practices for optimizing performance in high availability environments.

It's not sufficiently complete at this point to warrant an actual release, and we're still looking for contributions. If you can chip in providing a little insight on, say, tweaking your network, or your I/O subsystem, or your SAN, or your highly available application, we'd love to hear from you.

## Building

This documentation uses [AsciiDoc](http://www.methods.co.nz/asciidoc/), an intuitive text based documentation format that makes contributing easy, and that allows us to process sources into a variety of output formats.

It comes with a complete toolchain including `a2x`, which allows you to create XHTML, PDF, EPUB and other formats from the documentation. To build a PDF, for example, use this command:

    a2x -f pdf hp-ha-guide.txt

## Contributing

Contributions (under [CC-BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/) terms) and comments are very welcome.

For comments, please use [Notes](https://github.com/blog/622-inline-commit-notes).

For contributions, please [fork this repository](http://help.github.com/fork-a-repo/), make and push your changes, and then [issue a pull request](http://help.github.com/send-pull-requests/).
