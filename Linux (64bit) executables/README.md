# Exact algorithms
bb_bf: Brach & Bound best First  
  Usage: bb_bf instance [incumbentValue]

bb_df: Brach & Bound depth First  
  Usage: bb_df instance [incumbentValue]

##### Usage
Parameters:
- file of the instance
- input incumbent value (optional)

# Meta-heuristic

grasp: GRASP meta-heuristic  
  Usage: grasp instance iterations seed [maxTime [target]]

##### Usage
Parameters:
- instance file
- number of iterations
- seed
- maximum time (optional)
- target value (optional): if this value is given, the algorithm terminates when obtains a solution as good as the target
