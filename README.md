# deleting-items-
dict={'Roll No':'16/001','Name':'Arav','Course':'BTech'}
print("Name is: ",dict.pop('Name'))
print("Dictionary after popping Name is :", dict)
print("Marks is:", dict.pop('Mark',-1))
print("Dictionary after popping Marks is:", dict)
print("Randomly popping any item:", dict.popitem())
print("dictionary after random popping is:", dict)
print("Aggregate is:",dict.pop('Aggr'))
print("Dictionary after popping Aggregate is:")
