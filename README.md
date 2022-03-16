# Discrete Probability Detector (DPD)

This application uses an algorithm that transforms any sequence of symbols into a transition matrix. The algorithm may receive special characters from the entire ASCII range. These characters can be letters, numbers or special characters (ie. <kbd>`7S@%#u9f$*"</kbd>). The number of symbol/character types that make up a string, represent the number of states in a Markov chain. Thus, DPD is able to detect the number of states from the sequence and calculate the transition probabilities between these states. The final result of the algorithm is represented by a transition matrix (square matrix) which contains the transition probabilities between these symbol types (or states). The transition matrix can be further used for different prediction methods, such as Markov chains or Hidden Markov Models. This version of DPD is made in <kbd>HTML/JavaScript/CSS</kbd>.

# Live demo

https://gagniuc.github.io/Discrete-Probability-Detector-JS/

# Screenshot

<kbd><img src="https://github.com/Gagniuc/Discrete-Probability-Detector-JS/blob/main/img/Discrete%20Probability%20Detector.png?raw=true" /></kbd>

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>

