---
feature_text: |
  # <span style="color:white">The Simon Research Ensemble</span>
  We use mathematics, machine learning, and computer simulations as a toolkit to understand and solve problems.
feature_image: images/treez.jpg 
excerpt: "this is an excerpt"
---

<style>
figcaption {
    margin: 10px 0 0 0;
    font-family: Courier;
	font-size: 14px;
    color: #808080;
}
</style>

The Simon Research Ensemble resides in the School of Chemical, Biological, and Environmental Engineering ([CBEE](http://cbee.oregonstate.edu/)) at [Oregon State University](http://oregonstate.edu/). We leverage mathematics, machine learning, statistical mechanics, and computer simulations to shed light on physical phenomena ranging from porous materials with moving parts to mysterious, barren patches in arid grasslands. We aim to understand intimately and to explain clearly. The problems we approach have implications in clean energy, security, and human welfare.

<figure>
	<center>
	<img src="images/osu_logo.jpg" alt="" style="width:604px">
	</center>
</figure>

# Research topics

### Nano-porous materials

Metal-organic frameworks (MOFs) are crystalline materials that possess nano-sized pores, endowing them with enormous internal surface areas. As a consequence of their ability to selectively adsorb molecules into their pores, MOFs hold promise for many practical applications. For example, MOFs can densify hydrogen gas for onboard vehicular fuel storage, capture radioactive gases emitted during the reprocessing of used nuclear fuel, deliver therapeutic drugs, and detect vapor analytes as chemical sensors.

An exciting aspect of MOFs is their modular and versatile chemistry. In the synthesis of MOFs, metal nodes/clusters and organic linker molecules self-assemble in solution to construct a porous framework. 

<figure>
	<center>
	<img src="images/pillared_MOFs_schematic.png" alt="MOF schematic" style="width:604px">
	<figcaption>The molecular building blocks of a pillared square grid MOF are metal ions, linkers, and pillars.</figcaption>
	</center>
</figure>

By changing the chemistry of the metal nodes and linker molecules, *many* different MOFs can be synthesized.

<figure>
	<center>
	<img src="images/pillared_MOFs_building_blocks.png" alt="MOF schematic" style="width:500px">
	<figcaption>Pillared square grid MOFs have been synthesized with the shown metal ions, linkers, and pillars.</figcaption>
	</center>
</figure>

This high chemical tunability allows us to engineer MOFs with diverse properties and fine-tune existing MOF architectures to target specific guest molecules for gas storage and separations, drug delivery, catalysis, and chemical sensing. 

Many MOFs are flexible and have moving parts that respond to external stimuli, which often give rise to unique and valuable properties. 

<figure>
	<center>
	<img src="images/modes_of_flexibility.png" alt="flexible MOFs" style="width:600px">
	<figcaption>Examples of dynamic/flexible MOFs and their response to the adsorption of gas molecules (yellow balls). [Breathing] A large pore collapses upon the adsorption of gas. When more gas adsorbs, the pore opens again. [Gate-opening] Collapsed pores pop open and flood with gas molecules. [Swelling] The pore continuously swells as more gas adsorbs. [Ligand Rotation] Adsorbed gas molecules cause a swinging ligand to change its conformation.</figcaption>
	</center>
</figure>

We pose structural models that capture the essence of the flexible/dynamic degrees of freedom of a given MOF. Then, we use molecular models and statistical mechanics to study how the flexible/dynamic parts respond to external stimuli, such as heat, stress, and the adsorption of gas molecules. We make the minimal assumptions necessary to capture the experimentally observed features. Our goals are to fundamentally understand how flexible/dynamic parts in MOFs respond to different stimuli and give rise to unique properties, such as negative thermal expansion. Such insights are valuable for optimizing the chemistry of flexible/dynamic MOFs for gas storage, gas separations, drug delivery, and chemical sensing. Ideally, our models will uncover new, unexpected ways to exploit dynamic/flexible MOFs for engineering applications.

Another focus of our group is to leverage recent advances in deep learning and train neural networks to recognize optimal MOFs. Neural networks are attractive because they automatically discover features important for determining performance, negating the need for hand-engineered features.

### Self-organizing vegetation in arid landscapes

In the thirsty grasslands of Namibia, the landscape is covered by thousands of small, barren disks called fairy circles.

<figure>
	<center>
	<img src="images/namibia.jpg" alt="Fairy circles in Namibia" style="width:400px">
	<figcaption>Small, barren disks called fairy circles persist in the grasslands of Namibia.</figcaption>
	</center>
</figure>

Tune into the BBC documentary, *Africa* (S1: E1, at 3:00) [on Netflix] to listen to David Attenborough introduce fairy circles in his captivating narration. 

Fairy circles may at first appear to have little relevance in a research program in chemical engineering. To the contrary, the etiology of these striking patterns can be explained by principles of fluid flow, the theory of phase transitions, and multiple-scale analysis. Our group seeks to build a mathematical model to capture the formation and persistence of these fairy circles and understand the influence of climate on the pattern. This can help us understand and monitor how ecological systems cope with climate stress such as drought, and perhaps reveal new farming strategies in arid climates.

## The value of mathematical modeling

> Science is what we understand well enough to explain to a computer. Art is everything else we do. :microphone: Donald Knuth

We use mathematics and computer simulations to shed light on physical phenomena. The formalism of mathematics allows for a clear conceptualization of the phenomenon at hand. Mathematical models can reduce dauntingly complex physical processes to their core ingredients [[Ringrose and Howard](https://doi.org/10.1016/j.coisb.2017.02.003)]. Modeling is a means to identify underlying structure in the physical world and, from an engineering perspective, elucidate how to manipulate/harness/exploit physics to benefit humanity.

> If people do not believe that mathematics is simple, it is only because they do not realize how complicated life is. :microphone: John von Neumann

Great satisfaction can be found in expressing how something works in a mathematical framework. The insights that follow are often rich, unexpected, and beautiful.

> To those who do not know mathematics, it is difficult to get across a real feeling as to the beauty, the deepest beauty, of nature. :microphone: Richard Feynman

We frequently approach poorly understood problems with parsimonious, but illuminating models.

> Make things as simple as possible, but not simpler. :microphone: Albert Einstein

> Now it would be very remarkable if any system existing in the real world could be exactly represented by any simple model. However, cunningly chosen parsimonious models often do provide remarkably useful approximations. For example, the law PV = RT relating pressure P, volume V and temperature T of an ideal gas via a constant R is not exactly true for any real gas, but it frequently provides a useful approximation and furthermore its structure is informative since it springs from a physical view of the behavior of gas molecules. For such a model there is no need to ask the question “Is the model true?”. If “truth” is to be the “whole truth” the answer must be “No”. The only question of interest is “Is the model illuminating and useful?”. :microphone: George Box

For processes where the physics are well-understood, we employ _predictive_ models, where we attempt to model as much of the physics as the accuracies of current models permit. One might argue that the development of predictive models has the most lucid impact; imagine if a molecular model were so accurate that we could design the optimal nanoporous material for hydrogen storage on a computer. However, rarely are molecular models so accurate, and typically the most accurate models are computationally infeasible. Still, predictive models are often capable of capturing qualitative differences between materials, generating statistically reliable performance rankings of a set of materials, or elucidating trends/design rules.
