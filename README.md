Computed non - overlapping dfnc using window length of 31
Size each sample is having 157 TC, window length 31 the dFNcs generated for each sample is 5
Total 101x5 + 103x5 dFNCs
find the lower triangle matrix if these dfnc using np.tril.
Fed these lower triangle matrices to Kmeans
Calculated avg of all the 5 clusters
All dFNC's of each subject belonging to each cluster are extracted into adc and szc
Averaged all the samples of each cluster's dFNCs and visualised them
