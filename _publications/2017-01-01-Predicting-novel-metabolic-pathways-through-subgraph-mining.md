---
title: "Predicting novel metabolic pathways through subgraph mining"
collection: publications
permalink: /publication/2017-01-01-Predicting-novel-metabolic-pathways-through-subgraph-mining
type: journal
date: 2017-01-01
venue: 'Bioinformatics'
paperurl: '../files/ReactionMiner-Bioinformatics2017.pdf'
authors: '<strong>Aravind Sankar</strong>, Sayan Ranu, Karthik Raman'
url: 'https://doi.org/10.1093/bioinformatics/btx481'
abstract: 'Motivation: The ability to predict pathways for biosynthesis of metabolites is very important in metabolic engineering. It is possible to mine the repertoire of biochemical transformations from reaction databases, and apply the knowledge to predict reactions to synthesize new molecules. However, this usually involves a careful understanding of the mechanism and the knowledge of the exact bonds being created and broken. There is a need for a method to rapidly predict reactions for synthesizing new molecules, which relies only on the structures of the molecules, without demanding additional information such as thermodynamics or hand-curated reactant mapping, which are often hard to obtain accurately. Results: We here describe a robust method based on subgraph mining, to predict a series of biochemical transformations, which can convert between two (even previously unseen) molecules. We first describe a reliable method based on subgraph edit distance to map reactants and products, using only their chemical structures. Having mapped reactants and products, we identify the reaction centre and its neighbourhood, the reaction signature, and store this in a reaction rule network. This novel representation enables us to rapidly predict pathways, even between previously unseen molecules. We demonstrate this ability by predicting pathways to molecules not present in the KEGG database. We also propose a heuristic that predominantly recovers natural biosynthetic pathways from amongst hundreds of possible alternatives, through a directed search of the reaction rule network, enabling us to provide a reliable ranking of the different pathways. Our approach scales well, even to databases with >100 000 reactions. Supplementary information: Supplementary data are available at Bioinformatics online.'
code: https://github.com/RamanLab/ReactionMiner
---
