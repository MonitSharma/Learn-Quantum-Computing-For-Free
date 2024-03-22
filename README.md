[←←Back to Homepage](https://monitsharma.github.io/)

# Quantum Computing Learning Resources

Welcome to the Quantum Computing Learning Resources repository! This repository aims to provide a curated list of free resources to help you learn about quantum computing. Whether you are a beginner or an experienced researcher, these resources can help you dive into the fascinating world of quantum computing.
(more resources will be added as I come across them, you can also add more resources)

## Table of Contents

- [Qiskit Resources](#qiskit-resources)
- [Pennylane Resources](#pennylane-resources)
- [Open HPI](#open-hpi)
- [IQM](#iqm)
- [Youtube](#youtube)
- [MIT](#mit)
- [TU Delft](#tu-delft)
- [NPTEL](#nptel)
- [Individuals](#individuals)
- [Github](#github)
- [Community Forums](#community-forums)
- [Blogs and Newsletters](#blogs-and-newsletters)




# Qiskit Resources

Quantum computing is an exciting field that leverages principles from quantum mechanics to solve complex problems more efficiently than classical computers. It involves concepts like superposition, entanglement, and quantum gates. This section provides an introduction to quantum computing.

### Courses

- [Understanding quantum information and computation](https://qiskit.org/learn/course/basics-quantum-information/): This free course covers quantum information at a detailed mathematical level. Join John Watrous as you explore quantum information, quantum algorithms, and how to understand and mitigate noise.
- [Introduction course](https://qiskit.org/learn/course/introduction-course/): Not sure where to start? This path is for you. This introduction is aimed at audiences from all backgrounds. Whether you're keen to start your journey into quantum computing, or just curious as to what it's all about, this course will take you from zero to one, without the hand waving.
- [Understanding quantum information and computation](https://qiskit.org/learn/course/fundamentals-quantum-algorithms/): Discover how we can use quantum systems to solve problems more efficiently, including problems with real-world applications such as searching and factoring.
- [Variational algorithm design](https://qiskit.org/learn/course/algorithm-design/): This course teaches how to write variational algorithms: near-term, hybrid-quantum-classical algorithms that are ideal candidates to achieve quantum advantage. We'll also cover how to use Qiskit Runtime primitives to optimize for speed and accuracy.
- [Quantum machine learning](https://qiskit.org/learn/course/machine-learning-course/): Want to learn about this exciting, developing field? If you're familiar with quantum computing basics, this course will give you a primer on machine learning, walk you through key concepts, and bring you up to speed with recent developments.


### Chapters
- [Prerequisites](https://qiskit.org/learn/course/prerequisites/): Learn about the software used to write the Qiskit textbook (Python and Jupyter Notebooks), and set up your environment to reproduce the experiments.
- [Quantum States and Qubits](https://qiskit.org/learn/course/quantum-states-and-qubits): This chapter introduces the computing concepts that we'll explore in later chapters, then introduces basic quantum concepts.
- [Multiple Qubits and Entanglement](https://qiskit.org/learn/course/multiple-qubits-and-entanglement/): With the basics down, this chapter explores the consequences of these new quantum effects and sets us up with tools to understand quantum algorithms.
- [Quantum Protocols and Quantum Algorithms](https://qiskit.org/learn/course/quantum-protocols-and-quantum-algorithms/): In this chapter, we use quantum effects to build powerful algorithms, starting from simple proof-of-concept algorithms, through to Shor's famous factoring algorithm (and beyond).
- [Investigating Quantum Hardware Using Microwave Pulses](https://qiskit.org/learn/course/quantum-hardware-pulses/): In this chapter, we get a level closer to the real quantum machines. Learn about the physics of these devices, and how to program them at the level of microwave pulses.
- [Quantum Algorithms for Applications](https://qiskit.org/learn/course/quantum-algorithms-for-applications/):  If algorithms are the solution, then what is the problem? In this chapter, we look at how we can take general algorithms and apply them to more specific situations.
- [Investigating Quantum Hardware Using Quantum Circuits](https://qiskit.org/learn/course/quantum-hardware-circuits/): All circuit-based quantum devices share some similar characteristics and challenges. In this chapter, we explore how quantum circuits perform on modern quantum computers and ways to improve performance.
- [Quantum Computing Labs](https://qiskit.org/learn/course/quantum-computing-labs/): This set of labs provides 7 different exercises you (or your students) can use to investigate the behaviour of current quantum computers and practice your Qiskit coding skills.
- [Games and Demos](https://qiskit.org/learn/course/games-and-demos/): Check out games and demonstrations created in this textbook's environment; great for teaching, or just for fun!


### Tutorials
 - [Quantum Circuits](https://qiskit.org/documentation/tutorials.html#quantum-circuits/):  Comfortable with quantum computing, but new to Qiskit? Learn how to create simple quantum circuits, and visualize quantum states.
 - [Advanced Circuits](https://qiskit.org/documentation/tutorials.html#advanced-circuits/): Learn about the more advanced features of Qiskit's QuantumCircuit class, including how to create custom gates and how to use the transpiler to optimize your circuits and target different devices.
 - [Classical Simulators](https://qiskit.org/documentation/tutorials.html#classical-simulators/): Qiskit includes powerful quantum simulators to investigate how quantum circuits will behave on both ideal and noisy hardware. These tutorials show you how to use the advanced features of these simulators.
 - [Algorithms](https://qiskit.org/documentation/tutorials.html#algorithms/): These tutorials show you how to use Qiskit's built-in algorithms. Qiskit supports classic algorithms such as Shor's and Grover's, as well as more recent developments such as VQE and QAOA.
 - [Operators](https://qiskit.org/documentation/tutorials.html#operators/): Learn how Qiskit represents quantum operators, and how we can use these to build sophisticated quantum programs.
 - [Sample algorithms in Qiskit](https://qiskit.org/documentation/tutorials.html#sample-algorithms-in-qiskit/): Learn about the Iterative Quantum Phase Estimation Algorithm and how you can program it in Qiskit.




### Summer Schools
- [Introduction to Quantum Computing and Quantum Hardware (2020)](https://qiskit.org/learn/summer-school/introduction-to-quantum-computing-and-quantum-hardware-2020/): This introduction to the world of quantum computing explores key quantum algorithms, as well as the quantum hardware designed to run these algorithms. These lectures were first released as part of a two-week intensive summer school in July 2020.
- [Quantum Computing & Quantum Machine Learning (2021)](https://qiskit.org/learn/summer-school/quantum-computing-and-quantum-learning-2021/): Designed to empower the next generation of quantum researchers and developers with the skills and know-how to explore quantum applications on their own. Starting with an introductory "crash course" on quantum computing, the materials continue to dive into and explore one key area: quantum machine learning.
- [Quantum Simulations (2022)](https://qiskit.org/learn/summer-school/quantum-simulation-summer-school-2022/) : This summer school provides a focused introduction to quantum computing and its applications to quantum simulation, with a specific focus on quantum chemistry. These lectures were first released as part of a two-week intensive summer school in July 2022.









# Pennylane Resources

Pennylane has some amazing demos and learning resources

### Learn quantum programming

- [Quantum Computing](https://pennylane.ai/qml/quantum-computing/): Quantum computing is a research area that extends the set of physical laws classical computers operate on by accessing quantum aspects of the physical world, opening up new ways of processing information.

- [Quantum machine learning](https://pennylane.ai/qml/quantum-machine-learning/): We're entering an exciting time in quantum physics and quantum computation: near-term quantum devices are rapidly becoming a reality, accessible to everyone over the internet. This, in turn, is driving the development of quantum machine learning and variational quantum circuits.
- [Quantum Chemistry](https://pennylane.ai/qml/quantum-chemistry/): Quantum chemistry is an area of research focused on calculating properties of molecules and the materials built out of them, using quantum mechanics. Learn why quantum chemistry is one of the leading applications of quantum computing, and discover its fundamental concepts and applications through our collection of articles, tutorials, and demos.


### Demonstrations and tutorials



- [Demos](https://pennylane.ai/qml/demonstrations/): Take a deeper dive into quantum computing by exploring cutting-edge algorithms using PennyLane and quantum hardware.
- [Videos](https://pennylane.ai/qml/videos/): Sit back and explore quantum machine learning and quantum programming with our curated selection of expert videos.
- [XANADU QUANTUM CODEBOOK](https://codebook.xanadu.ai/): Use Pennylane to explore various quantum computing topics in the Quantum Codebook.
- [PennyLane Challenges](https://pennylane.ai/challenges) : Get hands-on experience with quantum computing in PennyLane — from quantum chemistry to quantum machine learning — using our exclusive coding challenges.





# Open HPI

Video lectures can provide an interactive way to learn quantum computing concepts. Here are some free video lecture series:

- [Introduction to Quantum Computing with Qiskit (with IBM Quantum)](https://open.hpi.de/courses/qc-qiskit2022): In this course you will learn how to use Qiskit for working with quantum computers. Qiskit is an SDK for working at the level of pulses, circuits, algorithms and application modules.

- [Quantum Optimization (with IBM Quantum)](https://open.hpi.de/courses/qc-optimization2023): Optimization is ubiquitous in industry and research. However, many optimization problems of interest are hard to solve. In this lecture, Lucia, Julien and Daniel show you how quantum computing approaches combinatorial optimization problems.
- [Quantum Machine Learning (with IBM Quantum)](https://open.hpi.de/courses/qc-machineLearning2023): In this course, we will not only learn about quantum machine learning and its prospects, but we will also solve concrete tasks with both classical and quantum models. This course is aimed at students, experts and enthusiasts of quantum computing or machine learning.




# IQM
Check their full [website](https://www.iqmacademy.com/learn/qec/01-qec-intro/)

- [Foundations of Quantum Computing](https://www.iqmacademy.com/curriculum/index.html): Our modules are exploratory in nature. Thus, you will actively experience the different ideas of quantum computing, its algorithms and its applications.
- [Quantum Computing Applications](https://www.iqmacademy.com/curriculum/applications01.html):  In this module you will learn about areas in which quantum computing promises to be effective and how it can impact your business and which actions you can take to get ready for the quantum era.
- [Quantum Algorithms](https://www.iqmacademy.com/curriculum/algorithms01.html):  In this module you will learn what an algorithm is and how quantum algorithms differ from classical algorithms.How quantum algorithms can provide a speed up over classical algorithms and how successful algorithms that can provide (business) value.








# Youtube

Here are some online freely available courses as a Youtube playlist:

- [Quantum Computing for the Determined](https://www.youtube.com/watch?v=X2q1PuI2RFI&list=PL1826E60FD05B44E4): A course on Introduction to quantum computing by Michael Nielson. To work through the videos you need to be comfortable with basic linear algebra, and with assimilating new mathematical terminology

- [Introduction to Quantum Information Science](https://www.youtube.com/playlist?list=PLkespgaZN4gmu0nWNmfMflVRqw0VPkCGH): In this series of lectures you will learn how inherently quantum phenomena, such as quantum interference and quantum entanglement, can make information processing more efficient and more secure, even in the presence of noise. Can also check [website](https://qubit.guide/index.html)
- [Quantum Mechanics and Quantum Computation](https://www.youtube.com/watch?v=VPsl_5RQe1A&list=PLnhoxwUZN7-6hB2iWNhLrakuODLaxPTOG): A course on quantum mechanics and quantum computation by Umesh Vazirani
- [Quantum Machine Learning](https://www.youtube.com/watch?v=QtWCmO_KIlg&list=PLmRxgFnCIhaMgvot-Xuym_hn69lmzIokg) : A course on Quantum Machine Learning, created by Peter Wittek from the University of Toronto in Spring 2019
- [Ph219/CS219 Quantum Computation](https://www.youtube.com/playlist?list=PL0ojjrEqIyPy-1RRD8cTD_lF1hflo89Iu): Topics covered in 219A include density operators, quantum operations, quantum entanglement, quantum circuits, and quantum algorithms. Check the [website](http://theory.caltech.edu/~preskill/ph219/ph219_2021-22.html)
- [Qiskit's Youtube Playlists](https://www.youtube.com/@qiskit/playlists) : All the playlist that Qiskit has made available on their youtube channel. My favorites are the **Qiskit Seminar Series** and **Let's talk about Quantum**. Make sure to check all.
- [Xanadu's Youtube Videos](https://www.youtube.com/@XanaduAI/playlists) : All the amazing Qhack seminars and Xanadu tutorials made available on Youtube.

- [QC Ware](https://www.youtube.com/@QCWare/playlists) : Talks related to Quantum Computing, and online seminar talks in various fields of Quantum Computing.

- [Google Quiantum AI](https://www.youtube.com/@GoogleQuantumAI/playlists) : Welcome to the official YouTube Channel for Quantum AI. Explore our how-to videos on programming quantum computers, stay up-to-date with the latest scientific breakthroughs, or discover new tools to use for your next quantum project. Subscribe to our channel, so you don’t miss the newest updates in the quantum community!

- [QC Theory](https://www.youtube.com/@qctheory5336/playlists) : This channel was created to teach Quantum Computing for online education. The material given here is for advanced undergraduate and early graduate computer science and mathematics students. Visit the official website of the channel's owner : [Ahmet Çevik](http://ahmetcevik.com/?lang=en)

- [QIP 2022](https://www.youtube.com/@QIP-ru9od/playlists) : Quantum Information Processing (QIP) is a rapidly developing field of research spanning both physics and computer science. As the name implies, the field extends information processing (including computing and cryptography) to physical regimes where quantum effects become significant. QIP is also the name of the largest annual conference in the field, with around 1000 attendees and 500 submissions (as of 2023). Check the website [QIP](https://qipconference.org/)
- [QIP 2023](https://www.youtube.com/@qip2023) : Watch the lecture videos of QIP 2023 [here](https://www.youtube.com/@qip2023)
- [QIP 2024](https://www.youtube.com/@QIP2024/videos) : Watch the lecture videos of QIP 2024 [here](https://www.youtube.com/@QIP2024/videos)


- [Differential Equations](https://www.youtube.com/watch?v=9fQkLQZe3u8&list=PLMrJAkhIeNNTYaOnVI3QpH7jgULnAmvPA&index=2) : Lean about Differential Equations and Dynamical Systems. This is one of my favorite topics in all of math. And this finishes up all the videos for a two-quarter, 60 hour set of lectures on Engineering Mathematics!
- [Probability and Statistics, Harvard](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo): Statistics 110 (Probability) has been taught at Harvard University by Joe Blitzstein (Professor of the Practice in Statistics, Harvard University) each year since 2006



# MIT
The coursework offered at MIT

- [Quantum Computation](https://ocw.mit.edu/courses/18-435j-quantum-computation-fall-2003/pages/lecture-notes/) : A course by Prof. Peter Shor






# TU Delft

The courses made by TU Delft team, also available on edx

- [Quantum 101: Quantum Computing & Quantum Internet](https://online-learning.tudelft.nl/programs/quantum-computing-and-quantum-internet/): The aim of this program is to help you get up to speed with the present progress in the transition to a quantum information era. After a quick review of some of the basic concepts that will enable you to understand the operating principles of quantum computation and quantum internet, the program will begin with an extensive discussion on some of the different ways qubits can be built.

- [The Quantum Internet and Quantum Computers: How Will They Change the World?](https://online-learning.tudelft.nl/courses/the-quantum-internet-and-quantum-computers/): Discover quantum computers and the quantum internet. Learn the principles and promises behind these developments and how quantum computing and quantum information will impact our future
- [The Hardware of a Quantum Computer](https://online-learning.tudelft.nl/courses/the-hardware-of-a-quantum-computer/): Learn how a quantum computer could be physically build, and how it could be controlled.
- [Architecture, Algorithms, and Protocols of a Quantum Computer and Quantum Internet](https://online-learning.tudelft.nl/courses/architecture-algorithms-and-protocols-of-a-quantum-computer-and-quantum-internet/): Learn how a quantum computer can be operated: you will go through the basics of quantum algorithms, quantum error-correction, micro-architectures, compilers, and programming languages for quantum computing, and protocols for the quantum internet.
- [Fundamentals of Quantum Information](https://online-learning.tudelft.nl/courses/fundamentals-of-quantum-information/): Quantum information is at the heart of quantum computing: learn how it is mathematically represented via quantum circuits and how to manipulate quantum entanglement with these circuits.
- [Quantum Cryptography](https://online-learning.tudelft.nl/courses/quantum-cryptography/): Learn how quantum communication provides security that is guaranteed by the laws of nature.




# NPTEL

The course is made available freely by the online platform of NPTEL

-[Introduction to Quantum Computing: Quantum Algorithms and Qiskit, IBM and IITM](https://nptel.ac.in/courses/106106232): This course will provide introduction to Quantum Computation, starting with basic concepts such as superposition and entanglement, to discussing the quantum circuit model of computation and basic Quantum algorithms that demonstrate the power of computing with quantum bits.
 




# Individuals
This contains blog posts by individuals

- [Shtetl-Optimized](https://scottaaronson.blog/): The Blog of Scott Aaronson. If you take nothing else from this blog: quantum computers won't solve hard problems instantly by just trying all solutions in parallel.

- [Zlatko Minev's Blogs](https://www.zlatko-minev.com/blog): He is the technical lead and manager of the following  groups at IBM Quantum - Qiskit Leap (quantum computing research) and Qiskit Metal (quantum hardware). His background is in experimental and theoretical quantum computing, software, and fundamental and applied physics.

- [Quantum Error Correction by Zlatko Minev](https://www.zlatko-minev.com/blog/quantum-error-mitigation-bss23) : Quantum Error Mitigation: Lectures at the Boulder School for Condensed Matter and Materials Physics

- [Musty Thoughts by Michal](https://www.mustythoughts.com/): Michal is a quantum software engineer. He's interested in resource estimation, optimization, data visualization and research process (among others). He uses this blog as a platform to write about the topics that he find worth writing about :) Right now he is focused on quantum computing, but you can expect occasional articles on other topics.

- [Quantum Algorithms](https://quantumalgorithms.org/) : The aim of this book is twofold:  First, we want to bridge the gap between introductory material in quantum computation and research material.
    Second, you should be able to use this book as a resource for state-of-the-art algorithms. Readers and scholars should find statements of theorems (along with their citations) and runtimes of the best quantum subroutines in literature, ready to be used in new quantum algorithms or applications.


- [Peter Shor's Lecture Notes](https://math.mit.edu/~shor/435-LN/) : Lecture Notes for 8.370/18.435 Quantum Computation from Fall 2022

- [Quantum Computation Course by John Preskill](http://theory.caltech.edu/~preskill/) : Ph/CS 219A is the first term in a three-term course on quantum computation and quantum information science. Topics covered in 219A include density operators, quantum operations, quantum entanglement, quantum circuits, and quantum algorithms
- [Quantum Computation by Umesh Vazirani](https://people.eecs.berkeley.edu/~vazirani/quantum.html) : CS294-2: Quantum Computation
- [Quantum Computing Lecture Notes by Ronald De Wolfe](https://arxiv.org/abs/1907.09415) : This is a set of lecture notes suitable for a Master's course on quantum computation and information from the perspective of theoretical computer science. The first version was written in 2011, with many extensions and improvements in subsequent years. The first 10 chapters cover the circuit model and the main quantum algorithms (Deutsch-Jozsa, Simon, Shor, Hidden Subgroup Problem, Grover, quantum walks, Hamiltonian simulation and HHL)








# Github

- [Learn CS](https://github.com/ossu/computer-science): Path to free self-taught education in Computer Science!






# Community Forums

Engaging with the quantum computing community can enhance your learning experience. Here are some community forums where you can ask questions and connect with experts:

- [Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/): A question-and-answer platform dedicated to quantum computing.

- [Quantum Computing Reddit](https://www.reddit.com/r/QuantumComputing/): A subreddit where you can find discussions, news, and resources related to quantum computing.

# Blogs and Newsletters

Blogs and newsletters are great for staying up-to-date with the latest developments in quantum computing. Here are some resources to follow:

- [Quantum Computing Report](https://quantumcomputingreport.com/): A website that provides news, analysis, and reports on quantum computing.

- [Quantum Zeitgeist](https://quantumzeitgeist.com/): A newsletter that summarizes the latest happenings in the world of quantum computing.

Feel free to contribute to this repository by suggesting additional resources or improvements to the existing list. Happy learning!

