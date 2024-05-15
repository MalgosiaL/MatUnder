I've started working on project A

I plan to use [PyInform](https://elife-asu.github.io/PyInform/shannon.html) library to estimate I(X,Y) and I(X,Y|Z).

So that's why I was working on preprocessing of conitinious features:
- discretization using histograms
- counting possible combination in order to estimate features distribution
(using [`pyinform.dist.Dist`](https://elife-asu.github.io/PyInform/dist.html#pyinform.dist.Dist))
- draft implementaion of IAMB algorithm

next step is to test __joint mutual information__ relevance 
