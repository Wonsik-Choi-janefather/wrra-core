# WRRA Domain Profile Template

Use this template to implement WRRA Core 1.0 in a new field without changing the Core itself.

| Field | Required entry |
|---|---|
| Domain name / version | Example: `WRRA-Art 0.1` |
| Target contract | Interpretation, computation, prediction, control, or OPEN |
| Validation inputs | Observed values, calibrated constants, datasets, or boundary conditions used to fix the model |
| SOURCE | Current independent inputs and resources |
| RELATION / LAW | Permitted interactions and rules |
| STATE / RESIDUE | Current state and presently instantiated effects of the past |
| BOUNDARY | Inside/outside distinction and inflow/outflow |
| COMMON CARRIER | Shared transport or update scaffold |
| WRRA-specific transformation | Core-derived mapping, computation, or structural operation applied to the inputs |
| UPDATE | Equation or rule generating the next present |
| RENDERER / PHENOTYPE | Mapping from internal state to external expression |
| OBSERVABLE / LEDGER | Measurements, conservation/accounting, and records |
| Output | Reproduced value, explanation, computed state, or unmeasured quantity produced by WRRA |
| Minimality baseline | Simpler null or reference model |
| Falsification conditions | Result that would reject, reduce, or reopen the WRRA extension |
| Current verdict | EXACT, COMPUTED, STRUCTURAL, CONDITIONAL, PARTIAL, OPEN, or FAIL-CLOSED |

## Minimum conformance checklist

1. SOURCE is specified.
2. Owners of current STATE and past RESIDUE/RECORD are distinguished.
3. BOUNDARY and external inputs are specified.
4. The common carrier states what is shared and what remains distinct.
5. UPDATE generates the next present.
6. RENDERER and PHENOTYPE are defined.
7. A minimum-computation comparator or baseline is provided.
8. OBSERVABLE, RECORD, and LEDGER are specified.
9. Failure conditions are declared in advance.

## Required evaluation chain

```text
Validation input → WRRA-specific transformation → Output → Falsification condition
```

Known constants and observed values may be used to calibrate a Domain Profile. A known value reproduced through WRRA's own structure is a reality-consistency and explanatory result. After the model is fixed, an unmeasured quantity computed by that same structure is recorded as a WRRA prediction.
