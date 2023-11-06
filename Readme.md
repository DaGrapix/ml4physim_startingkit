# Starting Kit - Machine Learning for Physical Simulation Challenge
This starting kit provides a set of jupyter notebooks helping the challenge participants to better understand the use case, the dataset and how to contribute to this competition. For general information concerning the challenge and submit your solutions, you can refer to the competition [Codabench page](https://www.codabench.org/competitions/1534/).

In the following, we describe the content of the jupyter notebooks : 

- **0_Basic_Competition_Information**: This notebook contains general information concerning the competition organization, phases, deadlines and terms. The content is the same as the one shared in the competition Codabench page. 

- **1-Airfoil_design_basic_simulation**: This notebook aims to familiarize the participants with the use case and to facilitate their comprehension. It allows the visualization of some simulation results.

- **2-Import_Airfoil_design_Dataset**: Shows how the challenge datasets could be downloaded and imported using proper functions. These data will be used in the following notebook to train and evaluate an augmented simulator. 

- **3-Reproduce_baseline_results**: This notebook shows how the baseline results could be reproduced. It includes the whole pipeline of training, evaluation and score calculation of an augmented simulator using [LIPS platform](https://github.com/IRT-SystemX/LIPS). 

- **4-How_to_Contribute**: This notebook shows 3 ways of contribution for beginner, intermediate and advanced users. The submissions should respect one of these forms to be valid and also to enable their proper evaluation through the LIPS platform which will be used for the final evaluation of the results.

       * Beginner Contributor: You only have to calibrate the parameters of existing augmented simulators
       * Intermediate Contributor: You can implement an augmented simulator respecting a given template (provided by the LIPS platform)
       * Advanced Contributor: you can implement your architecture independently from LIPS platform and use only the evaluation part of the framework to assess your model performance.

- **5-Scoring**: This notebook shows firstly how the score is computed by describing its different components. Next, it provides a script which can be used locally by the participants to obtain a score for their contributions. We encourage participants to evaluate their solutions via codabench (which uses the same scoring module as the one described in this notebook). 

- **6_Submit_to_Codabench**: It shows, step-by-step, how to submit your solution (augmented simulator) using the [competition Codabench page](https://www.codabench.org/competitions/1534/). 



