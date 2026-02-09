# CIS567-integrated-lab-1-
Week 2 Assignment - Setting Up GitHub

start = int(input())
end = int(input())

if end < start:
    print("Second integer can't be less than the first.")
else:
    while start <= end:
        print(start, end=' ')
        start += 5
    print()
