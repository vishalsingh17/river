---
hide:
- navigation
---


# Benchmarks

## Environment

<pre>Python implementation: CPython
Python version       : 3.9.12
IPython version      : 7.30.1

river       : 0.12.1
numpy       : 1.22.3
scikit-learn: 1.1.0
pandas      : 1.4.1
scipy       : 1.9.0

Compiler    : Clang 12.0.1 
OS          : Darwin
Release     : 21.5.0
Machine     : x86_64
Processor   : i386
CPU cores   : 8
Architecture: 64bit
</pre>

<div>
  <link href="https://unpkg.com/tabulator-tables@5.2.6/dist/css/tabulator.min.css" rel="stylesheet">
  <script src="https://unpkg.com/tabulator-tables@5.2.6/dist/js/tabulator.min.js" type="text/javascript"></script>
</div>

<script>
        let baseColumns
        let metrics
        let columns
        </script>

## Binary classification

### Results

<div id="binary-classification-results"></div>

### Datasets

<details>
  <summary>Bananas</summary>
  <pre>Bananas dataset.

An artificial dataset where instances belongs to several clusters with a banana shape.
There are two attributes that correspond to the x and y axis, respectively.

    Name  Bananas                                                   
    Task  Binary classification                                     
 Samples  5,300                                                     
Features  2                                                         
  Sparse  False                                                     
    Path  /Users/mastelini/Documents/river/river/datasets/banana.zip</pre>
</details>

<details>
  <summary>Phishing</summary>
  <pre>Phishing websites.

This dataset contains features from web pages that are classified as phishing or not.

    Name  Phishing                                                       
    Task  Binary classification                                          
 Samples  1,250                                                          
Features  9                                                              
  Sparse  False                                                          
    Path  /Users/mastelini/Documents/river/river/datasets/phishing.csv.gz</pre>
</details>

### Models

<details>
  <summary>ADWIN Bagging</summary>
  <pre>[HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)]</pre>
</details>

<details>
  <summary>ALMA</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  ALMAClassifier (
    p=2
    alpha=0.9
    B=1.111111
    C=1.414214
  )
)</pre>
</details>

<details>
  <summary>AdaBoost</summary>
  <pre>[HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)]</pre>
</details>

<details>
  <summary>Adaptive Random Forest</summary>
  <pre>[]</pre>
</details>

<details>
  <summary>Bagging</summary>
  <pre>[HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
)]</pre>
</details>

<details>
  <summary>Extremely Fast Decision Tree</summary>
  <pre>ExtremelyFastDecisionTreeClassifier (
  grace_period=200
  max_depth=inf
  min_samples_reevaluate=20
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)</pre>
</details>

<details>
  <summary>Hoeffding Adaptive Tree</summary>
  <pre>HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=True
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=42
)</pre>
</details>

<details>
  <summary>Hoeffding Tree</summary>
  <pre>HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)</pre>
</details>

<details>
  <summary>Leveraging Bagging</summary>
  <pre>[HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)]</pre>
</details>

<details>
  <summary>Logistic regression</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  LogisticRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.005
      )
    )
    loss=Log (
      weight_pos=1.
      weight_neg=1.
    )
    l2=0.
    l1=0.
    intercept_init=0.
    intercept_lr=Constant (
      learning_rate=0.01
    )
    clip_gradient=1e+12
    initializer=Zeros ()
  )
)</pre>
</details>

<details>
  <summary>Naive Bayes</summary>
  <pre>GaussianNB ()</pre>
</details>

<details>
  <summary>PyTorch logistic regression</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  PyTorchBinaryClassifier (
    network_func=&lt;class '__main__.PyTorchLogReg'&gt;
    loss=BCELoss()
    optimizer_func=&quot;&lt;lambda&gt;&quot;
  )
)</pre>
</details>

<details>
  <summary>Stacking</summary>
  <pre>[Pipeline (
  StandardScaler (
    with_std=True
  ),
  SoftmaxRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=CrossEntropy (
      class_weight={}
    )
    l2=0
  )
), GaussianNB (), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), Pipeline (
  StandardScaler (
    with_std=True
  ),
  KNNClassifier (
    n_neighbors=5
    window_size=100
    min_distance_keep=0.
    weighted=True
    cleanup_every=0
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
    softmax=False
  )
)]</pre>
</details>

<details>
  <summary>Stochastic Gradient Tree</summary>
  <pre>SGTClassifier (
  delta=1e-07
  grace_period=200
  init_pred=0.
  max_depth=inf
  lambda_value=0.1
  gamma=1.
  nominal_attributes=[]
  feature_quantizer=StaticQuantizer (
    n_bins=64
    warm_start=100
    buckets=None
  )
)</pre>
</details>

<details>
  <summary>Streaming Random Patches</summary>
  <pre>SRPClassifier (
  model=HoeffdingTreeClassifier (
    grace_period=50
    max_depth=inf
    split_criterion=&quot;info_gain&quot;
    delta=0.01
    tau=0.05
    leaf_prediction=&quot;nba&quot;
    nb_threshold=0
    nominal_attributes=None
    splitter=GaussianSplitter (
      n_splits=10
    )
    binary_split=False
    max_size=100.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
  )
  n_models=10
  subspace_size=0.6
  training_method=&quot;patches&quot;
  lam=6
  drift_detector=ADWIN (
    delta=1e-05
  )
  warning_detector=ADWIN (
    delta=0.0001
  )
  disable_detector=&quot;off&quot;
  disable_weighted_vote=False
  seed=None
  metric=Accuracy (
    cm=ConfusionMatrix (
      classes=[]
    )
  )
)</pre>
</details>

<details>
  <summary>Voting</summary>
  <pre>VotingClassifier (
  models=[Pipeline (
  StandardScaler (
    with_std=True
  ),
  SoftmaxRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=CrossEntropy (
      class_weight={}
    )
    l2=0
  )
), GaussianNB (), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), Pipeline (
  StandardScaler (
    with_std=True
  ),
  KNNClassifier (
    n_neighbors=5
    window_size=100
    min_distance_keep=0.
    weighted=True
    cleanup_every=0
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
    softmax=False
  )
)]
  use_probabilities=True
)</pre>
</details>

<details>
  <summary>Vowpal Wabbit logistic regression</summary>
  <pre>VW2RiverClassifier ()</pre>
</details>

<details>
  <summary>[baseline] Last Class</summary>
  <pre>NoChangeClassifier ()</pre>
</details>

<details>
  <summary>k-Nearest Neighbors</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  KNNClassifier (
    n_neighbors=5
    window_size=100
    min_distance_keep=0.
    weighted=True
    cleanup_every=0
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
    softmax=False
  )
)</pre>
</details>

<details>
  <summary>sklearn SGDClassifier</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  SKL2RiverClassifier (
    estimator=SGDClassifier(eta0=0.005, learning_rate='constant', loss='log_loss',
                penalty='none')
    classes=[False, True]
  )
)</pre>
</details>

