# Deep-Learning Based Language Emergence Experiments

Here are pointers to repos for our papers that work on language emergence using deep-learning agents.

### [Compositionality with Variation Reliably Emerges Between Neural-Networks](https://openreview.net/pdf?id=-Yzz6vlX7V-)
#### Henry Conklin, Kenny Smith (ICLR 2023)

Code: [https://github.com/hcoxec/variable_compositionality](https://github.com/hcoxec/variable_compositionality)

Summary: We re-evaluated how to look for compositional structure, in response to recent work claiming compositionality isn’t needed for generalization. While natural languages are compositional they’re also rich with variation – by introducing 4 explicit measures of variation, we showed that models reliably converge to compositional representations just with a degree of variation that skewed previous measures. We also showed that at the start of training variation correlates strongly with generalization – but that this effect goes away as representations become regular enough for the task. Converging to highly-variable representations is similar to what we see in human languages, and in a final set of experiments we show that model capacity, thought to condition variation in human language, has a similar conditioning effect with neural networks.


### [Anaphoric Structure Emerges Between Neural Networks](https://escholarship.org/content/qt6qf6251k/qt6qf6251k.pdf)
#### Nicholas Edwards, Hannah Rohde, Henry Conklin (CogSci 2023)

Code: [https://github.com/hcoxec/anaphors](https://github.com/hcoxec/anaphors)

Summary: Anaphors are ubiquitous in human language; structures like pronouns and ellipsis are present in virtually every language. This is in spite of the fact that they seem to introduce ambiguity – “they left a parcel for you” could refer to virtually anyone, and needs to be disambiguated by context. Many accounts of why anaphors exist are tied to efficiency: they enable brevity which lowers the effort of communicating. We show that anaphoric structures emerge between communicating neural networks whether or not there’s any pressure for efficiency, with efficiency pressures increasing the prevalence of anaphoric structures already present. Pointing to the relationship between semantics and pragmatics – rather than efficency – as a major causal factor.

