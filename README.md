

# QC

![image](https://github.com/user-attachments/assets/5af79c13-5937-42fe-a2ef-f174a366eff9)


- https://docs.quantum.ibm.com/
- https://en.wikipedia.org/wiki/Quantum_computing
- 



# Syllabus

Here’s a detailed explanation of each point, helping you to grasp the fundamentals of quantum computing and its applications:

---

### **What You'll Learn**

#### **1. Which Types of Applications May Benefit from Quantum Computing**
- Quantum computing is not suited for all applications but excels in areas like:
  - **Optimization Problems**: Finding the best solution among many, such as logistics and supply chain.
  - **Cryptography**: Breaking encryption (Shor's algorithm) or creating secure communication (quantum cryptography).
  - **Simulating Quantum Systems**: Modeling molecules for drug discovery, materials science, and chemistry.
  - **Machine Learning**: Speeding up data classification, clustering, and optimization tasks.
  - **Big Data and AI**: Enhancing search algorithms and large-scale data analysis.
  - **Finance**: Portfolio optimization, risk analysis, and fraud detection.
  
  Quantum computers leverage quantum phenomena like superposition and entanglement to process information in ways classical computers cannot.

---

#### **2. Quantum Physics Principles and How They Affect Quantum Computing**
- **Superposition**: A qubit can exist in a combination of states (0 and 1) simultaneously, enabling parallel computations.
- **Entanglement**: Qubits can be interconnected such that the state of one affects the state of another, even at a distance. This enables faster communication between qubits.
- **Quantum Interference**: Manipulating qubits to amplify correct solutions and cancel incorrect ones during computations.
- **Quantum Measurement**: Observing a qubit collapses its state to either 0 or 1, making measurement non-reversible.

---

#### **3. Mathematical Representation of Quantum State**
 
- A quantum state is represented as a **vector** in a complex vector space.
  - Single qubit: \(|\psi\rangle = a|0\rangle + b|1\rangle\), where \(a, b \in \mathbb{C}\) and \(|a|^2 + |b|^2 = 1\).
  - Multi-qubits: Use the **tensor product** to combine states, e.g., \(|\psi\rangle \otimes |\phi\rangle\).
- The **Bloch Sphere** is a graphical representation of a qubit, showing its state as a point on a sphere.

---

#### **4. Individual Quantum Operations**
- Quantum operations are reversible and represented by **unitary matrices**.
  - **Pauli Gates**: \(X, Y, Z\) for flipping and rotating states.
  - **Hadamard Gate (H)**: Creates superposition.
  - **Phase Gates**: Add a phase shift to the quantum state.
- These gates manipulate qubits and form the building blocks of quantum circuits.

---

#### **5. Mathematical Operations to Calculate Quantum Operations**
- Operations on qubits involve:
  - **Matrix Multiplication**: Applying gates to qubits (state vectors).
    - Example: \(H|0\rangle = \frac{1}{\sqrt{2}}(|0\rangle + |1\rangle)\).
  - **Tensor Products**: Combine states of multiple qubits.
  - **Inner Products**: Measure probability amplitudes of states.
  - **Complex Numbers**: Capture phase information of qubits.

---

#### **6. Representation of Multi-Operation Sequences**
- Multi-operation sequences represent quantum circuits.
  - Sequence gates into a **circuit** to solve problems.
  - Example: \(H \rightarrow CNOT \rightarrow Measurement\).
  - Mathematically, this involves multiplying the matrices of individual gates to form a composite matrix.

---

#### **7. Deutsch’s Algorithm**
- A quantum algorithm demonstrating quantum speedup.
  - Problem: Determine if a function \(f(x)\) is constant or balanced (produces the same or different outputs for inputs 0 and 1).
  - Classical approach: Requires 2 function evaluations.
  - Quantum approach: Requires just 1 evaluation using superposition and interference.
  - **Steps**:
    - Prepare qubits in a superposition.
    - Apply \(f(x)\) as a quantum operation.
    - Interfere states to extract the answer.

---

### **Syllabus**

#### **QIS Applications & Hardware**
- Learn the types of hardware used (e.g., superconducting qubits, trapped ions).
- Explore real-world applications for quantum computing.

#### **Quantum Operations**
- Operations that manipulate qubit states using gates.

#### **Qubit Representation**
- Understand single and multi-qubit states using mathematical and graphical methods.

#### **Measurement**
- Collapsing quantum states into classical values.

#### **Superposition**
- How to create and utilize qubits in superposed states.

#### **Matrix Multiplication**
- Perform matrix operations to simulate quantum gates and circuits.

#### **Multi-Qubit Operations**
- Explore operations like **CNOT**, **SWAP**, and multi-qubit entangling gates.

#### **Quantum Circuits**
- Design and simulate circuits to solve problems.

#### **Entanglement**
- Learn how entangled states are created and utilized in computations.

#### **Deutsch’s Algorithm**
- Delve into this foundational algorithm to understand quantum speedup.


--- 
Introduction to Quantum Computing for Everyone

UChicagoX QUAN12000

# Goals
Welcome! In this course, we delve into the interdisciplinary endeavor of quantum computing, with a focus on developing intuition about the major benefits and limits that are imposed on quantum computing by the quantum phenomena as well as getting comfortable with how basic quantum operations behave. The specific goals of the course are:

Learn the intuition behind the quantum mechanics principles that affect quantum computing.
Learn basic quantum computing operations
Learn the mathematics necessary to calculate quantum operations
Learn how individual quantum operations are combined to create higher-level operations and algorithms
As a virtual course, most of the content will be included as videos followed by individual questions to practice / check understanding. In each section, there will be a larger homework assignment that tests the understanding of all videos of the section. 

# Resources
Textbooks that might be useful:

# Recommended: 
Q is for Quantum, Terry Rudolph
Dancing with Qubits, Robert S. Sutor
Course Pacing and Access to Assignments
This is a self-paced course. Please note that access to graded problems is only available to those enrolled for the verified certificate.

# Grading / Assignments
For those enrolled in the Verified track, each student’s final grade will be computed according to the following:

Practice questions following videos: 20%
Homework problems for each section: 35% 
Exam: 45%
Your lowest 2 scores on the practice questions will be dropped. 

An overall grade of 70% or higher will be considered a passing grade. 

# Section Overview

Quantum information science (QIS) is useful for a small set of very compelling applications, some of which we will introduce in this section. Then we’ll introduce some current quantum computing hardware and take a historical perspective on the development of quantum computing. Quantum operations occur at a qubit level. Unlike classical computing, there are not yet programming languages that allow programmers to abstract away critical details of quantum operations without needing to understand them. In this section, we will introduce operations on a single qubit.

# Quantum Computing: Introduction and Applications

There's been a lot of excitement surrounding quantum computing, so in this video we're going to provide a little bit of an introduction as well as describe some applications that quantum computers are proposed to be really good at.

![image](https://github.com/user-attachments/assets/094a13b8-00e5-4aa2-b2ff-3c09976230dc)

First, I want to highlight though that classical computing is everywhere. 
This classical computing paradigm is seen in everything from laptops to cell phones, super computers, etc.
And what powers these devices are different types of software like operating systems, apps, web browsers, etc.
So, if we have all this computing power available to us, why would we even need a quantum computer?
![image](https://github.com/user-attachments/assets/5ec15da5-4c6a-4392-a7cc-915fa1502a7f)
Well, that's because we have limitations on our classical computation.
Classical computers are really good at solving many day-to-day problems, such as algebra and calculus.
And they can do so faster than a human.  
But there are still many complex problems that  are intractable.
So, what does intractable mean, exactly? That means that we need an infinite or a lot of resources or time to solve these problems.  
Some examples of these types of problems include natural processes and finding a solution when there might be an exponentially large set of potential solutions.
![image](https://github.com/user-attachments/assets/c51de922-ae05-49e6-b208-a10e986c0c63)
One particular example of this type of problem is  chemistry simulation.
So, chemistry simulation is a modeling of a natural process as well as trying to find a solution and a state space where there are many different types of possible solutions.
So, whenever we think about chemistry simulation, that can involve simulation of molecules.   
And it can be applied to develop improved chemicals and materials such as pharmaceuticals or fertilizers.So, classical simulation techniques for chemistry are implemented with a sort of guess and check type of mechanism.  
In this kind of process, theorists will develop a hypothesis, we'll have experiments that are outlined and performed and then these results are analyzed.
And then with those results, we develop new theories.  So the efficient simulation of atoms and simple  molecules is one of these things that we suspect that near-term quantum computers are going to be really, really good at.So, we can look at an example of this. Classical computers have a really difficult time representing information associated with chemical bonds and that's because all the components in a molecule in a way fuel each other.![image](https://github.com/user-attachments/assets/646c6d91-5348-4743-a31f-626e6fb05b50) So if you adjust one placement of one of those particles, all of the rest are impacted.
So that creates many, many different variations that can exist with how the structure of the molecule is set up.
So molecules of course have protons, neutrons, electrons, and these can all be organized in different variations of configurations. So caffeine, pictured here, is simply a 24 atom molecule but we would need 10^48 bits to represent that and that's a lot!
All the possible different energy arrangements would equal quite a lot of information to represent in the classical computer, so it's intractable.
However, a quantum computer could hold all this information in 160 cubits, which is a lot less than 10^48 bits. Another proposed application for quantum  computers would be optimization problems. 
![image](https://github.com/user-attachments/assets/18b19570-d94a-4c32-abbe-89bc10a4cdd7)
So, optimization problems fall into that category  of problems that have a very, very large state space for the answers that are possible.  
So when we think of optimization, we can try to maximize resources in terms of time, energy, hardware.
And one example of this is the fact that UPS optimizes its routes for minimal left turns rather than shortest route. So because of this, it's able to save 10,000,000 gallons of fuel each year and deliver 350,000 more packages.
So that's pretty significant.
Classical optimization involves really computationally expensive types of search algorithms. Most of the time we can't even find the best, we just have to find a good enough solution out of all the potential solutions. So, because quantum computers are good at exploring large state spaces, they're anticipated to be really good at finding optimum solutions for these types of optimization problems.
![image](https://github.com/user-attachments/assets/75098047-a857-48b2-afc9-37f7fabb9d8f)
So let's kind of dig a little deeper into that. An example application for quantum computers would be an optimization problem known as the traveling salesman problem. So, the traveling salesman problem is a problem that aims to find the shortest route in a round trip journey.
So here we have a picture of a tour of Italy and we have the optimum route, outlined here.
We want to try to find the route where we we travel the shortest amount of distance possible.
And that can get to be quite a lot of different variations of the journey as we include more cities in our trip. So let's look at this. If we have 20 cities that we're visiting.  
We actually implement a factorial all the way down  to 20 x19 x18... all the way down to 1.  
And that creates a very, very large number of combinations for the possible journeys that we can take. So quantum computers model optimization in such a way that qubit optimization or qubit observation has a high probability of determining the best route without having to check each single one.
So, that's done through the simple procedure of defining a target solution and defining the cost, encoding qubits with our search equation, and then allowing those qubit values to converge to the ideal route in relatively few number of iterations. 

![image](https://github.com/user-attachments/assets/f827502e-2386-4856-893d-42af1139d9b5)

So to kind of summarize some of the applications that quantum computers are targeted to be really good at, we have chemistry applications such as battery material discovery, fertilizer production, drug discovery, material durability. We have optimization problems, so financial market analysis, manufacturing applications, and then transportation optimization as well.
Security applications. So, we have more robust encryption schemes and more secure key generation are some examples of ways that we can apply quantum computing to security.
And then, of course, machine learning. So we can apply quantum computers in applications, potentially for artificial intelligence, audio and image generation, and predictive models. 
![image](https://github.com/user-attachments/assets/4f57d3d0-cae5-42b2-91de-0809cdf30f57) 
So let's look a little bit more into what the difference between a classical and quantum computer is physically.
So, we look here. To the left we have the Summit supercomputer and to the right we have a UChicago quantum computer.
So here we have around 250x10^15 bytes of storage.  
That's a lot of storage compared to the tens of  qubits of storage on the Shuster quantum computer.  
So, although the quantum computer is a lot smaller in terms of number of fundamental units it includes, so we have the qubit over to the right on the quantum computer rather than the bit on the left with the classical computer, we have a lot of benefits in the way that we encode information that allows us to get those those speed-ups with certain types of computation. 
![image](https://github.com/user-attachments/assets/5dac03b4-2f5e-4e10-b76a-6a97cc5a8714)
So moving forward with quantum machines, we need to make them more robust, more reliable, and generally scale them so that we can implement these different types of algorithms: for optimization, for simulation of natural processes, and for security purposes.
So there's many technical challenges that exist currently with scaling these machines in the terms of number of qubits.
And that's because we have relatively short lifetimes and they're very error-prone. They're very willing to communicate, not only  with each other but the surrounding environment.  
So we want to make sure that we make the world more robust from interactions outside of their computation.
So we have these devices that are currently very sensitive and we have limitations due to hardware and software, so we need to have more of these, not only more qubits, but more connections between these qubits. Finally, we also need to think about improving the control and hardware that will allow for more sophisticated systems and algorithms.
We just have a couple of applications that we've outlined here but there's a lot more potential to discover new applications, especially as these devices become a lot more robust, reliable, and increase in size.
![image](https://github.com/user-attachments/assets/a702ce62-a614-480c-bcb6-d121405e8f79)

So some takeaways: quantum computing is projected to be revolutionary and can potentially drastically change the way we solve some of the most challenging problems that exist for us today.
In this course, we'll learn a little bit more about why quantum information is different from classical information and how it potentially can change the world.

////









  
