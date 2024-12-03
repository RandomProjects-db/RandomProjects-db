## Fahed Daibes

[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Welcome+to+My+Profile;Exploring+DevOps%2C+Data+Science;And+Quantum+Computing;Building+Innovative+Tech+Solutions%21;Join+Me+on+This+Exciting+Journey;Always+learning+new+things)](https://git.io/typing-svg)

![Banner](./assets/quantum.png)

## 🚀 About Me  

Hi! I’m a passionate developer specializing in **DevOps**,
**Data Science**, and **Quantum Computing**.  
I love tackling complex problems and turning ideas into innovative solutions.
Currently, I’m working on exciting projects through the
 **MIT Emerging Talent Program** and looking forward to more impactful work.

## 💡 Core Skills & Interests

- 🔧 **DevOps**: Building automated workflows and optimizing systems.  
- 📊 **Data Science**: Transforming data into actionable insights.  
- ⚛️ **Quantum Computing**: Pioneering research in cutting-edge quantum technologies
- 🖥️ **IT Support**: Years of experience in IT infrastructure and troubleshooting.

## 🎯 Goals

- 🌱 Contribute to impactful open-source projects.  
- 🎓 Publish a quantum computing research paper.  
- 💼 Land a tech internship at a leading company by 2025.  

## 🔗 Fun Section: Create a Bell State  

Here’s a simple **Quantum Circuit** for creating a Bell state.
Can you modify it to entangle more qubits? 🧑‍💻

```python
from qiskit import QuantumCircuit, Aer, execute

# Create a Quantum Circuit with 2 qubits and 2 classical bits
qc = QuantumCircuit(2, 2)

# Apply a Hadamard gate on the first qubit
qc.h(0)

# Apply a CNOT gate (control=0, target=1)
qc.cx(0, 1)

# Measure the qubits
qc.measure([0, 1], [0, 1])

# Run the circuit on a simulator
simulator = Aer.get_backend('qasm_simulator')
result = execute(qc, simulator, shots=1024).result()
counts = result.get_counts(qc)

print("Bell state measurement results:", counts)
```

![My GIF](https://i.makeagif.com/media/7-10-2016/C4KvrW.gif)

# My GIFs Side by Side

| GIF 1 | GIF 2 |
|-------|-------|
| ![My GIF](https://i.makeagif.com/media/7-10-2016/C4KvrW.gif) | ![Another GIF](https://i.makeagif.com/media/7-10-2016/C4KvrW.gif) |
