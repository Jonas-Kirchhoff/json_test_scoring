---
level: 1.1
normative: true
references:
        - type: cpp_test
          name: "accept;UTF-8;unexpected BOM"
          path: "TSF/tests/unit-byte_order_mark.cpp"
score:
    Jonas-Kirchhoff: 1.0
---

The service does not accept UTF-8 byte order mark outside of a string and outside of the first three characters of the input.