# ExcIEEEST5B
type: "object"
description : >
## Description
The class represents IEEE Std 421.5-2005 type ST5B model. The Type ST5B excitation system is a variation of the Type ST1A model, with alternative overexcitation and underexcitation inputs and additional limits.  Reference: IEEE Standard 421.5-2005 Section 7.5.   Note: the block diagram in the IEEE 421.5 standard has input signal Vc and does not indicate the summation point with Vref. The implementation of the ExcIEEEST5B shall consider summation point with Vref.

## Data Model
  - properties:
    - kr:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Regulator gain (K).  Typical Value = 200. Default: 0.0
    - t1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Firing circuit time constant (T1).  Typical Value = 0.004. Default: 0
    - kc:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Rectifier regulation factor (K).  Typical Value = 0.004. Default: 0.0
    - vrmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum voltage regulator output (V).  Typical Value = 5. Default: 0.0
    - vrmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum voltage regulator output (V).  Typical Value = -4. Default: 0.0
    - tc1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Regulator lead time constant (T).  Typical Value = 0.8. Default: 0
    - tb1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Regulator lag time constant (T).  Typical Value = 6. Default: 0
    - tc2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Regulator lead time constant (T).  Typical Value = 0.08. Default: 0
    - tb2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Regulator lag time constant (T).  Typical Value = 0.01. Default: 0
    - toc1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : OEL lead time constant (T).  Typical Value = 0.1. Default: 0
    - tob1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : OEL lag time constant (T).  Typical Value = 2. Default: 0
    - toc2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : OEL lead time constant (T).  Typical Value = 0.08. Default: 0
    - tob2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : OEL lag time constant (T).  Typical Value = 0.08. Default: 0
    - tuc1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : UEL lead time constant (T).  Typical Value = 2. Default: 0
    - tub1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : UEL lag time constant (T).  Typical Value = 10. Default: 0
    - tuc2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : UEL lead time constant (T).  Typical Value = 0.1. Default: 0
    - tub2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : UEL lag time constant (T).  Typical Value = 0.05. Default: 0