<script>
    var results = [{'Accuracy': 0.888, 'Dataset': 'Phishing', 'F1': 0.8722627737226277, 'Memory': 5835, 'Model': 'Logistic regression', 'Time': 43.723}, {'Accuracy': 0.5430188679245282, 'Dataset': 'Bananas', 'F1': 0.19534883720930235, 'Memory': 4447, 'Model': 'Logistic regression', 'Time': 108.259}, {'Accuracy': 0.8264, 'Dataset': 'Phishing', 'F1': 0.8117953165654813, 'Memory': 4803, 'Model': 'ALMA', 'Time': 39.761}, {'Accuracy': 0.5064150943396226, 'Dataset': 'Bananas', 'F1': 0.4825949367088608, 'Memory': 3063, 'Model': 'ALMA', 'Time': 101.924}, {'Accuracy': 0.8232, 'Dataset': 'Phishing', 'F1': 0.8141295206055509, 'Memory': 3911518, 'Model': 'Stochastic Gradient Tree', 'Time': 289.019}, {'Accuracy': 0.6575471698113208, 'Dataset': 'Bananas', 'F1': 0.560639070442992, 'Memory': 2186974, 'Model': 'Stochastic Gradient Tree', 'Time': 373.299}, {'Accuracy': 0.8888, 'Dataset': 'Phishing', 'F1': 0.8753363228699551, 'Memory': 7211, 'Model': 'sklearn SGDClassifier', 'Time': 162.187}, {'Accuracy': 0.5466037735849056, 'Dataset': 'Bananas', 'F1': 0.20509427720807144, 'Memory': 5767, 'Model': 'sklearn SGDClassifier', 'Time': 618.006}, {'Accuracy': 0.8896, 'Dataset': 'Phishing', 'F1': 0.8763440860215054, 'Memory': 22362, 'Model': 'PyTorch logistic regression', 'Time': 126.001}, {'Accuracy': 0.5464150943396227, 'Dataset': 'Bananas', 'F1': 0.205026455026455, 'Memory': 20974, 'Model': 'PyTorch logistic regression', 'Time': 419.818}, {'Accuracy': 0.7736, 'Dataset': 'Phishing', 'F1': 0.6697782963827306, 'Memory': 678, 'Model': 'Vowpal Wabbit logistic regression', 'Time': 40.759}, {'Accuracy': 0.5513207547169812, 'Dataset': 'Bananas', 'F1': 0.0, 'Memory': 678, 'Model': 'Vowpal Wabbit logistic regression', 'Time': 122.834}, {'Accuracy': 0.8847077662129704, 'Dataset': 'Phishing', 'F1': 0.8714285714285714, 'Memory': 12021, 'Model': 'Naive Bayes', 'Time': 61.54}, {'Accuracy': 0.6152104170598226, 'Dataset': 'Bananas', 'F1': 0.4139120436907157, 'Memory': 3901, 'Model': 'Naive Bayes', 'Time': 146.625}, {'Accuracy': 0.8799039231385108, 'Dataset': 'Phishing', 'F1': 0.8605947955390334, 'Memory': 43202, 'Model': 'Hoeffding Tree', 'Time': 80.634}, {'Accuracy': 0.6421966408756369, 'Dataset': 'Bananas', 'F1': 0.5034049240440022, 'Memory': 24822, 'Model': 'Hoeffding Tree', 'Time': 149.084}, {'Accuracy': 0.8742994395516414, 'Dataset': 'Phishing', 'F1': 0.8560953253895509, 'Memory': 53712, 'Model': 'Hoeffding Adaptive Tree', 'Time': 111.592}, {'Accuracy': 0.6165314210228345, 'Dataset': 'Bananas', 'F1': 0.42824985931344967, 'Memory': 37552, 'Model': 'Hoeffding Adaptive Tree', 'Time': 272.604}, {'Accuracy': 0.8879103282626101, 'Dataset': 'Phishing', 'F1': 0.8734177215189873, 'Memory': 132189, 'Model': 'Extremely Fast Decision Tree', 'Time': 771.197}, {'Accuracy': 0.6252123042083412, 'Dataset': 'Bananas', 'F1': 0.4513812154696133, 'Memory': 29581, 'Model': 'Extremely Fast Decision Tree', 'Time': 181.077}, {'Accuracy': 0.9087269815852682, 'Dataset': 'Phishing', 'F1': 0.8969258589511755, 'Memory': 1460161, 'Model': 'Adaptive Random Forest', 'Time': 795.114}, {'Accuracy': 0.8856387997735422, 'Dataset': 'Bananas', 'F1': 0.8696213425129088, 'Memory': 8567505, 'Model': 'Adaptive Random Forest', 'Time': 3409.983}, {'Accuracy': 0.911929543634908, 'Dataset': 'Phishing', 'F1': 0.9005424954792043, 'Memory': 2374448, 'Model': 'Streaming Random Patches', 'Time': 1979.631}, {'Accuracy': 0.8741271938101529, 'Dataset': 'Bananas', 'F1': 0.8571428571428571, 'Memory': 4286571, 'Model': 'Streaming Random Patches', 'Time': 7089.395}, {'Accuracy': 0.8670936749399519, 'Dataset': 'Phishing', 'F1': 0.847985347985348, 'Memory': 74903, 'Model': 'k-Nearest Neighbors', 'Time': 287.36}, {'Accuracy': 0.8484619739573505, 'Dataset': 'Bananas', 'F1': 0.8274231678486997, 'Memory': 43915, 'Model': 'k-Nearest Neighbors', 'Time': 619.971}, {'Accuracy': 0.8935148118494796, 'Dataset': 'Phishing', 'F1': 0.8792007266121706, 'Memory': 416497, 'Model': 'ADWIN Bagging', 'Time': 845.887}, {'Accuracy': 0.6259671636157765, 'Dataset': 'Bananas', 'F1': 0.44821826280623617, 'Memory': 164085, 'Model': 'ADWIN Bagging', 'Time': 1592.132}, {'Accuracy': 0.8783026421136909, 'Dataset': 'Phishing', 'F1': 0.8635547576301617, 'Memory': 293807, 'Model': 'AdaBoost', 'Time': 921.577}, {'Accuracy': 0.6778637478769579, 'Dataset': 'Bananas', 'F1': 0.64504054897068, 'Memory': 171959, 'Model': 'AdaBoost', 'Time': 1512.784}, {'Accuracy': 0.8935148118494796, 'Dataset': 'Phishing', 'F1': 0.8792007266121706, 'Memory': 497232, 'Model': 'Bagging', 'Time': 984.982}, {'Accuracy': 0.6340819022457067, 'Dataset': 'Bananas', 'F1': 0.4594368553108447, 'Memory': 367092, 'Model': 'Bagging', 'Time': 2236.509}, {'Accuracy': 0.8951160928742994, 'Dataset': 'Phishing', 'F1': 0.8783658310120707, 'Memory': 1236762, 'Model': 'Leveraging Bagging', 'Time': 2740.843}, {'Accuracy': 0.8284581996603133, 'Dataset': 'Bananas', 'F1': 0.8028627195836044, 'Memory': 1243526, 'Model': 'Leveraging Bagging', 'Time': 5605.713}, {'Accuracy': 0.899119295436349, 'Dataset': 'Phishing', 'F1': 0.8866906474820143, 'Memory': 1692274, 'Model': 'Stacking', 'Time': 1615.174}, {'Accuracy': 0.8514814115870919, 'Dataset': 'Bananas', 'F1': 0.8321603753465558, 'Memory': 9988064, 'Model': 'Stacking', 'Time': 5362.456}, {'Accuracy': 0.8903122497998399, 'Dataset': 'Phishing', 'F1': 0.8769092542677449, 'Memory': 134957, 'Model': 'Voting', 'Time': 476.553}, {'Accuracy': 0.8301566333270428, 'Dataset': 'Bananas', 'F1': 0.7949886104783599, 'Memory': 76377, 'Model': 'Voting', 'Time': 1061.337}, {'Accuracy': 0.5156124899919936, 'Dataset': 'Phishing', 'F1': 0.4474885844748858, 'Memory': 535, 'Model': '[baseline] Last Class', 'Time': 17.153}, {'Accuracy': 0.5095301000188714, 'Dataset': 'Bananas', 'F1': 0.4529572721532309, 'Memory': 535, 'Model': '[baseline] Last Class', 'Time': 42.505}]

    baseColumns = [
        "Dataset",
        "Model",
        "Memory",
        "Time"
    ]
    metrics = Object.keys(results[0]).filter(x => !baseColumns.includes(x)).sort();
    columns = [...baseColumns, ...metrics].map(x => ({title: x, field: x}))

    function formatBytes(bytes, decimals = 2) {
        if (bytes === 0) return '0 Bytes'

        const k = 1024;
        const dm = decimals < 0 ? 0 : decimals;
        const sizes = ['Bytes', 'KB', 'MB', 'GB', 'TB', 'PB', 'EB', 'ZB', 'YB'];

        const i = Math.floor(Math.log(bytes) / Math.log(k));

        return parseFloat((bytes / Math.pow(k, i)).toFixed(dm)) + ' ' + sizes[i];
    }

    function msToTime(s) {
        var ms = s % 1000;
        s = (s - ms) / 1000;
        var secs = s % 60;
        s = (s - secs) / 60;
        var mins = s % 60;
        var hrs = (s - mins) / 60;

        return (
            (hrs > 0 ? hrs + 'h ' : '') +
            (mins > 0 ? mins + 'm ' : '') +
            (secs > 0 ? secs + 's' : '') +
            (ms > 0 ? ' ' + Math.round(ms) + 'ms' : '')
        )
    }

    columns.map((x, i) => {
        if (x.title === 'Dataset') {
            columns[i]["headerFilter"] = true
        }
        if (x.title === 'Model') {
            columns[i]["headerFilter"] = true
        }
        if (x.title === 'Memory') {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered){
                return formatBytes(cell.getValue())
            }
        }
        if (x.title === 'Time') {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return msToTime(cell.getValue())
            }
        }
        if (['Accuracy', 'F1', 'MacroF1', 'MicroF1'].includes(x.title)) {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return (100 * cell.getValue()).toFixed(2) + "%"
            }
        }
        if (['MAE', 'RMSE', 'R2'].includes(x.title)) {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return cell.getValue().toFixed(3)
            }
        }
    })

    new Tabulator('#binary-classification-results', {
        data: results,
        layout: 'fitColumns',
        columns: columns
    })
    </script>

