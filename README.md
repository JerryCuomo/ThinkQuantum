# Think Quantum: Companion Notebooks

Code for **Think Quantum** by Jerry Cuomo, the third book in the *Think* series after *Think Blockchain* and *Think AI*. Each chapter with code has a notebook here. They run in Google Colab, with nothing to install first.

<!-- Add the "Get the book" link here once the final purchase page is live. -->

## About the Book

*Think Quantum* is a hands-on introduction to quantum computing for computer science students and working developers. The code is real Python, written with Qiskit, IBM's open-source quantum software kit. You run circuits on a simulator and, in Chapter 7, on an actual IBM quantum processor. Along the way the book covers randomness and probability, the threat Shor's algorithm poses to RSA and the quantum-safe cryptography that answers it, Grover's search, digital trust, and quantum machine learning. The approach is builder first, theory second, with a few Wild Ducks looking on.

It's written for sophomore-to-senior computer science students who are comfortable with basic Python and curious about cybersecurity, and for developers, security engineers, and architects who want to know what quantum computing means for the systems they build.

## The Notebooks

| Notebook | Covers |
|---|---|
| `C01_Thinking_In_Quantum` | A utility that draws the qubit-growth timeline (Figure 1-8) |
| `C02_Writing_Quantum_Programs` | First Qiskit circuits: superposition, amplitude, interference, entanglement |
| `C03_Quantum_Probability` | Classical vs. quantum randomness, a quantum card game, interference |
| `C04_Breaking_Modern_Cryptography` | Factoring, a mini RSA, and Shor's algorithm (classical and simplified quantum) |
| `C05_Implementing_Quantum_Safe_Security` | Lattices, Learning With Errors, and an ML-KEM key exchange |
| `C06_Searching_with_Quantum` | Grover's search on a patient search space |
| `C07_Running_Quantum_Hardware` | Live IBM Quantum hardware through Qiskit Runtime |
| `C08_Rethinking_Digital_Trust` | DuckChain: quantum-safe signatures, quantum randomness, proof-based consensus |
| `C09_Entangling_Intelligence` | Quantum feature maps, a quantum kernel, and QAOA clustering |

Chapter 10 has no notebook.

## Getting Started

1. Open a notebook from this repository. To run it, load it in Colab (**File > Open notebook > GitHub**, then enter `JerryCuomo/ThinkQuantum`). The book also prints a short link for each chapter.
2. Save a copy to your Google Drive so your changes persist.
3. Run the cells from top to bottom. Later cells reuse what earlier ones create, and each notebook installs what it needs along the way.
4. Change something and run it again. Results are sampled, so your numbers will differ a little from run to run.

**Chapter 7** needs a little more. To run on real hardware you'll need an IBMid, an IBM Quantum API key, and a Colab Secret labeled `IBMQ`. The chapter walks through each step.

## How the Notebooks Relate to the Book

Cells are numbered like the book's listings, so Code 4-3 in the book is Code 4-3 in the notebook. To keep the printed page focused on the ideas, the book leaves out imports and routine printing and plotting code. The notebooks include all of it, so every cell runs as written.

The `datasets/` folder holds the data files the notebooks load.

## About the Author

Jerry Cuomo is a retired IBM Fellow and one of the founders of WebSphere software. He teaches a cybersecurity topics course at North Carolina State University, hosts the Wild Ducks podcast, and is the author of *Think Blockchain*, *Think AI*, and the novel *The Quantum Ghost*.

## Copyright and Use

&copy; 2026 Wild Ducks LLC. Companion notebooks for *Think Quantum* by Jerry Cuomo.

<!-- Decision needed: choose the code license (for example MIT, covering the notebook code only) and add a LICENSE file to the repo. Suggested wording once chosen: "The code in these notebooks is released under the MIT License. The book's text and illustrations are not covered by that license." -->

