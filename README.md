1. Computed non - overlapping dfnc using window length of 31
2. Size each sample is having 157 TC, window length 31 the dFNcs generated for each sample is 5
3. Total 101x5 + 103x5 dFNCs
4. find the lower triangle matrix if these dfnc using np.tril.
5. Fed these lower triangle matrices to Kmeans
6. Calculated avg of all the 5 clusters
7. Calculated avg of all the 5 clusters
8. All dFNC's of each subject belonging to each cluster are extracted into adc and szc
9. Averaged all the samples of each cluster's dFNCs and visualised them
