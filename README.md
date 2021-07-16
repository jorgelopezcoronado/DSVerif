# DSVerif -- A formal data set verification tool.
This repository contains the information for a formal data set verification tool, as descried in our [paper](https://arxiv.org/abs/2009.10822).

The directory [properties](./properties) contains example properties in the [*SMT-LIB*](http://smtlib.cs.uiowa.edu/) language. Those properties are the following:
- balanced -- a formula that checks that the data set has a balanced set of labels
- contradicting -- a formula that checks that the data set has no contradicting labels (same input vectors, different expected outputs)
- min\_100\_ex -- a formula that checks if there are at least 100 training examples
- min\_max -- a formula that checks if the data set input values are within a min / max range ([-1,1])
- well\_distributed -- a formula that checks that there doesn't exist a point which is more distant than a given constant (1) w.r.t. all the data set training examples

Currently, the data set verification tool's source code is not publicly available. If you are interested in the tool or collaboration, please do not hesitate to [contact us](mailto:erick.petersen@airbus.com,jorge.lopez-c@airbus.com,claude.poletti@airbus.com?subject=Regarding%20DLinkEm). A small video showcasing the tool is shown in the video below.

[![DSVerif Demo](https://github.com/jorgelopezcoronado/DSVerif/)](https://youtu.be/sHKCxnhETXg)

