# TESLA-Obstacle-Avoidance-
AIM

To implement a reactive obstacle avoidance strategy based on proximity sensing.

PROCEDURE
Initialize the obstacle distance
Define a safe distance threshold
Compare obstacle distance with threshold
If distance < threshold, trigger avoidance action
Execute right-turn manoeuvre
Display the result
CODE
# Input value
distance = 0.25   # in meters

# Safe threshold
threshold = 0.5

# Obstacle avoidance logic
if distance < threshold:
    action = "Turn Right"
else:
    action = "Move Forward"

# Output
print(action)
OUTPUT

Turn Right

RESULT

The robot performs a right-turn manoeuvre when an obstacle is detected within the unsafe distance, ensuring safe navigation.