## Multiclass classification

### Results

<div id="multiclass-classification-results"></div>

### Datasets

<details>
  <summary>ImageSegments</summary>
  <pre>Image segments classification.

This dataset contains features that describe image segments into 7 classes: brickface, sky,
foliage, cement, window, path, and grass.

    Name  ImageSegments                                                  
    Task  Multi-class classification                                     
 Samples  2,310                                                          
Features  18                                                             
  Sparse  False                                                          
    Path  /Users/mastelini/Documents/river/river/datasets/segment.csv.zip</pre>
</details>

<details>
  <summary>Insects</summary>
  <pre>Insects dataset.

This dataset has different variants, which are:

- abrupt_balanced
- abrupt_imbalanced
- gradual_balanced
- gradual_imbalanced
- incremental-abrupt_balanced
- incremental-abrupt_imbalanced
- incremental-reoccurring_balanced
- incremental-reoccurring_imbalanced
- incremental_balanced
- incremental_imbalanced
- out-of-control

The number of samples and the difficulty change from one variant to another. The number of
classes is always the same (6), except for the last variant (24).

      Name  Insects                                                                                 
      Task  Multi-class classification                                                              
   Samples  52,848                                                                                  
  Features  33                                                                                      
   Classes  6                                                                                       
    Sparse  False                                                                                   
      Path  /Users/mastelini/river_data/Insects/INSECTS-abrupt_balanced_norm.arff                   
       URL  http://sites.labic.icmc.usp.br/vsouza/repository/creme/INSECTS-abrupt_balanced_norm.arff
      Size  15.66 MB                                                                                
Downloaded  True                                                                                    
   Variant  abrupt_balanced                                                                         

Parameters
----------
    variant
        Indicates which variant of the dataset to load.</pre>
</details>

<details>
  <summary>Keystroke</summary>
  <pre>CMU keystroke dataset.

Users are tasked to type in a password. The task is to determine which user is typing in the
password.

The only difference with the original dataset is that the &quot;sessionIndex&quot; and &quot;rep&quot; attributes
have been dropped.

      Name  Keystroke                                                       
      Task  Multi-class classification                                      
   Samples  20,400                                                          
  Features  31                                                              
    Sparse  False                                                           
      Path  /Users/mastelini/river_data/Keystroke/DSL-StrongPasswordData.csv
       URL  http://www.cs.cmu.edu/~keystroke/DSL-StrongPasswordData.csv     
      Size  4.45 MB                                                         
Downloaded  True                                                            </pre>
</details>

### Models

<details>
  <summary>ADWIN Bagging</summary>
  <pre>[HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)]</pre>
</details>

<details>
  <summary>AdaBoost</summary>
  <pre>[HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)]</pre>
</details>

<details>
  <summary>Adaptive Random Forest</summary>
  <pre>[]</pre>
</details>

<details>
  <summary>Bagging</summary>
  <pre>[HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
), HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=False
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=None
)]</pre>
</details>

<details>
  <summary>Extremely Fast Decision Tree</summary>
  <pre>ExtremelyFastDecisionTreeClassifier (
  grace_period=200
  max_depth=inf
  min_samples_reevaluate=20
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)</pre>
</details>

<details>
  <summary>Hoeffding Adaptive Tree</summary>
  <pre>HoeffdingAdaptiveTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  bootstrap_sampling=True
  drift_window_threshold=300
  drift_detector=ADWIN (
    delta=0.002
  )
  switch_significance=0.05
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
  seed=42
)</pre>
</details>

<details>
  <summary>Hoeffding Tree</summary>
  <pre>HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)</pre>
</details>

<details>
  <summary>Leveraging Bagging</summary>
  <pre>[HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
)]</pre>
</details>

<details>
  <summary>Naive Bayes</summary>
  <pre>GaussianNB ()</pre>
</details>

<details>
  <summary>Stacking</summary>
  <pre>[Pipeline (
  StandardScaler (
    with_std=True
  ),
  SoftmaxRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=CrossEntropy (
      class_weight={}
    )
    l2=0
  )
), GaussianNB (), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), Pipeline (
  StandardScaler (
    with_std=True
  ),
  KNNClassifier (
    n_neighbors=5
    window_size=100
    min_distance_keep=0.
    weighted=True
    cleanup_every=0
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
    softmax=False
  )
)]</pre>
</details>

<details>
  <summary>Streaming Random Patches</summary>
  <pre>SRPClassifier (
  model=HoeffdingTreeClassifier (
    grace_period=50
    max_depth=inf
    split_criterion=&quot;info_gain&quot;
    delta=0.01
    tau=0.05
    leaf_prediction=&quot;nba&quot;
    nb_threshold=0
    nominal_attributes=None
    splitter=GaussianSplitter (
      n_splits=10
    )
    binary_split=False
    max_size=100.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
  )
  n_models=10
  subspace_size=0.6
  training_method=&quot;patches&quot;
  lam=6
  drift_detector=ADWIN (
    delta=1e-05
  )
  warning_detector=ADWIN (
    delta=0.0001
  )
  disable_detector=&quot;off&quot;
  disable_weighted_vote=False
  seed=None
  metric=Accuracy (
    cm=ConfusionMatrix (
      classes=[]
    )
  )
)</pre>
</details>

<details>
  <summary>Voting</summary>
  <pre>VotingClassifier (
  models=[Pipeline (
  StandardScaler (
    with_std=True
  ),
  SoftmaxRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=CrossEntropy (
      class_weight={}
    )
    l2=0
  )
), GaussianNB (), HoeffdingTreeClassifier (
  grace_period=200
  max_depth=inf
  split_criterion=&quot;info_gain&quot;
  delta=1e-07
  tau=0.05
  leaf_prediction=&quot;nba&quot;
  nb_threshold=0
  nominal_attributes=None
  splitter=GaussianSplitter (
    n_splits=10
  )
  binary_split=False
  max_size=100.
  memory_estimate_period=1000000
  stop_mem_management=False
  remove_poor_attrs=False
  merit_preprune=True
), Pipeline (
  StandardScaler (
    with_std=True
  ),
  KNNClassifier (
    n_neighbors=5
    window_size=100
    min_distance_keep=0.
    weighted=True
    cleanup_every=0
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
    softmax=False
  )
)]
  use_probabilities=True
)</pre>
</details>

<details>
  <summary>[baseline] Last Class</summary>
  <pre>NoChangeClassifier ()</pre>
</details>

<details>
  <summary>k-Nearest Neighbors</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  KNNClassifier (
    n_neighbors=5
    window_size=100
    min_distance_keep=0.
    weighted=True
    cleanup_every=0
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
    softmax=False
  )
)</pre>
</details>

