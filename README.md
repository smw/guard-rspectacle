# Guard::RSpectacle [![Build Status](https://secure.travis-ci.org/netzpirat/guard-rspectacle.png)](http://travis-ci.org/netzpirat/guard-rspectacle)

Guard::RSpectacle automatically tests your application when files are modified.

Tested on MRI Ruby 1.8.7, 1.9.2, REE and the latest versions of JRuby & Rubinius.

If you have any questions please join us on our [Google group](http://groups.google.com/group/guard-dev) or on `#guard`
(irc.freenode.net).

## Prove of concept

**This is an early stage prove of concept. The idea is that Guard starts the Rails environment, reloads changed Ruby files and starts the RSpec runner embedded in the current process.**

## Install

### Guard and Guard::RSpectacle

Please be sure to have [Guard](https://github.com/guard/guard) installed.

Add it to your `Gemfile`, preferably inside the development group:

    gem 'guard-rspectacle', :git => 'git://github.com/netzpirat/guard-rspectacle.git'

Add guard definition to your `Guardfile` by running this command:

    $ guard init rspectacle

## Usage

Please read the [Guard usage documentation](https://github.com/guard/guard#readme).

## License

(The MIT License)

Copyright (c) 2011 Michael Kessler

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

