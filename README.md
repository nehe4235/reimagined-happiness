
def tambah(x, y):
    return x + y

def kurang(x, y):
    return x - y

def kali(x, y):
    return x * y

def bagi(x, y):
    if y == 0:
        return "Erorr: pembagian dengan nol"
    return x / y

# printnan kalkulator kita
print("pilih lokasi")
print("1. Tambah")
print("2. kurang")
print("3. kali")
print("4. bagi")

pilihan = input("masukan pilihan(1/2/3/4)")

num1 = float(input("masukan angka pertama:"))
num2 = float(input("masukan angka kedua:"))

if pilihan == '1':
    print(num1, "+", num2, "=", tambah(num1, num2))

elif pilihan == '2':
    print(num1, "-", num2, "=", kurang(num1, num2))

elif pilihan == '3':
    print("masuk kali")
    print(num1, "*", num2, "=", num1 * num2)

elif pilihan == '3':
    print(num1, "/", num2, "=", bagi(num1, num2))
else:
    print("pilihan vaild")
