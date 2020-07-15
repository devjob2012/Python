"""
This is Selection Sort
"""
print('Selection Sort')
a = [54, 26, 93, 17, 77, 31, 15, 44, 55, 20]
print(a)


def selection_sort(list_a):
    list_length = len(list_a)
    for i in range(list_length):
        max_location = i
        for j in range(i + 1, list_length):
            if list_a[j] < list_a[max_location]:
                max_location = j
        list_a[max_location], list_a[i] = list_a[i], list_a[max_location]
    return list_a


print(selection_sort(a))
