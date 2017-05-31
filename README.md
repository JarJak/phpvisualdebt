# PHPVisualDebt
Static Analyzer following QDD (Question Driven Development) which
Question Everything what is leaving Visual Debt behind.

![PHP 7.0](https://img.shields.io/badge/PHP-7.0-8C9CB6.svg?style=flat)
[![Build Status](https://travis-ci.org/phpvisualdebt/phpvisualdebt.svg?branch=master)](https://travis-ci.org/phpvisualdebt/phpvisualdebt)
[![Latest Stable Version](https://poser.pugx.org/phpvisualdebt/phpvisualdebt/v/stable)](https://packagist.org/packages/phpvisualdebt/phpvisualdebt)
[![Total Downloads](https://poser.pugx.org/phpvisualdebt/phpvisualdebt/downloads)](https://packagist.org/packages/phpvisualdebt/phpvisualdebt)
[![License](https://poser.pugx.org/phpvisualdebt/phpvisualdebt/license)](https://packagist.org/packages/phpvisualdebt/phpvisualdebt)
[![Coverage Status](https://coveralls.io/repos/github/phpvisualdebt/phpvisualdebt/badge.svg?branch=master)](https://coveralls.io/github/phpvisualdebt/phpvisualdebt?branch=master)

---

## Features

This tool provide static analysis for source code following best QDD practices.

* interface questioner - asks a question for justification of single interface usage
* `final` keyword - asks a question for need of a keyword


## Installation

Install with Composer

```
composer require phpvisualdebt/phpvisualdebt
```

## Usage

Analyzing code:
```bash
bin/phpvisualdebt src/
```

## License

The MIT License (MIT)

Copyright (c) 2017 Michał Brzuchalski <michal.brzuchalski@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.