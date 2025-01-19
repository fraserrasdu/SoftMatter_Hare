# SoftMatter_Hare
Additional material for paper Quantifying memory: Detection of focal conic domain rearrangement across a phase transition

In the folder Images we collect the images used to generate figure 4 of the paper. The images were segmented and the focal conic domains were manually labeled as “large central focal conic domain” or “focal conic domain that does not meet the requirements (either because it is too small or because it is too off-centered)”.

In the folder Data we report all the data used to generate figures 5 and 6 of the paper. 
The data are to be read as such: 

Column titles’ explanation:
T is the temperature at which the sample is heated before being cooled back to smectic phase.
index is a characteristic index associated to each temperature ramp
n_eff is the effective weight used in the weighted average 
pcond is the conditional probability that a focal conic domain forms in a pocket after cooling if a focal conic domain was previously in the same pocket.
pcond_err_bnm is the associated error calculated as described in the paper 
p2cond is the conditional probability that a focal conic domain forms in a pocket after cooling if there was no focal conic domain previously in the same pocket. 
p2cond_err_bnm is the associated error to p2cond. 
sum_p_n is the total number of pockets 
sum_f_n is the sum of the focal conic domains after cooling 
sum_f_i is the sum of focal conic domains before cooling 
sum_!f_n is the count of empty pockets 
sum_f_if_f is the sum of focal conic domains that form in a pocket if there was a focal conic domain in the same pocket before heating
sum_!f_if_f is the sum of empty pockets in which there was a focal conic domain (in the same pocket) before heating
sum_f_if_!f is the sum of focal conic domains that form in a pocket if there was no focal conic domain in the same pocket before heating
sum_!f_if_!f is the sum of empty pockets that were empty before heating
unwt_mean_pcond is the unweighted mean of pcond 
geom indicates the channel geometry analysed, characterised by the listed w and s
 
