##What's the problem?

* Highlight current deficiencies in ROOT with Python.
* Show concrete examples of "gotchas" and awkward code.
* Ad hoc workarounds implemented by many.
* Lack of integration with other powerful scientific Python packages.



##Introducing rootpy

* What rootpy is.
* What rootpy is not.
* Show how rootpy improves the examples shown in the previous section.



##What does rootpy offer?

Main body of talk here. Need to keep it brief and concise.

* trees
* plotting
* matplotlib interface
* memory management
* context managers
* root_numpy
* etc.



##The future of rootpy

* Larger documentation coverage. This is important!
* More code examples.
* Automatic wrapping of ROOT methods by parsing method signatures:
   - If a method expects a TColor, rootpy can accept any matplotlib/ROOT color
     and convert it into a TColor before passing to the ROOT method.
   - Reduce the amount of code in rootpy.
* TMVA:
   - Feed TMVA NumPy arrays instead of TTrees. 
* RooFit and RooStats:
   - Wrap RooArgSet as set() and RooArgList as list()...
   - Create RooDataSets from NumPy arrays.



##How can I contribute?

* We use Git! Development is community-driven.
* Just fork rootpy into your own GitHub account and:
    
        git clone git@github.com:[username]/rootpy.git
  Then submit a pull request with your contribution.
* Contributions are reviewed by peers before merging into the main branch.
* All new code is automatically tested against our test suite using
  [Travis CI](https://travis-ci.org/).
