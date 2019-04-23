Polygon-polygon misalignment problems arise in regressions where the response and explanatory variable are measured on a different spatial units and where there is no simple relationship between the two sets of units. A classic example of this problem in political science is in the British elections before the 1960s where votes are counted in constituencies, and census variables (social characteristics) were reported only at the local government district level, where local government district and census boundaries were very different. A recent example occurs in the relationship between general election results (reported by constituency) and 2016 Brexit referendum results (reported for local government districts).

We develop code to address two closely related types of Polygon-Polygon spatial misalignment problems: 
1. Totals. For example, what is the relationship between the number of voters and the population size.  
2. Compostions. For example, the relationship between social composition and vote share.
  
Although our main substantive interest is in the composition cases, we first develop code to deal with the total case because this is a necessary step in the composition case. Later we aim to extend the method in cases that covariates are provided at multiple different scales.
