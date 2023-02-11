# -
задание 12.7.3
money = int(input("сумма инвестирования:"))
per_cent = ("ТКБ": 5,6. "VTB": 4,28, "СКБ": 5,9, "СБЕР" : 4,0)
procent = list (per_cent.values())
bankTKB = round(procent[0]/100*5000)
bankVTB = round(procent[1]/100*5000)
bankSKB = round(procent[2]/100*5000)
bankSBER = round(procent[3]/100*5000)
deposit = [bankTKB, bankVTB, bankSKB, bankSBER]
print("2000", deposit)
deposit.sort()
print("max", deposit [0])
