# Academic Showcase

I am a Computer Science master's student at the University of Milano-Bicocca, with interests in quantum computing, theoretical computer science, and the design of clean, well-structured, and elegant software.

This page collects a curated overview of my academic projects: selected work that best represents my interests and approach, followed by a broader list of additional university projects.

## Selected Projects

These are the academic projects I consider the most representative of my interests, technical approach, or learning path.

### [Quantum Fourier Transform Lab](https://github.com/rChimisso/qft-laboratory-report)

**Quantum Computing**

A laboratory assignment on Quantum Fourier Transform developed as both a written report and an executable notebook. It combines the mathematical side of QFT with a practical implementation in PennyLane, including a comparison between the classical Discrete Fourier Transform and quantum circuits built both manually and with PennyLane's native QFT tools.

**Highlights**

* Implemented a classical DFT and custom QFT circuits for an arbitrary number of qubits
* Compared QFT and DFT behaviour on different input families, including sparse, constant, and periodic signals, for 4- and 10-qubit cases
* Explored the gate-level structure of the transform, including a decomposition of the controlled phase shift into elementary operations
* Tools: Python, PennyLane, NumPy, Matplotlib, Jupyter Notebook

<img width="1689" height="389" alt="image" src="https://github.com/user-attachments/assets/441646fe-75f0-4dba-86a5-2144bb20ce8c" />

---

### [OpenGL Showcase](https://github.com/rChimisso/opengl-showcase)

**Computer Graphics**

A graphics project focused on real-time rendering techniques in OpenGL. The scene combines multiple lighting and shading features, with particular attention to how visual effects are built at the shader and scene-management level rather than treated as isolated demos.

**Highlights**

* Implemented procedural texturing through a time-varying Perlin-noise-based surface
* Built a lighting setup with multiple point lights, cubemap shadow mapping, normal mapping, a skybox, and a Phong lighting system
* Explored how rendering choices affect realism, scene readability, and technical complexity
* Tools: C++, OpenGL, GLSL

<img width="1908" height="1072" alt="image" src="https://github.com/user-attachments/assets/8b950a1c-7cb7-47a7-8d8f-2256aa20ccc6" />

---

### [E1P-Prolog](https://github.com/rChimisso/E1P-Prolog)

**Logic Programming / Parsing**

A Prolog library for parsing strings into URIs, built as a structured and modular exercise in logic programming. Beyond the parsing task itself, the project is interesting because it turns a formal specification into a composable implementation with separate handling for URI components and display utilities.

**Highlights**

* Implemented a URI parser exposed through `uri_parse/2`, with additional utilities for displaying parsed URIs
* Structured the parser into modular components for parts such as scheme, authority, path, port, query, and fragment
* Worked on correctness, composability, and clean predicate-level organization
* Tools: SWI-Prolog

---

### [GrayDCT2](https://github.com/rChimisso/mcs-prog-2)

**Scientific Computing / Numerical Methods**

A project for the Scientific Computing course that compares naive and fast DCT-II implementations and applies JPEG-like compression to grayscale `.bmp` images. It combines algorithmic comparison, practical image processing, and a well-documented software structure with testing and automated documentation.

**Highlights**

* Compared naive and optimized DCT-II approaches and connected them to a concrete compression workflow
* Built a small application for JPEG-like compression of grayscale bitmap images
* Included a report with results and analysis, automated code checks, generated documentation, and release builds for Linux and Windows
* Tools: Python, SciPy, Sphinx, pytest

<img width="1493" height="309" alt="image" src="https://github.com/user-attachments/assets/e1c51473-b749-4a64-96a6-5398fd8e8cb4" />

---

### [De Bruijn Graph Sequence Reconstruction](https://github.com/rChimisso/bioinfo)

**Bioinformatics / Algorithms**

A bioinformatics project centered on reconstructing a sequence from FASTA/FASTQ reads through a de Bruijn graph. What makes it notable is the algorithmic perspective: the project approaches a biological problem through graph-based reconstruction and careful data representation.

**Highlights**

* Implemented sequence reconstruction from reads in FASTA/FASTQ format through a de Bruijn graph approach
* Worked on a problem that sits at the intersection of algorithms, graph structures, and biological data
* Documented the project with Sphinx and LaTeX-based output options
* Tools: Python, Sphinx

---

### [Frozen Lake DQL](https://github.com/Crystal-Spider/Frozen-Lake-DQL)

**Machine Learning / Independent Study**

An early (high school age) project built in Processing to explore Deep Q-Learning through direct implementation rather than high-level frameworks. It is worth highlighting not because of scale, but because it reflects an early effort to understand the mechanics behind neural networks, gradient descent, backpropagation, and reinforcement learning in a hands-on way.

**Highlights**

* Implemented a Frozen Lake environment with Deep Q-Learning in Processing 3.4 without external libraries
* Treated the project as a way to study the fundamentals behind learning algorithms more deeply
* Included a visual representation of the neural network during training, making the learning process more inspectable
* Tools: Processing / Java

## Other Academic Projects

A selection of additional projects completed during my studies.

* **[SPARK: Synthetic Probes for Assessing Reasoning on Knowledge-graphs](https://github.com/rChimisso/SPARK)** − Master’s AI project on evaluating multi-hop question answering over knowledge graphs, comparing hop length, prompting strategies, graph variants, and efficiency metrics across different language models.
* **[MatIter](https://github.com/rChimisso/mcs-prog-1)** − Scientific computing project providing iterative solvers for symmetric positive definite systems, with comparisons among Jacobi, Gauss-Seidel, Gradient Descent, and Conjugate Gradient methods.
* **[Bachelor’s Thesis](https://github.com/rChimisso/computer-science-bachelor-thesis)** — Thesis materials for my bachelor’s work on exploring and comparing deep learning architectures for predicting brain responses to realistic images, with an accompanying arXiv publication.
* **[2WSI-RL](https://github.com/rChimisso/2WSI-RL)** − Reinforcement learning study on traffic-light intersection management, built around simulation, experimentation, and analysis of RL approaches in a control problem.
* **[E1P-Lisp](https://github.com/rChimisso/E1P-Lisp)** − Lisp library for parsing strings into URIs, developed as a structured exercise in language design, parsing logic, and modular implementation.
* **[Che Fico!](https://github.com/rChimisso/che-fico)** − Android application developed to identify plants, save their locations, and set reminders, combining mobile development with a practical user-facing workflow.
* **[SD REST](https://github.com/rChimisso/sd-rest)** − Distributed systems project for a banking-style full-stack application, combining a Java/Spring backend with an Angular/TypeScript frontend and extensive code documentation.


## Notes

Most of the repositories collected here were developed in academic contexts, but they also reflect broader interests that continue to shape my work, especially in quantum computing, theoretical computer science, and software design.
