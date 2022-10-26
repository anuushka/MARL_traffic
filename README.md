# MARL_traffic

Oct26

Changed action and dqn_agent.

action is  action = np.argmax((avg_act * alpha) + curr_act) #oorchilson

avg_act - average of previous actions

curr_act - current action

added self.prev_actions = deque(maxlen=10) to dqn_agent class Agent.

dqn_agent.py act heseg deer 2 zuil butsaana: return np.argmax(action_values.cpu().data.numpy()), action_values.cpu().data.numpy()

