# Asset-Referenced Settlement Unit (Working Model)

*Note: Naming is provisional and subject to change.*

---

## Purpose

Define how value is represented within Open SCU for settlement and clearing.

---

## Concept

Instead of a fixed currency, OpenSCU uses a **dynamic reference unit** based on real-world assets.

This unit is:

- Not a tradable token  
- Not intended for retail use  
- Used solely for internal settlement  

---

## Initial Approach (v1)

The reference unit may be based on a basket including:

- Oil (e.g., Brent benchmark)
- Natural gas
- Other relevant commodities (future consideration)

---

## Key Design Questions

- What assets should be included?
- How should weights be determined?
- How often should the index rebalance?
- How do we handle volatility?

---

## Constraints

- Must remain simple and explainable  
- Must reflect real economic value  
- Must avoid unnecessary complexity  

---

## Open Questions

This model is intentionally incomplete.

Contributors are encouraged to explore:

- Alternative basket compositions  
- Weighting mechanisms  
- Stability models  

---

## Goal

To define a robust, transparent, and practical reference model for settlement.
