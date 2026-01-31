This repository accompanies the paper "Beyond Correlation: Why Likert-Scale Calibration Challenges LLM-as-Participant Designs".

It contains:
- Four Jupyter notebooks written in Python that are designed to exemplify the steps of the simulation pipeline discussed in the paper. They read the original stimuli of the simulated studies (*630similarFrenchWordPair.csv* and *Barbosa&Cat_2019.csv*). Two are used to simulate Barbosa and De Cat (2029) with OpenAI and local models (*Barbosa_19-OpenAI.ipynb* and *Barbosa_19-local.ipynb*), the other two are used to simulate Lakhzoum, Izaute, and Ferrand (2021) with OpenAI and local models (*Lakhzoum_21-OpenAI.ipynb*, *Lakhzoum_21-local.ipynb*). Both notebooks display the same structure, they only differ in data preprocessing and output evaluation.
- Two additional notebooks with evaluation functions written ad hoc per each simulation. They read model results after prompting, calculates stats, and provides visualisations.

The proposed framework can be tested in future research. 



