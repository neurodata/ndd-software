# Current Development Status of Each Package

## Oblique Trees
* Current state: being implemented into `scikit-learn`
* POC: Adam Li, Jong Shin
* Checklists
    - [x] TC benchmarking on simulation data
    - [x] Cohen's Kappa benchmarking on cc18 suites
    - [x] Iris benchmarking tutorial
        - [x] update documentation
        - [x] add OT functionality to sklearn benchmark script `plot_iris_dtc.py`
    - [ ] Simulation benchmarking tutorial
        - [x] visualize simulation data
        - [x] choose one simulation and limit runtime under 30 seconds
        - [ ] use absolute value of the plot in addition to the delta plot (OF minus RF)
    - [ ] MNIST benchmarking tutorial
        - [x] multi-class one vs rest ROC curve
        - [x] printout performance over 10 CV for sqrt and n_features
        - [ ] perform grid/random serach over `max_features` and `n_estimators`
    - [ ] Pickle trained trees/forests and assess time complexity/memory and performance trade-offs (can be sotred as a pandas dataframe)
        * Pickle dump with protocol-5 to measure the length of the string
* Reference: [Final PR](https://github.com/scikit-learn/scikit-learn/pull/22754), [Local PR](https://github.com/neurodata/scikit-learn/pull/21), [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/20819), [TEST PR](https://github.com/neurodata/scikit-learn/pull/11), [Paper](https://arxiv.org/pdf/1506.03410.pdf)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Oblique%20Trees.svg?raw=true">

## Graph Spectral Embedding
* Current state: being implemented into `scikit-learn`
* POC: Jong Shin
* Checklists
    - [ ] Run benchmark using the same set up described in [this paper](https://doi.org/10.1109/HPEC.2017.8091045)
    - [ ] Provide more reference in the issue
* Reference: [Initial PR](https://github.com/scikit-learn/scikit-learn/pull/20029), [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/18177)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Graph%20Spectral%20Embedding.svg?raw=true">

## Streaming Trees
* Current state: being implemented into `scikit-learn`
* Checklists
    - [ ] Add `partial_fit` to `DecisionTreeClassifier`
    - [ ] Create Benchmark to show that multiple `partial_fit` roughly equates to fitting in batch
* Reference: [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/18888), [Initial PR](https://github.com/scikit-learn/scikit-learn/pull/18889), [Repo](https://github.com/neurodata/SDTF)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Streaming%20Trees.svg?raw=true">

## Honest Trees
* Current state: intial issue raised in `scikit-learn`
* Checklists
    - [ ] Produce ECE results of isotonic calibration on top of honest forest [[NDD Issue](https://github.com/neurodata/honest-forests/issues/2)]
    - [ ] Make a PR associated with the initial issue
* Reference: [Initial Issue](https://github.com/scikit-learn/scikit-learn/issues/19710), [Repo](https://github.com/neurodata/honest-forests), [Notebook](https://nbviewer.org/github/EYezerets/ProgLearn/blob/sklearnUF/docs/tutorials/honest_posteriorestimates_runtime.ipynb), [Paper](https://arxiv.org/abs/1907.00325)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Honest%20Trees.svg?raw=true">

## Binned Trees
* Current state: planning phase
* Checklists
    - [ ] Make a standalone repo for the project
    - [ ] Consult with Hao for further development
    - [ ] Create initial issue in `scikit-learn`
* Reference: [Repo](https://github.com/PSSF23/scikit-learn-stream/tree/hist)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/Binned%20Trees.svg?raw=true">

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
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/MORF.svg?raw=true">

## AutoGMM
* Current state: being implemented into `scikit-learn`
* Checklists
    - [ ] Address issues raised in the PR
    - [ ] Follow up with Jovo
* Reference: [Issue](https://github.com/scikit-learn/scikit-learn/issues/19338), [PR](https://github.com/scikit-learn/scikit-learn/pull/19562)
* Milestone
<img src="https://github.com/jshinm/neurodata-software-milestone/blob/main/output/MORF.svg?raw=true">
* [To be Updated]
* POC: tingshan

## Multivariate/Sequential Feature Selection
* Current state: brainstorming/planning
* POC: Jong Shin, CEP, Sambit Panda, Mike Powell
* Reference: [CEP's Note](202205_cep-note.md)

## Large Deformation Diffeomorphic Metric Mapping (LDDMM) (into `skimage`)
* [To be Updated]
* POC: Vikram Chandrashekhar, Devin Crowley
- [PR](https://github.com/scikit-image/scikit-image/pull/5323)