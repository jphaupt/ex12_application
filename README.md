# ex12_application
Exercises for a doctoral candidate position. 

Here are some things that I did _not_ do but may do later given the time. None of them are strictly necessary, but they are details that I would be interested in exploring nevertheless. 
- Part (b): check the Hückel cyclic alkene formula. Looking it up, it seems like it is essentially exactly the same as what I did in the question: fill a matrix based on nearest-neight atoms (alphas on the diagonals, betas for nearest-neighours, and 0 otherwise), and find the matrix eigenvalues (energies). This is exactly what is happening in this question anyway, so I did this already. I think the mention of Hückel theory in this question was just a sanity check that that is more or less what we are doing. 
- Part (d): maybe try to find a way to re-express the integral, or perhaps use a package like mpmath to go to further decimal places, so that we can reasonably go to higher N without getting overflow errors. 
- Show more work in parts (e) and (g). This is just busywork, and is done in any standard statistical mechanics textbook. 
- The N comes from the split operator method. By my understanding, this partition function was for a single oscillator? Is that right? (i.e. there is no N when calculating the quantum or classical cases) Seems to be right based on the numerics.  
