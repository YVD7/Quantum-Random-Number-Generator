# Quantum-Random-Number-Generator


🚀 Quantum Random Number Generator (QRNG) using Amazon Braket
📌 Overview

This project implements a Quantum Random Number Generator (QRNG) using Amazon Braket. It leverages the principles of quantum mechanics—specifically superposition and measurement—to generate truly random numbers.

Unlike classical pseudo-random generators, which rely on deterministic algorithms, this approach produces intrinsically unpredictable randomness, making it highly suitable for secure applications such as cryptography.

⚛️ How It Works

The QRNG is built using a simple one-qubit quantum circuit:

Initialize a qubit in state |0⟩
Apply a Hadamard gate (H) to create superposition
Measure the qubit → collapses randomly to 0 or 1
Repeat the process multiple times to generate a random bitstring
🧠 Key Concepts Covered
Quantum Superposition
Quantum Measurement
Randomness vs Pseudo-Randomness
Shannon Entropy
Cryptographic Key Generation
🛠️ Tech Stack
Python
Amazon Braket SDK
NumPy
Matplotlib
📊 Features

✔️ Quantum random bit generation using single-qubit circuit
✔️ Classical pseudo-random bit generation for comparison
✔️ Statistical analysis (0s vs 1s distribution)
✔️ Shannon entropy calculation
✔️ Cryptographic key generation (binary → hex)
✔️ Circuit visualization

🔍 Results & Observations
The quantum generator produces nearly equal numbers of 0s and 1s, indicating uniform randomness
Shannon entropy ≈ 1, showing high unpredictability
Classical random numbers are repeatable when the seed is known
Quantum-generated keys are non-deterministic and cannot be reproduced
🔐 Why Quantum Randomness Matters

Randomness is critical for secure systems. Weak randomness can lead to vulnerabilities.

Quantum Random Number Generators provide:

True randomness based on physical laws
Stronger cryptographic security
Resistance to prediction and reverse engineering
📸 Sample Circuit
q0: ──H──M──
🚀 Getting Started
1. Install Dependencies
pip install amazon-braket-sdk numpy matplotlib
2. Run the Project
python qrng.py
📈 Future Improvements
Run on real quantum hardware (IonQ / Rigetti via Amazon Braket)
Add advanced randomness tests (NIST test suite)
Integrate with secure key exchange systems
Build a web interface for real-time QRNG
🤝 Applications
Cryptographic key generation
Secure communications
Blockchain & fintech security
Scientific simulations
📚 References
Amazon Braket Documentation
Quantum Computing fundamentals
Shannon Entropy theory
👨‍💻 Author

Yash Dawande
Software Engineer | Quantum Computing Enthusiast
