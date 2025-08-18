---
level: 1.1
normative: true
references:
        - type: cpp_test
          name: "compliance tests from nativejson-benchmark;strings"
          path: "tests/src/unit-testsuites.cpp"
        - type: cpp_test
          name: "parser class - core;parse;string;escaped"
          path: "TSF/tests/unit-class_parser_core.cpp"
score:
    Jonas-Kirchhoff: 1.0
---

The service parses \\, \\/, \\b,\\f, \\n, \\r, \\t and escaped quotation marks.