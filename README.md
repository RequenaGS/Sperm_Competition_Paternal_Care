# Sperm_Competition_Paternal_Care

Code for the study "Sperm competition games when males invest in paternal care", run in Mathematica 11.0.1.0, platform Mac OS X x86(32-bit, 64-bit Kernel)

In this study, we extend previous sperm competition games in order to incorporate male allocation to paternal effort as an additional component of males' fitness. Building on existing theory (Parker 1998; Parker and Pizzari 2010), we consider how the effect of male allocation to paternal effort on offspring survival affects the relationship between mating rate, fertilization success and paternal care. In particular, we explore between-species variation in the cost of male care, from scenarios where parental behaviour is energetically inexpensive (i.e. low allocation to paternal effort results in relatively high offspring survival) to situations where care is very costly (i.e. equivalent offspring survival requires high male allocation to care). The main goals of this study are to evaluate how variation among species in female promiscuity and the cost of male care affect (1) male allocation between obtaining matings, producing ejaculates and providing parental care, and (2) the association between paternal care and paternity that emerges as the result of male allocation between these three different components of fitness. Our findings reveal that the cost of paternal care can drive how males respond to sperm competition and whether a detectable empirical association is predicted to exist between paternity and paternal care.

Using standard methods (Otto & Day, 2007), we found the analytical solution for the evolutionarily stable allocation (ESA) strategies in four steps. First, we obtained the ESA to ejaculates by solving the partial derivative of the fitness function with respect to allocation to ejaculate production, setting the mutant male allocation to care equal to the wild male strategy, as well as the mutant male allocation to ejaculate equal to the wild male strategy and equal to the ESA allocation to ejaculate. Next, we solved the partial derivative of the fitness function with respect to allocation to paternal care, setting the mutant male allocation to care equal to the wild male strategy and equal to the ESA allocation to care.

The next step regards ensuring not only that the model is internally consistent (regarding its mathematical and logical properties), but also that it is biologically consistent (Houston & McNamara 2002, 2005). In particular, the model must respect the ‘Fisher condition’: in a diploid species with sexual reproduction, each offspring must necessarily be the result of the fertilization of one female gamete by one male gamete and each mating event must occur between a male and a female (Houston & McNamara 2002, 2005). Therefore, to ensure self-consistency in a reproducing population with 1:1 sex ratio, female and male mating rates must be the same at equilibrium. 

The fourth step checks whether the equilibrium solutions represent fitness maxima. This condition is satisfied for functions with multiple variables if the Hessian matrix has no positive eigenvalues (Otto & Day, 2007). In our model, equations 4a-c of Requena & Alonzo (in press) represent fitness maxima when females mating rate f is higher than 2, the baseline B of offspring survival without paternal care is non-negative, and the shape parameter α of the offspring survival function is higher than 10. We explore the parametric space delimited by 2 ≤ f ≤ 15, 0 ≤ B ≤ 0.8 and 10 ≤ α ≤ 80

References:

Houston AI, McNamara JM. 2002 A self–consistent approach to paternity and parental effort. Philos. Trans. R. Soc. Lond. B Biol. Sci. 357, 351–362.

Houston AI, McNamara JM. 2005 John Maynard Smith and the importance of consistency in evolutionary game theory. Biol. Philos. 20, 933–950.

Otto SP, Day T. 2007 A biologist's guide to mathematical modeling in ecology and evolution. Princeton, NJ: Princeton University Press.

Parker, G. A. 1998. Sperm competition and the evolution of ejaculates: towards a theory base. Pp. 3–54 in T. R. Birkhead, and A. P. Møller, eds. Sperm competition and sexual selection. Academic Press, New York.

Parker, G. A., and T. Pizzari. 2010. Sperm competition and ejaculate economics. Biol. Rev. 85:897–934.
