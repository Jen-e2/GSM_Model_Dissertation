# GSM_Model_Dissertation

The RunGSM file allows the user to run the heauristic algorithm over the optional choices of the net replenishment time. 

The solveGSM is the model used in the function to solve the GSM for each particular value of the net replenishment time. 

Within the models, to evaluate the result at a different set of lead times for the serial supply chain example, the definition of L within the code needs to be changed in both files. The options are: L_downdec, L_uniform, and L_downinc which refers to downstream decreasing, uniform and increasing lead times. 

Please note that these models have been specifically curated for the two examples. These can easily be adapted for geenral use. 
