prices = [1, 12, 5, 111, 200, 1000, 10]

def selection_sort(list_a):
    list_length = len(list_a)
    for i in range(list_length):
        max_location = i
        for j in range(i + 1, list_length):
            if list_a[j] < list_a[max_location]:
                max_location = j
        list_a[max_location], list_a[i] = list_a[i], list_a[max_location]
    return list_a

def maximumToys(prices, k):
    print(prices)
    print(k)
    totalPrice = 0
    for price in prices:
        if totalPrice < k:
            totalPrice +=price
            print(totalPrice)
        else:
            totalPrice +=price
    print(totalPrice)
maximumToys(prices, 50)
