# Current Development Status of Each Package

## Oblique Trees
* Current state: being implemented into `scikit-learn`
* Checklists
    - [x] TC benchmarking on simulation data
    - [x] Cohen's Kappa benchmarking on cc18 suites
    - [ ] Iris benchmarking tutorial
    - [ ] Simulation benchmarking tutorial
    - [ ] MNIST benchmarking tutorial
* Reference: [Final PR](https://github.com/scikit-learn/scikit-learn/pull/22754), [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/20819), [TEST PR](https://github.com/neurodata/scikit-learn/pull/11), [Paper](https://arxiv.org/pdf/1506.03410.pdf)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Oblique%20Trees.jpg?raw=true">

## Graph Spectral Embedding
* Current state: being implemented into `scikit-learn`
* Checklists
    - [ ] Run benchmark using the same set up described in [this paper](https://doi.org/10.1109/HPEC.2017.8091045)
    - [ ] Provide more reference in the issue
* Reference: [Initial PR](https://github.com/scikit-learn/scikit-learn/pull/20029), [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/18177)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Graph%20Spectral%20Embedding.jpg?raw=true">

## Streaming Trees
* Current state: being implemented into `scikit-learn`
* Checklists
    - [ ] Add `partial_fit` to `DecisionTreeClassifier`
    - [ ] Create Benchmark to show that multiple `partial_fit` roughly equates to fitting in batch
* Reference: [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/18888), [Initial PR](https://github.com/scikit-learn/scikit-learn/pull/18889), [Repo](https://github.com/neurodata/SDTF)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Streaming%20Trees.jpg?raw=true">

## Honest Trees
* Current state: intial issue raised in `scikit-learn`
* Checklists
    - [ ] Produce ECE results of isotonic calibration on top of honest forest [[NDD Issue](https://github.com/neurodata/honest-forests/issues/2)]
    - [ ] Make a PR associated with the initial issue
* Reference: [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/19710), [Repo](https://github.com/neurodata/honest-forests), [Notebook](https://nbviewer.org/github/EYezerets/ProgLearn/blob/sklearnUF/docs/tutorials/honest_posteriorestimates_runtime.ipynb), [Paper](https://arxiv.org/abs/1907.00325)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Honest%20Trees.jpg?raw=true">

## Binned Trees
* Current state: planning phase
* Checklists
    - [ ] Make a standalone repo for the project
    - [ ] Consult with Hao for further development
    - [ ] Create initial issue in `scikit-learn`
* Reference: [Repo](https://github.com/PSSF23/scikit-learn-stream/tree/hist)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Binned%20Trees.jpg?raw=true">

## MORF
* Current state: planning phase
* Comments
    - The MORF will have much better visibility from `scikit-learn` if developed as an off-shoot once oblique tree is merged
* Checklists
    - [ ] Merge Oblique Tree PR
    - [ ] Devise plan with Adam Li
    - [ ] Create an issue
* Reference: [Repo]()
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/MORF.jpg?raw=true">

## AutoGMM
* [To be Updated]

## Multivariate Feature Selection
* [To be Updated]