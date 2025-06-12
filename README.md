SARS-CoV-2 Evolution Simulation
1.Overview
This project simulates the evolutionary process of the SARS-CoV-2 genome using a genetic algorithm. The goal is to study how mutations accumulate over generations, how they affect fitness, and how evolutionary relationships are visualized through phylogenetic trees.
2. Workflow
1.	Install bio python and matplotlib.
2.	In the simulation loop just load the reference genome in FASTA format.
3.	Run the project 
3.Key Functions
1. load_reference_genome(filepath)
•	Loads the reference genome from a FASTA file.
2. initialize_population(reference_genome, population_size, mutation_rate)
•	Creates an initial population of genomes with random mutations.
3. mutate_genome(sequence, mutation_rate)
•	Introduces mutations into a genome sequence based on the mutation rate.
4. evaluate_fitness(sequence, reference_sequence, critical_sites, mutation_weights)
•	Calculates a fitness score by penalizing mutations at critical sites.
5. select_population(population, fitness_scores, selection_size)
•	Selects genomes for reproduction based on their fitness.
6. generate_next_generation(population, mutation_rate)
•	Generates the next generation of genomes by applying mutations.
7. construct_phylogenetic_tree(population)
•	Constructs a phylogenetic tree based on evolutionary relationships.
8. visualize_tree(tree, filepath)
•	Saves and visualizes the phylogenetic tree.

 

