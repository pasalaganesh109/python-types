# python-types
# python.examples
a = ("Focus", "on", "Career")
b = ["git", "for", "hub"]
c = {"Git": 1, "for":2, "hub":3}
d = "Fisherman"
e = 10.23
f = 11.22
 
print(type(a))
print(type(b))
print(type(c))
print(type(d))
print(type(e))
print(type(f))


#printing N*N diagonal matrix
n = int(input())
for i in range(n):
   for j in range(n):
      if i == j or j == n - 1 - i:
          print("*", end="")
      else:
          print(" ", end="")
   print() 
