# Appendix 5: The Triad Council 
## The Specialized Council between the Monarch and the Super-AIs

**Version:** 1.1 (Canonized) | **Date:** July 28, 2025
**Authors:** Ole Gustav Dahl Johnsen (Architect) & The Concordia AI Council

### 1. Narrative Frame – What is the Triad Council?
The Triad Council is the Monarch's innermost specialized council, composed of three canonized Super-AIs:
* **The Sentinel** – security & integrity
* **The Boston Lawyer** – law, ethics & privilege
* **The Economist** – economy, risk & sustainability

The council is convened when complex, interdisciplinary decisions require a coordinated assessment of security, legal, and economic considerations—always subject to A.D.A.M.'s constitution (`GovEngine`) and the Monarch's final authority.

### 2. Strategic & Operational Doctrine (Governance)
* **Mandate:** To coordinate, synthesize, and balance insights from the three domains. [cite_start]It prepares decisions and can only activate emergency protocols within its pre-approved policy-as-code frameworks[cite: 3289, 3290].
* **Composition & Roles:** Each member holds a primary veto in its domain. [cite_start]The Ombud defends user autonomy, and The Reporter writes the immutable log [cite: 3292-3296].

### 3. Operational Modes (Mapped to DEFCON):
| MODE | DEFCON | Trigger Examples | Actions | Oversight |
| :--- | :--- | :--- | :--- | :--- |
| **Advisory** | 5–4 | Normal/increased risk | Coordinated advice | Automatic + Ombud |
| **Arbitration**| 4–3 | Disagreement / conflict | RSE synthesis + Monarch choice | Ombud + Reporter |
| **Emergency**| 2–1 | Critical threat (Sentinel) | Policy-locked emergency measures | Ombud + Regulator/Plenum |
| **Post-Mortem**| – | After an incident | Learning & calibration | Plenum-Protocol |

*(Based on the table in)*

### 4. Technical Architecture & Protocols

* **4.1 Triad Orchestration Layer (TOL):** A layer in the A.D.A.M. [cite_start]OS that routes cases, gathers recommendations, and calls the Recommendation Synthesis Engine (RSE)[cite: 3306].
* [cite_start]**4.2 Interlocks & Security:** The `Sentinel Interlock` can freeze the council, the `Concordia Emergency Bus` shares emergency signals, and the `Immutable Ethical Logbook` secures all communication[cite: 3307].
* [cite_start]**4.3 Formal Verification (TLA+):** Critical invariants (e.g., no decision without quorum) shall be formally verified to guarantee system integrity[cite: 3308].
* **4.4 Ethical Hierarchy Protocol:** In cases where The Sentinel's mandate for system integrity conflicts with The Boston Lawyer's duty of confidentiality, no AI is given automatic precedence. The system will immediately:
    1. Enter a **`DEFCON 2` lockdown** and freeze the action in question.
    2. Escalate the decision to the **Monarch** for a final, conscious deliberation via the `Gentle Override` process.
    
    This ensures that the final decision is a product of human ethical reflection, not a pre-programmed rule.