<script>
    var results = [{'Accuracy': 0.7319185794716327, 'Dataset': 'ImageSegments', 'MacroF1': 0.7304188192194185, 'Memory': 74112, 'MicroF1': 0.7319185794716329, 'Model': 'Naive Bayes', 'Time': 333.376}, {'Accuracy': 0.5068972694760346, 'Dataset': 'Insects', 'MacroF1': 0.4930190627831494, 'Memory': 115338, 'MicroF1': 0.5068972694760346, 'Model': 'Naive Bayes', 'Time': 11182.934}, {'Accuracy': 0.6525319868621011, 'Dataset': 'Keystroke', 'MacroF1': 0.6515767870317882, 'Memory': 906211, 'MicroF1': 0.6525319868621011, 'Model': 'Naive Bayes', 'Time': 13431.261}, {'Accuracy': 0.776093546990039, 'Dataset': 'ImageSegments', 'MacroF1': 0.7631372452021826, 'Memory': 102414, 'MicroF1': 0.776093546990039, 'Model': 'Hoeffding Tree', 'Time': 650.318}, {'Accuracy': 0.5373058073305959, 'Dataset': 'Insects', 'MacroF1': 0.5273644947479657, 'Memory': 625350, 'MicroF1': 0.5373058073305959, 'Model': 'Hoeffding Tree', 'Time': 21233.767}, {'Accuracy': 0.6482180499044071, 'Dataset': 'Keystroke', 'MacroF1': 0.6472493759146577, 'Memory': 1142433, 'MicroF1': 0.6482180499044071, 'Model': 'Hoeffding Tree', 'Time': 31639.209}, {'Accuracy': 0.7743611953226505, 'Dataset': 'ImageSegments', 'MacroF1': 0.7631658299307779, 'Memory': 109228, 'MicroF1': 0.7743611953226506, 'Model': 'Hoeffding Adaptive Tree', 'Time': 952.447}, {'Accuracy': 0.6123147955418472, 'Dataset': 'Insects', 'MacroF1': 0.6032960266714977, 'Memory': 62665, 'MicroF1': 0.6123147955418472, 'Model': 'Hoeffding Adaptive Tree', 'Time': 36969.608}, {'Accuracy': 0.7237119466640521, 'Dataset': 'Keystroke', 'MacroF1': 0.7223930256436223, 'Memory': 182624, 'MicroF1': 0.7237119466640521, 'Model': 'Hoeffding Adaptive Tree', 'Time': 32168.352}, {'Accuracy': 0.6253789519272412, 'Dataset': 'ImageSegments', 'MacroF1': 0.6326079461514587, 'Memory': 887107, 'MicroF1': 0.6253789519272412, 'Model': 'Extremely Fast Decision Tree', 'Time': 6432.51}, {'Accuracy': 0.6525819819478873, 'Dataset': 'Insects', 'MacroF1': 0.6508885643449825, 'Memory': 4000158, 'MicroF1': 0.6525819819478873, 'Model': 'Extremely Fast Decision Tree', 'Time': 333584.878}, {'Accuracy': 0.856267464091377, 'Dataset': 'Keystroke', 'MacroF1': 0.8560901018523239, 'Memory': 10480881, 'MicroF1': 0.856267464091377, 'Model': 'Extremely Fast Decision Tree', 'Time': 318939.289}, {'Accuracy': 0.8185361628410567, 'Dataset': 'ImageSegments', 'MacroF1': 0.8141343880882678, 'Memory': 1477744, 'MicroF1': 0.8185361628410566, 'Model': 'Adaptive Random Forest', 'Time': 3394.313}, {'Accuracy': 0.7466081329119912, 'Dataset': 'Insects', 'MacroF1': 0.7443289389681618, 'Memory': 217379, 'MicroF1': 0.7466081329119912, 'Model': 'Adaptive Random Forest', 'Time': 91420.908}, {'Accuracy': 0.9691651551546644, 'Dataset': 'Keystroke', 'MacroF1': 0.9691813964225687, 'Memory': 976485, 'MicroF1': 0.9691651551546644, 'Model': 'Adaptive Random Forest', 'Time': 19248.81}, {'Accuracy': 0.7652663490688609, 'Dataset': 'ImageSegments', 'MacroF1': 0.7628763468265889, 'Memory': 2616439, 'MicroF1': 0.7652663490688609, 'Model': 'Streaming Random Patches', 'Time': 16804.185}, {'Accuracy': 0.7373550059606032, 'Dataset': 'Insects', 'MacroF1': 0.7357364735163476, 'Memory': 1663610, 'MicroF1': 0.7373550059606032, 'Model': 'Streaming Random Patches', 'Time': 633535.253}, {'Accuracy': 0.9535271336830237, 'Dataset': 'Keystroke', 'MacroF1': 0.953589747225338, 'Memory': 10203947, 'MicroF1': 0.9535271336830238, 'Model': 'Streaming Random Patches', 'Time': 131682.944}, {'Accuracy': 0.8198354265915981, 'Dataset': 'ImageSegments', 'MacroF1': 0.8160519969700989, 'Memory': 132394, 'MicroF1': 0.8198354265915981, 'Model': 'k-Nearest Neighbors', 'Time': 904.716}, {'Accuracy': 0.6868317974530248, 'Dataset': 'Insects', 'MacroF1': 0.6839236226719289, 'Memory': 227180, 'MicroF1': 0.6868317974530248, 'Model': 'k-Nearest Neighbors', 'Time': 36159.402}, {'Accuracy': 0.9845090445610079, 'Dataset': 'Keystroke', 'MacroF1': 0.9845076076521823, 'Memory': 224649, 'MicroF1': 0.9845090445610079, 'Model': 'k-Nearest Neighbors', 'Time': 13009.841}, {'Accuracy': 0.7778258986574275, 'Dataset': 'ImageSegments', 'MacroF1': 0.765010539660814, 'Memory': 968611, 'MicroF1': 0.7778258986574276, 'Model': 'ADWIN Bagging', 'Time': 8718.315}, {'Accuracy': 0.5794652487369197, 'Dataset': 'Insects', 'MacroF1': 0.5701984940722999, 'Memory': 3779176, 'MicroF1': 0.5794652487369197, 'Model': 'ADWIN Bagging', 'Time': 302060.638}, {'Accuracy': 0.8058238148928869, 'Dataset': 'Keystroke', 'MacroF1': 0.8062504565207903, 'Memory': 7013405, 'MicroF1': 0.805823814892887, 'Model': 'ADWIN Bagging', 'Time': 288734.153}, {'Accuracy': 0.8046773495019489, 'Dataset': 'ImageSegments', 'MacroF1': 0.7977695866822913, 'Memory': 950489, 'MicroF1': 0.8046773495019489, 'Model': 'AdaBoost', 'Time': 8696.764}, {'Accuracy': 0.5635324616345299, 'Dataset': 'Insects', 'MacroF1': 0.5546220283668154, 'Memory': 6686747, 'MicroF1': 0.5635324616345299, 'Model': 'AdaBoost', 'Time': 299320.993}, {'Accuracy': 0.8415608608265112, 'Dataset': 'Keystroke', 'MacroF1': 0.8430678719218746, 'Memory': 38613241, 'MicroF1': 0.841560860826511, 'Model': 'AdaBoost', 'Time': 423184.381}, {'Accuracy': 0.7769597228237333, 'Dataset': 'ImageSegments', 'MacroF1': 0.7645642360301897, 'Memory': 1008843, 'MicroF1': 0.7769597228237333, 'Model': 'Bagging', 'Time': 9210.347}, {'Accuracy': 0.6064109599409616, 'Dataset': 'Insects', 'MacroF1': 0.5985583633495227, 'Memory': 1064579, 'MicroF1': 0.6064109599409616, 'Model': 'Bagging', 'Time': 349903.142}, {'Accuracy': 0.6679739202902103, 'Dataset': 'Keystroke', 'MacroF1': 0.6688529665037395, 'Memory': 10896363, 'MicroF1': 0.6679739202902103, 'Model': 'Bagging', 'Time': 515583.618}, {'Accuracy': 0.7782589865742746, 'Dataset': 'ImageSegments', 'MacroF1': 0.7660163657276378, 'Memory': 952066, 'MicroF1': 0.7782589865742745, 'Model': 'Leveraging Bagging', 'Time': 27651.873}, {'Accuracy': 0.6918273506537741, 'Dataset': 'Insects', 'MacroF1': 0.6866970895319842, 'Memory': 4544858, 'MicroF1': 0.6918273506537741, 'Model': 'Leveraging Bagging', 'Time': 899361.945}, {'Accuracy': 0.9480366684641404, 'Dataset': 'Keystroke', 'MacroF1': 0.9481036874490959, 'Memory': 5550619, 'MicroF1': 0.9480366684641404, 'Model': 'Leveraging Bagging', 'Time': 199951.687}, {'Accuracy': 0.8527501082719792, 'Dataset': 'ImageSegments', 'MacroF1': 0.8518698684396576, 'Memory': 1399585, 'MicroF1': 0.8527501082719792, 'Model': 'Stacking', 'Time': 7834.691}, {'Accuracy': 0.751792911612769, 'Dataset': 'Insects', 'MacroF1': 0.7498238877852432, 'Memory': 2983276, 'MicroF1': 0.7517929116127688, 'Model': 'Stacking', 'Time': 236013.317}, {'Accuracy': 0.9763713907544488, 'Dataset': 'Keystroke', 'MacroF1': 0.9763665247853219, 'Memory': 3653522, 'MicroF1': 0.9763713907544488, 'Model': 'Stacking', 'Time': 146361.554}, {'Accuracy': 0.8033780857514076, 'Dataset': 'ImageSegments', 'MacroF1': 0.7949621132813502, 'Memory': 322317, 'MicroF1': 0.8033780857514076, 'Model': 'Voting', 'Time': 2262.615}, {'Accuracy': 0.6482297954472345, 'Dataset': 'Insects', 'MacroF1': 0.6362223941753195, 'Memory': 985553, 'MicroF1': 0.6482297954472345, 'Model': 'Voting', 'Time': 82197.771}, {'Accuracy': 0.793274180106868, 'Dataset': 'Keystroke', 'MacroF1': 0.7984237858213096, 'Memory': 2391520, 'MicroF1': 0.793274180106868, 'Model': 'Voting', 'Time': 75692.984}, {'Accuracy': 0.14811606756171503, 'Dataset': 'ImageSegments', 'MacroF1': 0.1481156678425267, 'Memory': 1436, 'MicroF1': 0.14811606756171503, 'Model': '[baseline] Last Class', 'Time': 71.279}, {'Accuracy': 0.2897610081934642, 'Dataset': 'Insects', 'MacroF1': 0.28976272570313216, 'Memory': 1454, 'MicroF1': 0.2897610081934642, 'Model': '[baseline] Last Class', 'Time': 1688.062}, {'Accuracy': 0.9975488994558557, 'Dataset': 'Keystroke', 'MacroF1': 0.9975489582566448, 'Memory': 5287, 'MicroF1': 0.9975488994558557, 'Model': '[baseline] Last Class', 'Time': 668.641}]

    baseColumns = [
        "Dataset",
        "Model",
        "Memory",
        "Time"
    ]
    metrics = Object.keys(results[0]).filter(x => !baseColumns.includes(x)).sort();
    columns = [...baseColumns, ...metrics].map(x => ({title: x, field: x}))

    function formatBytes(bytes, decimals = 2) {
        if (bytes === 0) return '0 Bytes'

        const k = 1024;
        const dm = decimals < 0 ? 0 : decimals;
        const sizes = ['Bytes', 'KB', 'MB', 'GB', 'TB', 'PB', 'EB', 'ZB', 'YB'];

        const i = Math.floor(Math.log(bytes) / Math.log(k));

        return parseFloat((bytes / Math.pow(k, i)).toFixed(dm)) + ' ' + sizes[i];
    }

    function msToTime(s) {
        var ms = s % 1000;
        s = (s - ms) / 1000;
        var secs = s % 60;
        s = (s - secs) / 60;
        var mins = s % 60;
        var hrs = (s - mins) / 60;

        return (
            (hrs > 0 ? hrs + 'h ' : '') +
            (mins > 0 ? mins + 'm ' : '') +
            (secs > 0 ? secs + 's' : '') +
            (ms > 0 ? ' ' + Math.round(ms) + 'ms' : '')
        )
    }

    columns.map((x, i) => {
        if (x.title === 'Dataset') {
            columns[i]["headerFilter"] = true
        }
        if (x.title === 'Model') {
            columns[i]["headerFilter"] = true
        }
        if (x.title === 'Memory') {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered){
                return formatBytes(cell.getValue())
            }
        }
        if (x.title === 'Time') {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return msToTime(cell.getValue())
            }
        }
        if (['Accuracy', 'F1', 'MacroF1', 'MicroF1'].includes(x.title)) {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return (100 * cell.getValue()).toFixed(2) + "%"
            }
        }
        if (['MAE', 'RMSE', 'R2'].includes(x.title)) {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return cell.getValue().toFixed(3)
            }
        }
    })

    new Tabulator('#multiclass-classification-results', {
        data: results,
        layout: 'fitColumns',
        columns: columns
    })
    </script>

