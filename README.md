# Home_works_17.7.3
Python код. Расчет дохода от депозита в разных банках. 

# Словарь с процентными ставками
per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}

money = float(input("Введите сумму вклада: "))

deposit = [int(money * rate / 100) for rate in per_cent.values()]

print("Накопления за год:", deposit)

max_deposit = max(deposit)

print("Максимальная сумма, которую вы можете заработать —", max_deposit)

