# Motif-Finding_Gibbs-Sampler<br />
Gibbs sampling (also called alternating conditional sampling) is a Markov Chain Monte Carlo algorithm for high-dimensional data.<br />
GibbsSampler is a motif finding algorithm that finds one common motif and returns a list of bestMotifs containing the closest motif match from each string in dna.<br />
##Problem Statement<br />
Given: Integers k, t, and N, followed by a collection of strings Dna.<br />
Return: The strings BestMotifs resulting from running GibbsSampler(Dna, k, t, N)   with 20 random starts.<br />
We have to code Gibbs Sampler for the purpose of motif discovery. Here,<br />
Dna -- A collection of DNA strings that are of the same length.<br />
"t" -- Is an integer indicating how many times to read the genetic algorithm.<br />
"k" -- An integer indicating the motif length being searched for.<br />
"N" -- The number of iterations before returning the best motif.<br />
