# quantum-teleportation
#  Quantum Teleportation using IBM Quantum Composer and Qiskit

This project implements the **Quantum Teleportation Protocol**, where the quantum state of one qubit is transferred to another qubit using entanglement and classical communication.

---

## 🧠 Concepts Demonstrated

- Quantum Superposition
- Quantum Entanglement (Bell Pair)
- Measurement into Classical Bits
- Conditional Quantum Gates (X and Z)
- Quantum information transfer without physically moving the qubit

---

## ⚙️ Circuit Steps

1. Created a Bell pair between **q1** and **q2** using H and CNOT.
2. Combined the unknown state of **q0** with the Bell pair.
3. Measured **q0 → c0** and **q1 → c1**.
4. Applied conditional corrections on **q2**:
   - X gate if **c1 = 1**
   - Z gate if **c0 = 1**
5. After correction, **q2 holds the original state of q0**.

---

## 🛠️ Tools & Technologies

- IBM Quantum Composer
- OpenQASM 2.0
- Qiskit (Python) — for programmatic implementation

---

## 📂 Project Files

- `teleportation.qasm` — OpenQASM implementation
- `circuit.png` — Circuit design from Composer
- `teleportation.py / .ipynb` — Qiskit implementation (to be added)
- `README.md` — Project documentation

---

## ✅ Outcome

The project verifies that the unknown quantum state of **q0** is successfully reconstructed on **q2**, demonstrating the fundamental quantum teleportation protocol.
