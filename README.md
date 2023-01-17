# molsim-ml-code-examples
Code examples used in the ML course of the MolSim winterschool


## Contents 

All folders contain two versions of the same notebook. One "filled" and one with empty cells, to fill in with the class.

- [importance-of-invariance](./importance-of-invariance/) gives a basic example of why it is important to encode molecular geometries in a translationally/permutationally/rotationally invariant fashion.
   For this, we get conformer energies and train a model to predict the energy given the structure.
   We use the [Merck Molecular Force Field](https://en.wikipedia.org/wiki/Merck_molecular_force_field)
- [lr-gradient-descent](./lr-gradient-descent/) implements linear regression using gradient descent using Jax
- [bias-variance-tradeoff](./bias-variance-tradeoff/) shows some examples of under/overfitting and the utility of incorporating prior knowledge. 
  For this, we fit different functions to noisy data sampled from a LJ potential.


## Notes 

- If you are using this in class, remember to turn Copilot off, as it will directly will in all the code and give you no time to ask students for ideas.
- If you are running on battery, some of the operations can be slow if you use battery saver mode
- Visualizing the conformers requires a running pymol server. You can run one using `pymol -R`
- When projecting the notebooks, you should increase your font size by a lot and probably use a light color theme
## Acknowledgments

- The content on gradient descent is very inspired by Andrey Karparthy's content:
  - [A Hacker's guide to Neural Nets](http://karpathy.github.io/neuralnets/)
  - [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html)

  and by [Andrew White's book](https://github.com/whitead/dmol-book).