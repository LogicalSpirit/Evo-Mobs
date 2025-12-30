# Evo-Mobs
Evo-Mobs: Genetic Algorithm Framework for Minecraft
A production-ready Minecraft plugin that evolves mob movement patterns using genetic algorithms. Mobs "learn" to navigate to target locations through evolutionary selection over multiple generations.
🧬 How It Works
Genetic Algorithm Overview
The plugin implements a classic genetic algorithm with the following components:

Genotype (DNA): Each mob has a sequence of movement vectors that control its behavior
Fitness Function: Mobs are scored based on how close they get to a target location
Selection: Better-performing mobs have higher probability of reproducing
Crossover: Parent DNA sequences are combined to create offspring
Mutation: Random variations are introduced to maintain diversity
Elitism: Top performers are preserved unchanged into the next generation

🚀 Quick Start
Requirements

Java 21 (or Java 17 with minor modifications)
Paper 1.21+ (will NOT work on standard Spigot - requires Paper's Mob Goals API)
Maven for building
