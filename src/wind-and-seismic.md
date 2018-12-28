# Wind and Seismic

## WITH THE EXCEPTION OF UPLIFT:

- 1.0E = Ultimate Seismic = LRFD Seismic = Un-factored Seismic. This is reducible.
    - Use 'SMU' in takeoff.
- 0.7E = Allowable Seismic = ASD Seismic. Not reducible as the EOR has already reduced the value by 0.7. 
    - Use 'SM' in takeoff.
- 1.0W = Ultimate Wind = LRFD Wind = Un-factored Wind. This is reducible.
    - Use 'WLU' in takeoff
- 0.6W = Allowable Wind = ASD Wind. Not reducible as the EOR has already reduced the value by 0.6. 
    - Use 'WL' in takeoff.

NOTE: Do not confuse 1.0E with E, and 1.0W with W. If there is no decimal value before the letter then there is no indication as to whether the value is ultimate or allowable, and therefore we need to either confirm or assume it’s ASD. There are cases where we have already confirmed this - for example, Kramer has ‘E = ___K’ for braces and we know that this is an LRFD load. If you are not too sure, just ask. 
 



## FOR UPLIFT VALUES:

- 1.0W = Gross Ultimate Wind = Gross LRFD Wind. This is reducible by applying the formula: 0.6W – 0.6D.
- 0.6W = Gross Allowable Wind = Gross ASD Wind. The wind has been reduced by 0.6, but we can still subtract out 0.6*D.
- 0.6W – 0.6D = 0.6D + 0.6W = Net Allowable Wind = Net ASD Wind. The EOR has already reduced the wind values.
	
NOTE:  ‘Net Uplift’ is not the same as ‘Net Allowable Wind’ or ‘Net ASD Wind’. ‘Net Uplift’ doesn’t always mean that the EOR has reduced the values. This is a bit confusing, but the reason is that within ASCE 7-10, ‘Net Uplift’ refers to ultimate wind values (I’ll refrain from explaining why). Therefore, we need to read the notes to get a better understanding of what type of value the wind is.