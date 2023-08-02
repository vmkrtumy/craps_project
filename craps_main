import random

def randomize_nums():
	nums = []
	nums.append(random.randint(1, 6))
	nums.append(random.randint(1, 6))
	nums.append(nums[0] + nums[1])
	print(nums[0], '+', nums[1], '=', nums[2])
	return nums

def goal_func(goal):
	res = 0
	while res != goal and res != 7:
		n = randomize_nums()
		res = n[2]
	if res == goal:
		print("You win:)")
		return 0
	else:
		print("You lose:(")
		return 0

nums1 = randomize_nums()
if nums1[2] == 7 or nums1[2] == 11:
	print("You win:)")
elif nums1[2] == 2 or nums1[2] == 3 or nums1[2] == 12:
	print("You lose:(")
else:
	goal = nums1[2]
	goal_func(goal)
