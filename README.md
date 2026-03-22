# LAB-EXERCISE-5

# 1.Length of a string

text = input("Enter a string: ")
length = len(text)
print("Length of the string is:", length)

# 2. Count characters in string

text = input("Enter a string: ")
count = 0

for c in text:
    count = count + 1

print("Number of characters:", count)

# 3. Replace same letters with $

text = input("Enter a string: ")

first = text[0]
result = first

for c in text[1:]:
    if c == first:
        result = result + "$"
    else:
        result = result + c

print("Result:", result)

# 4. Swap first 2 characters

a = input("Enter first string: ")
b = input("Enter second string: ")

new_a = b[:2] + a[2:]
new_b = a[:2] + b[2:]

print(new_a + " " + new_b)

# 5.Concatenate 4 variables

a = "I"
b = "am"
c = "learning"
d = "chess"

result = a + " " + b + " " + c + " " + d
print(result)

# 6. Concatenate user input

a = input("Enter first word: ")
b = input("Enter second word: ")

result = a + " " + b
print("Combined:", result)

# 7. Concatenate age and name

name = input("Enter your name: ")
age = input("Enter your age: ")

text = "My name is " + name + " and I am " + age + " years old."
print(text)