## Regression

### Results

<div id="regression-results"></div>

### Datasets

<details>
  <summary>Friedman7k</summary>
  <pre>Sample from the stationary version of the Friedman dataset.

This sample contains 10k instances sampled from the Friedman generator.

    Name  Friedman7k
    Task  Regression
 Samples  7,000     
Features  10        
  Sparse  False     </pre>
</details>

<details>
  <summary>FriedmanGSG10k</summary>
  <pre>Sample from the FriedmanGSG generator.

This sample contains 10k instances sampled from the Friedman generator and presents
global and slow gradual concept drifts that affect the data and happen after
3.5k and 7k instances. The transition window between different concepts has a length of
1k instances.

    Name  FriedmanGSG10k
    Task  Regression    
 Samples  10,000        
Features  10            
  Sparse  False         </pre>
</details>

<details>
  <summary>FriedmanLEA10k</summary>
  <pre>Sample from the FriedmanLEA generator.

This sample contains 10k instances sampled from the Friedman generator and presents
local-expanding abrupt concept drifts that locally affect the data and happen after
2k, 5k, and 8k instances.

    Name  FriedmanLEA10k
    Task  Regression    
 Samples  10,000        
Features  10            
  Sparse  False         </pre>
</details>

<details>
  <summary>TrumpApproval</summary>
  <pre>Donald Trump approval ratings.

This dataset was obtained by reshaping the data used by FiveThirtyEight for analyzing Donald
Trump's approval ratings. It contains 5 features, which are approval ratings collected by
5 polling agencies. The target is the approval rating from FiveThirtyEight's model. The goal of
this task is to see if we can reproduce FiveThirtyEight's model.

    Name  TrumpApproval                                                        
    Task  Regression                                                           
 Samples  1,001                                                                
Features  6                                                                    
  Sparse  False                                                                
    Path  /Users/mastelini/Documents/river/river/datasets/trump_approval.csv.gz</pre>
</details>

### Models

<details>
  <summary>Adaptive Model Rules</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  AMRules (
    n_min=200
    delta=1e-07
    tau=0.05
    pred_type=&quot;adaptive&quot;
    pred_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    splitter=TEBSTSplitter (
      digits=1
    )
    drift_detector=ADWIN (
      delta=0.002
    )
    alpha=0.99
    anomaly_threshold=-0.75
    m_min=30
    ordered_rule_set=True
    min_samples_split=5
  )
)</pre>
</details>

<details>
  <summary>Adaptive Random Forest</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  []
)</pre>
</details>

<details>
  <summary>Bagging</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  [HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=False
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  )]
)</pre>
</details>

