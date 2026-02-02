# EEG-Analysis

MATLAB program for EEG analysis, as well as example analysis outputs. Analysis includes EEG preprocessing, labeling, epoching, ICA, ERP analysis, and a paired paired t-test. EEG signals are recorded in an awareness experiment involving auditory stimuli, and analysis is done to investigate the neural correlates of auditory awareness, specifically the differences in brain responses between aware and unaware perception of stimuli.

## Paired t-test results

ERP analysis was conducted to evaluate brain responses to auditory stimuli. ERPs were averaged separately for conditions where the subject reported being aware of a tone and where no tone was present. Results of ERP analysis are presented in figures `ERPs.jpg`, `IPs.jpg`, and `Statistics.txt`. Statistical analysis is based on t-test to compare brain responses during auditory awareness versus no auditory awareness. More closely, comparison is done between EEG mean amplitudes of a condition, where participant was aware of a tone, and a condition, where was no tone. Results are following:

`h = 0

p = 0.0831

tstat = -2.5620

ci = [-0.9652, 0.1043]

df = 3

sd = 0.3361`

Thus, null hypothesis h—there is no difference in mean EEG amplitude between conditions—is not rejected. P-value p is not below the standard threshold, `0.05`, indicating that the results are not statistically significant, though they approach significance, likely due to the small number of subjects. The t-value tstat of `-2.5620` suggests that the mean amplitude in the tone awareness condition is lower than in the no-tone condition.
