my_list = [1, 2.5, 'a', "Hello", [3, 4], 5, 6.8, 'b', [7, 'c'],2,'c']

int_count = 0

float_count = 0

char_count = 0

str_count = 0

list_count = 0

for item in my_list:

    if isinstance(item, int):

        int_count += 1

    elif isinstance(item, float):

        float_count += 1

    elif isinstance(item, str) and len(item) == 1:

        char_count += 1

    elif isinstance(item, str):

        str_count += 1

    elif isinstance(item, list):

        list_count += 1

        

print("Total number of elements in the list:", len(my_list))

print("Total integer values:", int_count)

print("Total float values:", float_count)

print("Total character values:", char_count)

print("Total string values:", str_count)

print("Total list values:", list_count)
