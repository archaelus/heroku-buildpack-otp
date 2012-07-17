Heroku buildpack: OTP
=======================

This buildpack compiles Erlang/OTP from source and produces a slug containing an uninstalled otp/ directory. Once extracted, this image can be used by running `<extract>/Install -minimal </absolute/path/to/extract>`. The image can then be used with a regular heroku-buildpack-erlang.

Usage
-----

Example usage:

    $ heroku build git://github.com/erlang/otp.git -b git://github.com/archaelus/heroku-buildpack-otp.git