<details>
  <summary>Exponentially Weighted Average</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  [LinearRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=Squared ()
    l2=0.
    l1=0.
    intercept_init=0.
    intercept_lr=Constant (
      learning_rate=0.01
    )
    clip_gradient=1e+12
    initializer=Zeros ()
  ), HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=True
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=None
  ), KNNRegressor (
    n_neighbors=5
    window_size=100
    aggregation_method=&quot;mean&quot;
    min_distance_keep=0.
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
  ), AMRules (
    n_min=200
    delta=1e-07
    tau=0.05
    pred_type=&quot;adaptive&quot;
    pred_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    splitter=TEBSTSplitter (
      digits=1
    )
    drift_detector=ADWIN (
      delta=0.002
    )
    alpha=0.99
    anomaly_threshold=-0.75
    m_min=30
    ordered_rule_set=True
    min_samples_split=5
  )]
)</pre>
</details>

<details>
  <summary>Hoeffding Adaptive Tree</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  HoeffdingAdaptiveTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    bootstrap_sampling=True
    drift_window_threshold=300
    drift_detector=ADWIN (
      delta=0.002
    )
    switch_significance=0.05
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
    seed=42
  )
)</pre>
</details>

<details>
  <summary>Hoeffding Tree</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  HoeffdingTreeRegressor (
    grace_period=200
    max_depth=inf
    delta=1e-07
    tau=0.05
    leaf_prediction=&quot;adaptive&quot;
    leaf_model=LinearRegression (
      optimizer=SGD (
        lr=Constant (
          learning_rate=0.01
        )
      )
      loss=Squared ()
      l2=0.
      l1=0.
      intercept_init=0.
      intercept_lr=Constant (
        learning_rate=0.01
      )
      clip_gradient=1e+12
      initializer=Zeros ()
    )
    model_selector_decay=0.95
    nominal_attributes=None
    splitter=TEBSTSplitter (
      digits=1
    )
    min_samples_split=5
    binary_split=False
    max_size=500.
    memory_estimate_period=1000000
    stop_mem_management=False
    remove_poor_attrs=False
    merit_preprune=True
  )
)</pre>
</details>

<details>
  <summary>Linear Regression</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  LinearRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=Squared ()
    l2=0.
    l1=0.
    intercept_init=0.
    intercept_lr=Constant (
      learning_rate=0.01
    )
    clip_gradient=1e+12
    initializer=Zeros ()
  )
)</pre>
</details>

<details>
  <summary>Linear Regression with l1 regularization</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  LinearRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=Squared ()
    l2=0.
    l1=1.
    intercept_init=0.
    intercept_lr=Constant (
      learning_rate=0.01
    )
    clip_gradient=1e+12
    initializer=Zeros ()
  )
)</pre>
</details>

<details>
  <summary>Linear Regression with l2 regularization</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  LinearRegression (
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.01
      )
    )
    loss=Squared ()
    l2=1.
    l1=0.
    intercept_init=0.
    intercept_lr=Constant (
      learning_rate=0.01
    )
    clip_gradient=1e+12
    initializer=Zeros ()
  )
)</pre>
</details>

<details>
  <summary>Multi-layer Perceptron</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  MLPRegressor (
    hidden_dims=(5,)
    activations=(&lt;class 'river.neural_net.activations.ReLU'&gt;, &lt;class 'river.neural_net.activations.ReLU'&gt;, &lt;class 'river.neural_net.activations.Identity'&gt;)
    loss=Squared ()
    optimizer=SGD (
      lr=Constant (
        learning_rate=0.001
      )
    )
    seed=42
  )
)</pre>
</details>

<details>
  <summary>Passive-Aggressive Regressor, mode 1</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  PARegressor (
    C=1.
    mode=1
    eps=0.1
    learn_intercept=True
  )
)</pre>
</details>

<details>
  <summary>Passive-Aggressive Regressor, mode 2</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  PARegressor (
    C=1.
    mode=2
    eps=0.1
    learn_intercept=True
  )
)</pre>
</details>

<details>
  <summary>Stochastic Gradient Tree</summary>
  <pre>SGTRegressor (
  delta=1e-07
  grace_period=200
  init_pred=0.
  max_depth=inf
  lambda_value=0.1
  gamma=1.
  nominal_attributes=[]
  feature_quantizer=StaticQuantizer (
    n_bins=64
    warm_start=100
    buckets=None
  )
)</pre>
</details>

<details>
  <summary>Streaming Random Patches</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  SRPRegressor (
    model=HoeffdingTreeRegressor (
      grace_period=50
      max_depth=inf
      delta=0.01
      tau=0.05
      leaf_prediction=&quot;adaptive&quot;
      leaf_model=LinearRegression (
        optimizer=SGD (
          lr=Constant (
            learning_rate=0.01
          )
        )
        loss=Squared ()
        l2=0.
        l1=0.
        intercept_init=0.
        intercept_lr=Constant (
          learning_rate=0.01
        )
        clip_gradient=1e+12
        initializer=Zeros ()
      )
      model_selector_decay=0.95
      nominal_attributes=None
      splitter=TEBSTSplitter (
        digits=1
      )
      min_samples_split=5
      binary_split=False
      max_size=500.
      memory_estimate_period=1000000
      stop_mem_management=False
      remove_poor_attrs=False
      merit_preprune=True
    )
    n_models=10
    subspace_size=0.6
    training_method=&quot;patches&quot;
    lam=6
    drift_detector=ADWIN (
      delta=1e-05
    )
    warning_detector=ADWIN (
      delta=0.0001
    )
    disable_detector=&quot;off&quot;
    disable_weighted_vote=True
    drift_detection_criteria=&quot;error&quot;
    aggregation_method=&quot;mean&quot;
    seed=42
    metric=MAE ()
  )
)</pre>
</details>

<details>
  <summary>[baseline] Mean predictor</summary>
  <pre>StatisticRegressor (
  statistic=Mean ()
)</pre>
</details>

<details>
  <summary>k-Nearest Neighbors</summary>
  <pre>Pipeline (
  StandardScaler (
    with_std=True
  ),
  KNNRegressor (
    n_neighbors=5
    window_size=100
    aggregation_method=&quot;mean&quot;
    min_distance_keep=0.
    distance_func=functools.partial(&lt;function minkowski_distance at 0x142cd2670&gt;, p=2)
  )
)</pre>
</details>

