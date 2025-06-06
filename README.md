# SlimNet
Instructions for running the SlimNet

1. Run the first 19 cells individually
	a. This will install all the necessary dependencies for the original CNN and the PTQ model.
2. Once you are at the 20th cell, delete the run time.
	a. Deleting the runtime is at the top of the notebook where it says Runtime -> Disconnect and delete runtime
3. Then install the required libraries which is cell 21 and 22.
4. After the reinstallation, restart the session by going to the top and pressing Runtime -> Restart session.
	a. It is important to restart after installing so the new environment includes those libraries properly.
5. Run cells 23 and onward to run the QAT model, the testing, heatmap, and the confusion matrix.
