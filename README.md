# MARL_traffic

Oct26
Changed action and dqn_agent.
action is  action = np.argmax((avg_act * alpha) + curr_act) #oorchilson
avg_act - average of previous actions
curr_act - current action