<script>
    var results = [{'Dataset': 'TrumpApproval', 'MAE': 1.3474338935927912, 'Memory': 5215, 'Model': 'Linear Regression', 'R2': -4.81891868547912, 'RMSE': 4.126219207359161, 'Time': 29.41}, {'Dataset': 'Friedman7k', 'MAE': 2.23757758349508, 'Memory': 5447, 'Model': 'Linear Regression', 'R2': 0.6549674406764808, 'RMSE': 2.9098720954400448, 'Time': 236.652}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.521459611350154, 'Memory': 5447, 'Model': 'Linear Regression', 'R2': 0.6037965552608275, 'RMSE': 3.3624494572844275, 'Time': 371.959}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.2897103473066593, 'Memory': 5447, 'Model': 'Linear Regression', 'R2': 0.6487787967935958, 'RMSE': 2.9552632714772367, 'Time': 366.626}, {'Dataset': 'TrumpApproval', 'MAE': 1.2151577407875496, 'Memory': 5457, 'Model': 'Linear Regression with l1 regularization', 'R2': -4.650904180700232, 'RMSE': 4.0662129936129725, 'Time': 33.893}, {'Dataset': 'Friedman7k', 'MAE': 2.3552263510654856, 'Memory': 5689, 'Model': 'Linear Regression with l1 regularization', 'R2': 0.6357810009521413, 'RMSE': 2.989683112289033, 'Time': 307.746}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.640726178462324, 'Memory': 5689, 'Model': 'Linear Regression with l1 regularization', 'R2': 0.5768193415984122, 'RMSE': 3.4750379066060555, 'Time': 401.71}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.501408073457101, 'Memory': 5689, 'Model': 'Linear Regression with l1 regularization', 'R2': 0.6020350333760573, 'RMSE': 3.1481512550934787, 'Time': 439.382}, {'Dataset': 'TrumpApproval', 'MAE': 1.9978419034436667, 'Memory': 5239, 'Model': 'Linear Regression with l2 regularization', 'R2': -5.640263007309195, 'RMSE': 4.407819407941372, 'Time': 33.965}, {'Dataset': 'Friedman7k', 'MAE': 2.5425853022401457, 'Memory': 5471, 'Model': 'Linear Regression with l2 regularization', 'R2': 0.5818589220275194, 'RMSE': 3.203356525801635, 'Time': 273.481}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.804691270416271, 'Memory': 5471, 'Model': 'Linear Regression with l2 regularization', 'R2': 0.539341677314148, 'RMSE': 3.6256518778679254, 'Time': 359.827}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.589283256672832, 'Memory': 5471, 'Model': 'Linear Regression with l2 regularization', 'R2': 0.5743092293383871, 'RMSE': 3.2464438425345, 'Time': 358.104}, {'Dataset': 'TrumpApproval', 'MAE': 4.903983530526025, 'Memory': 4651, 'Model': 'Passive-Aggressive Regressor, mode 1', 'R2': -14.171985226958702, 'RMSE': 6.662732200837991, 'Time': 32.727}, {'Dataset': 'Friedman7k', 'MAE': 6.016255319658246, 'Memory': 4983, 'Model': 'Passive-Aggressive Regressor, mode 1', 'R2': -1.347670503657537, 'RMSE': 7.590361003168411, 'Time': 267.132}, {'Dataset': 'FriedmanLEA10k', 'MAE': 6.210896502344477, 'Memory': 4983, 'Model': 'Passive-Aggressive Regressor, mode 1', 'R2': -1.151193121824162, 'RMSE': 7.834952027785555, 'Time': 398.055}, {'Dataset': 'FriedmanGSG10k', 'MAE': 6.03923179207394, 'Memory': 4983, 'Model': 'Passive-Aggressive Regressor, mode 1', 'R2': -1.3149273533396322, 'RMSE': 7.6037270396456345, 'Time': 399.262}, {'Dataset': 'TrumpApproval', 'MAE': 31.12616606921402, 'Memory': 4651, 'Model': 'Passive-Aggressive Regressor, mode 2', 'R2': -403.916378910996, 'RMSE': 34.42023446743753, 'Time': 32.311}, {'Dataset': 'Friedman7k', 'MAE': 10.12033002328945, 'Memory': 4983, 'Model': 'Passive-Aggressive Regressor, mode 2', 'R2': -5.562891455099383, 'RMSE': 12.690872201368217, 'Time': 265.561}, {'Dataset': 'FriedmanLEA10k', 'MAE': 10.42075346727717, 'Memory': 4983, 'Model': 'Passive-Aggressive Regressor, mode 2', 'R2': -5.005052424437335, 'RMSE': 13.090464069276372, 'Time': 388.326}, {'Dataset': 'FriedmanGSG10k', 'MAE': 10.19807040130848, 'Memory': 4983, 'Model': 'Passive-Aggressive Regressor, mode 2', 'R2': -5.54715023614311, 'RMSE': 12.728352006390262, 'Time': 384.054}, {'Dataset': 'TrumpApproval', 'MAE': 0.49369847918747883, 'Memory': 69210, 'Model': 'k-Nearest Neighbors', 'R2': 0.22347386899695654, 'RMSE': 1.5073329387274894, 'Time': 199.986}, {'Dataset': 'Friedman7k', 'MAE': 2.8164610154113827, 'Memory': 78486, 'Model': 'k-Nearest Neighbors', 'R2': 0.4947712815895522, 'RMSE': 3.5211771463760955, 'Time': 1933.551}, {'Dataset': 'FriedmanLEA10k', 'MAE': 3.1012647780473994, 'Memory': 78486, 'Model': 'k-Nearest Neighbors', 'R2': 0.44465419180979704, 'RMSE': 3.9808736209297644, 'Time': 2918.533}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.8745914499918843, 'Memory': 78486, 'Model': 'k-Nearest Neighbors', 'R2': 0.48619451592674623, 'RMSE': 3.5798338992946586, 'Time': 2891.232}, {'Dataset': 'TrumpApproval', 'MAE': 0.9491372912226345, 'Memory': 152067, 'Model': 'Hoeffding Tree', 'R2': -0.725690551385761, 'RMSE': 2.2470493616023144, 'Time': 66.35}, {'Dataset': 'Friedman7k', 'MAE': 1.9193700459829393, 'Memory': 1987683, 'Model': 'Hoeffding Tree', 'R2': 0.7475497441538437, 'RMSE': 2.4890393788775222, 'Time': 811.741}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.084802419740617, 'Memory': 2338767, 'Model': 'Hoeffding Tree', 'R2': 0.7321832538154749, 'RMSE': 2.76449307288471, 'Time': 1247.497}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.0785888748804457, 'Memory': 2942067, 'Model': 'Hoeffding Tree', 'R2': 0.7027339138034574, 'RMSE': 2.7134792168404567, 'Time': 1236.01}, {'Dataset': 'TrumpApproval', 'MAE': 0.9105420162631065, 'Memory': 140799, 'Model': 'Hoeffding Adaptive Tree', 'R2': -0.7046590881261467, 'RMSE': 2.2333146833315145, 'Time': 85.486}, {'Dataset': 'Friedman7k', 'MAE': 1.9506957305094021, 'Memory': 3184955, 'Model': 'Hoeffding Adaptive Tree', 'R2': 0.7424836697720142, 'RMSE': 2.5138898668498864, 'Time': 1147.806}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.278191208853517, 'Memory': 3216951, 'Model': 'Hoeffding Adaptive Tree', 'R2': 0.6812575434847706, 'RMSE': 3.015897651428698, 'Time': 1593.826}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.259173195983733, 'Memory': 1496887, 'Model': 'Hoeffding Adaptive Tree', 'R2': 0.6536141664272965, 'RMSE': 2.9307764236035703, 'Time': 1673.978}, {'Dataset': 'TrumpApproval', 'MAE': 9.429746533156267, 'Memory': 2116974, 'Model': 'Stochastic Gradient Tree', 'R2': -108.97151968967047, 'RMSE': 17.937886241411594, 'Time': 147.577}, {'Dataset': 'Friedman7k', 'MAE': 3.209324662171133, 'Memory': 20969242, 'Model': 'Stochastic Gradient Tree', 'R2': 0.21521551831389918, 'RMSE': 4.388529917508489, 'Time': 3242.443}, {'Dataset': 'FriedmanLEA10k', 'MAE': 3.246544597341542, 'Memory': 27020122, 'Model': 'Stochastic Gradient Tree', 'R2': 0.29830631914660743, 'RMSE': 4.474766974153515, 'Time': 3652.684}, {'Dataset': 'FriedmanGSG10k', 'MAE': 3.734527959428925, 'Memory': 26896570, 'Model': 'Stochastic Gradient Tree', 'R2': 0.03619923259897739, 'RMSE': 4.888869384234904, 'Time': 3687.315}, {'Dataset': 'TrumpApproval', 'MAE': 0.8006486246351854, 'Memory': 1090860, 'Model': 'Adaptive Random Forest', 'R2': -0.5288187480594344, 'RMSE': 2.1149940606524193, 'Time': 1042.767}, {'Dataset': 'Friedman7k', 'MAE': 2.2358713972983697, 'Memory': 36896964, 'Model': 'Adaptive Random Forest', 'R2': 0.6676618475692191, 'RMSE': 2.855840581273244, 'Time': 10627.621}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.45890037255293, 'Memory': 47660540, 'Model': 'Adaptive Random Forest', 'R2': 0.6187682206129985, 'RMSE': 3.2983078581132137, 'Time': 16709.683}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.7275467018672592, 'Memory': 51949864, 'Model': 'Adaptive Random Forest', 'R2': 0.5160599849636207, 'RMSE': 3.4706944162043065, 'Time': 16168.956}, {'Dataset': 'TrumpApproval', 'MAE': 1.4006677136480725, 'Memory': 119778, 'Model': 'Adaptive Model Rules', 'R2': -1.0268122181765436, 'RMSE': 2.4352183578287736, 'Time': 70.414}, {'Dataset': 'Friedman7k', 'MAE': 2.270973750140377, 'Memory': 402838, 'Model': 'Adaptive Model Rules', 'R2': 0.6498817168508653, 'RMSE': 2.9312391674566967, 'Time': 861.914}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.4390756781223444, 'Memory': 845542, 'Model': 'Adaptive Model Rules', 'R2': 0.6351554005305408, 'RMSE': 3.226640661742825, 'Time': 1232.858}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.36031549747784, 'Memory': 710958, 'Model': 'Adaptive Model Rules', 'R2': 0.6245899904541841, 'RMSE': 3.049010031996783, 'Time': 1195.624}, {'Dataset': 'TrumpApproval', 'MAE': 0.6402449207912374, 'Memory': 970083, 'Model': 'Streaming Random Patches', 'R2': -0.3269050867790717, 'RMSE': 1.9703849500925579, 'Time': 2085.473}, {'Dataset': 'Friedman7k', 'MAE': 1.5112400943450646, 'Memory': 61282527, 'Model': 'Streaming Random Patches', 'R2': 0.8447394201076949, 'RMSE': 1.9519759476588219, 'Time': 27348.38}, {'Dataset': 'FriedmanLEA10k', 'MAE': 1.70819094956249, 'Memory': 86379159, 'Model': 'Streaming Random Patches', 'R2': 0.8014475472874096, 'RMSE': 2.3803141017491347, 'Time': 40109.645}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.03699247015952, 'Memory': 85549007, 'Model': 'Streaming Random Patches', 'R2': 0.7135196919501734, 'RMSE': 2.666937973476643, 'Time': 39098.204}, {'Dataset': 'TrumpApproval', 'MAE': 0.9039014968328843, 'Memory': 1341885, 'Model': 'Bagging', 'R2': -0.7053188035272708, 'RMSE': 2.233746795998647, 'Time': 561.934}, {'Dataset': 'Friedman7k', 'MAE': 1.8437634800710987, 'Memory': 17440529, 'Model': 'Bagging', 'R2': 0.7672731443500319, 'RMSE': 2.3898305630718757, 'Time': 8340.236}, {'Dataset': 'FriedmanLEA10k', 'MAE': 1.9864230724426428, 'Memory': 15954021, 'Model': 'Bagging', 'R2': 0.7545218266923563, 'RMSE': 2.64669003866202, 'Time': 12883.548}, {'Dataset': 'FriedmanGSG10k', 'MAE': 1.957369802642882, 'Memory': 11898901, 'Model': 'Bagging', 'R2': 0.7383472985477564, 'RMSE': 2.550712234539315, 'Time': 12742.581}, {'Dataset': 'TrumpApproval', 'MAE': 40.75458054545452, 'Memory': 245867, 'Model': 'Exponentially Weighted Average', 'R2': -567.6629514867817, 'RMSE': 40.7904615623717, 'Time': 520.789}, {'Dataset': 'Friedman7k', 'MAE': 2.057767274497001, 'Memory': 2813151, 'Model': 'Exponentially Weighted Average', 'R2': 0.7142218481173572, 'RMSE': 2.648246284771721, 'Time': 5368.631}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.1819946941633717, 'Memory': 1378959, 'Model': 'Exponentially Weighted Average', 'R2': 0.7037761073848869, 'RMSE': 2.9074127035173922, 'Time': 7665.499}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.2147289830450694, 'Memory': 1912595, 'Model': 'Exponentially Weighted Average', 'R2': 0.666171182864221, 'RMSE': 2.883544537400712, 'Time': 7944.852}, {'Dataset': 'TrumpApproval', 'MAE': 1.5898274221188347, 'Memory': 11583, 'Model': 'Multi-layer Perceptron', 'R2': -8.045077068340989, 'RMSE': 5.144430305753038, 'Time': 395.458}, {'Dataset': 'Friedman7k', 'MAE': 2.146869030920678, 'Memory': 12091, 'Model': 'Multi-layer Perceptron', 'R2': 0.6318109228679125, 'RMSE': 3.0059330965111926, 'Time': 3160.269}, {'Dataset': 'FriedmanLEA10k', 'MAE': 2.4022330927696007, 'Memory': 12091, 'Model': 'Multi-layer Perceptron', 'R2': 0.6097219798337612, 'RMSE': 3.3372111657174504, 'Time': 4565.735}, {'Dataset': 'FriedmanGSG10k', 'MAE': 2.3374765641352027, 'Memory': 12091, 'Model': 'Multi-layer Perceptron', 'R2': 0.6039860504721648, 'RMSE': 3.138715628619861, 'Time': 4545.362}, {'Dataset': 'TrumpApproval', 'MAE': 1.567554989468773, 'Memory': 514, 'Model': '[baseline] Mean predictor', 'R2': -0.6584830635688459, 'RMSE': 2.202858861923226, 'Time': 12.072}, {'Dataset': 'Friedman7k', 'MAE': 4.02148215121205, 'Memory': 514, 'Model': '[baseline] Mean predictor', 'R2': -0.0014847455535940135, 'RMSE': 4.957537743224416, 'Time': 93.657}, {'Dataset': 'FriedmanLEA10k', 'MAE': 4.2928283270418905, 'Memory': 514, 'Model': '[baseline] Mean predictor', 'R2': -0.0009442770949354973, 'RMSE': 5.344432444452069, 'Time': 140.269}, {'Dataset': 'FriedmanGSG10k', 'MAE': 4.056248001853763, 'Memory': 514, 'Model': '[baseline] Mean predictor', 'R2': -0.001061815629166185, 'RMSE': 4.991267544175499, 'Time': 137.383}]

    baseColumns = [
        "Dataset",
        "Model",
        "Memory",
        "Time"
    ]
    metrics = Object.keys(results[0]).filter(x => !baseColumns.includes(x)).sort();
    columns = [...baseColumns, ...metrics].map(x => ({title: x, field: x}))

    function formatBytes(bytes, decimals = 2) {
        if (bytes === 0) return '0 Bytes'

        const k = 1024;
        const dm = decimals < 0 ? 0 : decimals;
        const sizes = ['Bytes', 'KB', 'MB', 'GB', 'TB', 'PB', 'EB', 'ZB', 'YB'];

        const i = Math.floor(Math.log(bytes) / Math.log(k));

        return parseFloat((bytes / Math.pow(k, i)).toFixed(dm)) + ' ' + sizes[i];
    }

    function msToTime(s) {
        var ms = s % 1000;
        s = (s - ms) / 1000;
        var secs = s % 60;
        s = (s - secs) / 60;
        var mins = s % 60;
        var hrs = (s - mins) / 60;

        return (
            (hrs > 0 ? hrs + 'h ' : '') +
            (mins > 0 ? mins + 'm ' : '') +
            (secs > 0 ? secs + 's' : '') +
            (ms > 0 ? ' ' + Math.round(ms) + 'ms' : '')
        )
    }

    columns.map((x, i) => {
        if (x.title === 'Dataset') {
            columns[i]["headerFilter"] = true
        }
        if (x.title === 'Model') {
            columns[i]["headerFilter"] = true
        }
        if (x.title === 'Memory') {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered){
                return formatBytes(cell.getValue())
            }
        }
        if (x.title === 'Time') {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return msToTime(cell.getValue())
            }
        }
        if (['Accuracy', 'F1', 'MacroF1', 'MicroF1'].includes(x.title)) {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return (100 * cell.getValue()).toFixed(2) + "%"
            }
        }
        if (['MAE', 'RMSE', 'R2'].includes(x.title)) {
            columns[i]["formatter"] = function(cell, formatterParams, onRendered) {
                return cell.getValue().toFixed(3)
            }
        }
    })

    new Tabulator('#regression-results', {
        data: results,
        layout: 'fitColumns',
        columns: columns
    })
    </script>

