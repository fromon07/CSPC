# CSPC - Computer Science for Physics and Chemistry
My coursework repository. Each practical is under PW<n>/Lab <X>/.
## Setup
Create the environment for a given lab:
conda env create -f PW<n>/Lab\ <X>/environment.yml
conda activate cspc
---
## PW1 - Lab A: Reproducible Foundations
**What I built:**
- To test a radioactive decay simulation which is given by decay.py via test_decay.py and compare the speed of pure python code vs numpy code via speed.py documents.
**Speed comparison (loop vs NumPy):**
- loop : 1.7689 s
- numpy : 0.000135 s
- speed-up: 13,107 x faster
**Tests:** all passing? yes
**Conclusion:**
- In test_decay.py, all three tests passed. Observed that the speed of numpy is 13,107 times faster than pure python code. Using numpy library and pytest commands are practised, such as "pytest.raises", pytest.approx. The main problem was understanding the behaviour of "TODO 2" on teast_decay.py file, but the commands were searched and the logic behind it was succesfully understood.