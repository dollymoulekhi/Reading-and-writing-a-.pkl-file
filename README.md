# Reading-and-writing-a-.pkl-file

## Writing dict,or other things in a .pkl file

import pickle
a_file = open("master_list.pkl", "wb")
pickle.dump(x, a_file)
a_file.close()


## reading a pkl file

a_file = open("master_list.pkl", "rb")
output = pickle.load(a_file)
print(output)
