EEG Cognitive State Classification	
						 
Objective: Analysed EEG data to classify cognitive states using advanced deep learning techniques.
●	Data Loading: Loaded EEG data from the PhysioNet repository.

●	Power Spectral Density (PSD) Analysis:

	○	Calculated band-wise PSD for resting and task states.

	○	Focused on Delta (1-4 Hz), Theta (4-8 Hz), Alpha (8-12 Hz), Beta (12-30 Hz), and Gamma (30-100 Hz) bands.

	○	Compared the PSDs of the two states and summarized the findings.

●	 Deep Learning Classification:

	○	Implemented binary classification using the EEGNet model.

	○	Trained and validated the models using the provided dataset.

	○	Evaluated the models using accuracy, precision, recall, and F1-score metrics.

●	Technology used: Python, MNE Libraries, TensorFlow & PyTorch, EEGNet
