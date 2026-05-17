# probality-mean-and-variance
# Aim:
Program to Find Mean and Variance

# Program to find Mean and Variance
```
n = int(input("Enter number of values: "))

x = []
p = []

print("Enter values of x:")
for i in range(n):
    x.append(float(input()))

print("Enter probabilities:")
for i in range(n):
    p.append(float(input()))

# Calculate mean
mean = 0
for i in range(n):
    mean += x[i] * p[i]

# Calculate E(X^2)
ex2 = 0
for i in range(n):
    ex2 += (x[i] ** 2) * p[i]

# Variance formula
variance = ex2 - mean**2

print("Mean =", mean)
print("Variance =", variance)
```
# OUTPUT:


<img width="740" height="769" alt="image" src="https://github.com/user-attachments/assets/2b06467c-919e-48f5-b926-c0707ff41759" />



https://github.com/calwinsam17-jpg/probality-mean-and-variance

# RESULT:

Thus the code run successfully and got the output!
