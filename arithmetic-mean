# výpočet aritmetického průměru
# arithmetic mean

user_input = input("Zadejte čísla, jejichž aritmetický průměr chcete vypočítat: ").split(", ")
new_numbers = ", ".join(str(item) for item in user_input)

for i in range(0, len(user_input)):
    user_input[i] = float(user_input[i])
  
def calculate_mean():
    total = sum(user_input)
    count = len(user_input)
    mean = "{:.2f}".format(total / count)
    print(f"Průměr čísel '{new_numbers}' je: {mean}")

calculate_mean()





