# Linear-Feedback-Shift-Register-LFSR-Design-Using-Cadence-Virtuoso

### Overview
This project involves the **design and simulation of a 5-bit Fibonacci Linear Feedback Shift Register (LFSR)** using **Cadence Virtuoso Schematic Editor**. The LFSR generates maximal-length pseudo-random binary sequences (period 31) essential for Built-In Self-Test (BIST), cryptography, error detection, and noise generation in VLSI systems.

### Key Highlights
- **Configuration**: 5-bit Fibonacci LFSR with XNOR feedback
- **Maximal Length**: Achieves full period of 31 (2⁵ - 1) states
- **Tools**: Cadence Virtuoso (Schematic Editor + ADE)
- **Components**: 5 D Flip-Flops + XNOR gate for feedback (taps [5,2])
- **Verification**: Transient & DC simulations confirm correct state transitions and sequence periodicity
- **Focus**: Pseudo-random sequence generation, feedback logic, and VLSI design flow

### Objectives
- Design and implement a 5-bit Fibonacci LFSR in Cadence Virtuoso
- Achieve maximal-length pseudo-random sequence using proper tap selection
- Verify functionality through transient simulation and waveform analysis
- Understand lock-up states and initialization strategies
- Gain hands-on experience with Cadence Virtuoso design and simulation flow

### Results
- Successfully simulated and verified the LFSR operation
- Generated pseudo-random sequence with exact period of 31 clock cycles
- Confirmed avoidance of lock-up states with proper seed initialization
- Demonstrated efficient use of XNOR feedback for sequence generation
- Clean schematic and reliable simulation results in Virtuoso environment

### Technologies & Components
- **Tool**: Cadence Virtuoso Schematic Editor & Analog Design Environment (ADE)
- **Logic**: D Flip-Flops (dff), 2-input XNOR gate
- **Simulation**: vpulse (clock), vdc (1.8V supply)
- **Design Flow**: Schematic capture, netlisting, transient analysis, waveform verification

---

**Status**: Successfully designed and simulated (March 2026)
