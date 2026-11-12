# reproducibility-materials


1. Download the code: Download `reproducibility_materials.7z` and extract it using the password provided to the reviewers.

2. Prepare the environment: Use a Python environment compatible with the provided scripts and install their required dependencies. If a dependency file is included in the archive, follow it; otherwise, check the imports in the scripts.

3. Configure the experiment: Set the array geometry, switching topology, SNR, number of snapshots, and network parameters according to the experimental settings in the manuscript. The representative configuration uses 9 array elements, 3 RF channels, 4 switching states, and 256 snapshots per state.

4. Run training or evaluation: Run the corresponding script in the extracted code. For evaluation, select the desired source-number, SNR, and switching-topology settings.

5. Check the results: Use the evaluation outputs to examine covariance-reconstruction NMSE and DOA-estimation RMSE. Results may vary slightly with random seeds and independently generated test samples.

For model details, parameter settings, and the evaluation protocol, please refer to the manuscript.
