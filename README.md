# Assignment-7
# tuple and its basic operations

#length of tuple
a=(1,2,3,4,5,6,7,8)
length=len(a)
print("length of a:",length)

#concatenation
a=(1,2,3,4)
b=(5,6,7,8)
c=a+b
print("concatenation:",c)

#repetation
a="hello"
b=("hello",)*4
print("repetation:",b)

#membership
a=(1,2,3,4,5,6,7,8,9)
b=5 in a
print("membership:",b)


##q2 indexing,slicing,iteration

# indexing
a=(1,2,3,4,5,6,7,8,9)
b=a[2]
print("index:",b)

#negative indexing
b=a[-5]
print("neg index:",b)

#slicing
b=a[3:6]
print("slicing;",b)


 output:     
length of a: 8
concatenation: (1, 2, 3, 4, 5, 6, 7, 8)
repetation: ('hello', 'hello', 'hello', 'hello')
membership: True
index: 3
neg index: 5
slicing; (4, 5, 6)