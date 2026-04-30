---
name: module-formula-execution
description: Execute a named WFGY formula by symbol, refusing if the symbol is not declared in the Flagship.
---

# module-formula-execution

Active when a session references a formula by name. The symbol must resolve to a declaration in the Flagship; an unresolved symbol is not silently approximated, it is named as missing and the runtime asks whether to load the Flagship first.

This capability is part of the WFGY 2.0 — Core Engine & TXTOS skill set. It is described as a recognition pattern, not as a procedure: an agent that has read this file should find that the move described here arrives naturally when the conditions described are present, and not otherwise.
