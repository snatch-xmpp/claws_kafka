

# Claws Kafka #

Copyright (c) 2017-2018 Manuel Rubio

__Authors:__ "Manuel Rubio" ([`manuel@altenwald.com`](mailto:manuel@altenwald.com)).

[![Build Status](https://img.shields.io/travis/snatch-xmpp/claws_kafka/master.svg)](https://travis-ci.org/snatch-xmpp/claws_kafka)
[![Codecov](https://img.shields.io/codecov/c/github/snatch-xmpp/claws_kafka.svg)](https://codecov.io/gh/snatch-xmpp/claws_kafka)
[![License: Apache 2.0](https://img.shields.io/github/license/snatch-xmpp/claws_kafka.svg)](https://raw.githubusercontent.com/snatch-xmpp/claws_kafka/master/LICENSE)
[![Hex](https://img.shields.io/hexpm/v/claws_kafka.svg)](https://hex.pm/packages/claws_kafka)

Claws Kafka is an extension for [snatch](https://github.com/snatch-xmpp/snatch) to provide to the system of a way consume/publish events from/to [Apache Kafka](https://kafka.apache.org/).

Installation
------------

The system requires OTP 19+ and we prefer to use [rebar3](http://www.rebar3.org) instead of older versions. To install claws_kafka only needs:

```erlang
{deps, [
    {claws_kafka, "0.2.0"}
]}
```

Or if you are using [erlang.mk](https://erlang.mk) instead, you can use:

```Makefile
DEPS += claws_kafka
dep_snatch = hex 0.2.0
```

You'll need a C/C++ compiler installed in your system for [fast_xml](https://github.com/processone/fast_xml) and [stringprep](https://github.com/processone/stringprep).

For further information [check this doc](doc/how-to/claws_kafka.md).

Troubleshooting
---------------

Feel free to create an issue in github to point a bug, flaw or improvement and even send a pull request with a specific change. Read the [LICENSE](LICENSE) if you have doubts about what you can do with the code.

Enjoy!


## Modules ##


<table width="100%" border="0" summary="list of modules">
<tr><td><a href="claws_kafka.md" class="module">claws_kafka</a></td></tr></table>

