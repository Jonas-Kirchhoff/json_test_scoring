---
level: 1.1
normative: true
references:
        - type: cpp_test
          name: "regression tests 1;issue #186 miloyip/nativejson-benchmark: floating-point parsing"
          path: "tests/src/unit-regression1.cpp"
score:
    Jonas-Kirchhoff: 1.0
---

The service parses numbers within the 64-bit double range but outside of the double precision without throwing an exception.