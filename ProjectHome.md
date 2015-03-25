# Bunny the Fuzzer (DEPRECATED) #

**IMPORTANT: This project is superseded by [American Fuzzy Lop](http://code.google.com/p/american-fuzzy-lop/), which performs considerably better and uses a much less complicated approach to instrumenting the fuzzed code. The following content is kept for historical purposes only.**

A closed loop, high-performance, general purpose protocol-blind fuzzer for C programs.

Uses compiler-level integration to seamlessly inject precise and reliable instrumentation hooks into the traced program. These hooks enable the fuzzer to receive real-time feedback on changes to the function call path, call parameters, and return values in response to variations in input data.

This architecture makes it possible to significantly improve the coverage of the testing process without a noticeable performance impact usually associated with other attempts to peek into run-time internals.

Bunny is currently known to support Linux, FreeBSD, OpenBSD, and Cygwin on IA32 and IA64 systems.

## Quick links ##

  * [Download current version](http://bunny-the-fuzzer.googlecode.com/files/bunny-0.93.tgz) (**DEPRECATED**)
  * [See detailed documentation](http://code.google.com/p/bunny-the-fuzzer/wiki/BunnyDoc)