The	dataset	TimeSeries.csv	represents	the	recording of	a	number	of	variables for	
admitted patients.	 The	 data	 was obtained	 over	 the	 first	 24	 hours	 of	 hospital	
admission.	

1. The dataset contains a certain number of patients, and these patients are distributed across different outcome classes.
2. The values across variables and outcome classes have specific distributions, and visualizations have been used to identify nonsensical or impossible values, with justification provided for the chosen course of action.
3. The data has been sampled into regular intervals, and the number of intervals per patient has been determined. If the number of intervals is not the same for all patients, the average number of intervals per patient has been calculated.
4. Summary statistics and plots have been utilized to describe and visualize the extent of missing data. Differences in missingness rates across variables and outcome classes have been discussed, along with possible explanations.
5. A function has been created to calculate Mean Arterial Pressure (MAP) using Systolic Blood Pressure and Diastolic Blood Pressure. MAP values have been computed for all patients at each recording interval, and a plot has been generated to show the change in MAP over time for each patient, including the identification of the first hour when vasopressors were started, highlighted in the plot.
