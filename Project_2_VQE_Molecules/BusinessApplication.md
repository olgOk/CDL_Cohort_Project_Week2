![CDL 2020 Cohort Project](../figures/CDL_logo.jpg)

# Quantum Cohort Project Business Application

This week our team has explored the Variational Quantum Eigensolver (VQE) for constructing potential energy surfaces for small molecules. Our main goal in the project was to illustrate main steps of the VQE framework using small molecules of increasing computational difficulty. In addition, we want to compare classical techniques of creating VQE algorithms.


## Overview.
The million dollar question that can be asked around the future of quantum computing is what potential applications can be tackled with this breakthrough technology. Nowadays, we are in an era of quantum computing where devices are noisy and to a certain extent unreliable for useful and relevant computations. However, we investigated how we could use in a very near future hybrid classical quantum algorithms such as the Variational Quantum Eigensolver to handle critical applications such as drugs synthesis or material science. The advantage of those algorithms is essentially the ability to harness at the same time the power of both a quantum computer and a classical computer by combining their use into an efficient feedback loop mechanism. This allows us to derive molecular properties that could help us discover new types of metal alloys to create efficient high temperature superconductors, facilitating the electricity transport (and its associated electric energy) for smart power grids, but also for new batteries that do necessitate alloys being able to store a lot of energy. One could also think about using this method for active principles detection in drug synthesis allowing the tackling of all kinds of diseases.


## Q&A #1: What is the purpose of the analysis here?

The analysis conducted here is the performance investigation of the variational quantum eigensolver (VQE) as a variational quantum algorithm dedicated to the simulation of molecules. What we want to check is if the results provided by the algorithms do yield same or better (in the sense of more accurate) results than classical computation for small molecules. This analysis will allow us to specify if this algorithm could demonstrate a significant and reliable advantage for simulations of larger molecules which are not tractable by classical computation due to the amount of data that has to be processed. Typically, we try out different methods in order to yield the best possible results for molecules of LiH and H4. We also extend the analysis in order to find out the first excited states of those molecules on top of their ground state, by adjusting the original VQE implementation.


## Q&A #2: How do the VQE and QAOA methods provide an advantage over classical machine learning methods?

VQE & QAOA are both constituents of a class of  algorithms that are called variational quantum algorithms. The interest of these kind of methods is to use simultaneously the power of the quantum computer and the flexibility of classical computation in order to handle problem instances of  sheer sizes (in terms of the data that has to be handled). The advantage over classical methods could come from the fact that, under the assumption that these methods do same or better quality of results on datasets that are handled well by classical computers today, they would be able to handle much more problem instances that are intractable due to the curse of dimensionality associated to the data that has to be dealt with.

## Q&A #3: How do these methods help in discovering new molecules?

By simulating at the lowest scale (electrons, nuclei, etc…) the molecular structure, one can develop a set of tools allowing us to determine a set of useful properties associated to certain compounds or materials. Typically, one could imagine to find high temperature superconductivity by identifying new set of alloys that couldn’t be imagined by the usual experimental research. The ability to play on the ground structure of the molecules allows the reconstruction of all kinds of different macroscopic properties, the same reasoning might apply for active principle in a chemical compound for the design of drugs.

## Q&A #4: Who would be interested to invest in this technology?.

Typically, if one thinks about the urgent questions related to energy storage or energy transport, one could directly think about ABB, striving to develop smarter grids for electricity distribution. The national electrical company EDF in France would also be a good candidate for this technology, as their ambition is to move away slowly from electricity production of nuclear power plants towards renewable energies that could deal with significant increase of yield using opportunities associated to this technology.

## Q&A #5: Is it possible to evaluate physical properties of these molecules computationally? 
Two quantities of interest that we could hope to derive in the very near future with the help of VQE are essentially the Density of states, which correspond to the distribution of occupied quantum states according to their associated energies (which helps figuring out the configuration of orbitals and therefore the behavior of valence electrons for potential resistivity measurements), and the chemical response under external constraints such as variations of temperature or pressure. 
