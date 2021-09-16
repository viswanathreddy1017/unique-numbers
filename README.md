# unique-numbers
#U will get unique numbers i.e without repetition of numbers in a list



N=[1,2,3,4,5,5,2,3,1]
uniques=[]   
for num in N:
    if num is not in uniques:
           uniques.append(num)
print(uniques)
