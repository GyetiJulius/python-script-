// This is written by Julius Gyeti
// 10989434

# Python program to display all the prime numbers within an interval

n = input("enter last number: ")
sum = 0

for number in range(2, n + 1):
    i = 2
    for i in range(2, number):
        if (int(number % i) == 0):
            i = number
            break;
     if i is not number:
        sum = sum + number
        print(sum)
