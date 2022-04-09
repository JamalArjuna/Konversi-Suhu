# Konversi-Suhu
Program konversi suhu menggunkan bahasa python
inputuser_1 = str(input("SUHU APA YANG MAU DI KONVERSI (C/F/R/K):"))

# ALGORITMA CELCIUS
if inputuser_1 == "C":
    input_user_c = float(input("MASUKKAN SUHU DALAM BENTUK CELCIUS: "))
    # REAMUR_C
    reamur_c = (4/5) * input_user_c
    print("SUHU DALAM REAMUR ADALAH",reamur_c, "REAMUR")

    #kelvin_c
    Kelvin_c = input_user_c + 273
    print("SUHU DALAM KELVIN ADALAH",Kelvin_c, "KELVIN")

    # FAHRENHEIT_C F = °C × 1,8 + 32
    fahrenheit_c = input_user_c * 1.8 + 32
    print("SUHU DALAM FAHRENHEIT ADALAH",fahrenheit_c, "FAHRENHEIT")
    # END ALGORITMA CELCIUS


# ALGORITMA FAHRENHEIT
if  inputuser_1 == "F":
    input_user_f = float(input("SILAHKAN MASUKKAN SUHU DALAM BENTUK FAHRENHEIT: "))

    # KELVIN_F
    kelvin_f = (input_user_f + 459.67) / 1.8
    print("SUHU DALAM KELVIN ADALAH",kelvin_f, "KELVIN")

    # REAMUR °Ré = (°F − 32) / 2,25
    reamur_f = (input_user_f - 32) / 2.25
    print("SUHU DALAM REAMUR ADALAH",reamur_f, "REAMUR")

    # CELCIUS °C = (°F − 32) / 1,8
    celcius_f = (input_user_f - 32) / 1.8
    print("SUHU DALAM CELCIUS ADALAH",celcius_f, "CELCIUS")

    # END ALGORITMA FAHRENHEIT
   

    # ALGORITMA KELVIN
if inputuser_1 == "K":
    input_user_k = float(input("SILAHKAN MASUKKAN SUHU DALAM KELVIN: "))

    #CELCIUS_K C = K − 273,15
    celcius_k = input_user_k - 273.15
    print("SUHU DALAM CELCIUS ADALAH",celcius_k, "CELCIUS")

    #REAMUR_K Ré = (K − 273,15) × 0,8
    reamur_k = (input_user_k - 273.15) * 0.8
    print("SUHU DALAM REAMUR ADALAH",reamur_k, "REAMUR")

    #FAHRENHEIT_K F = K × 1,8 − 459,67
    fahrenheit_k = input_user_k * 1.8 - 459,67
    print("SUHU DALAM FAHRENHEIT ADALAH",fahrenheit_k, "FAHRENHEIT")

    #END ALGHORITMA KELVIN


    #ALGORITMA REAMUR

if inputuser_1 == "R":
    input_user_r = float(input("SILAHKAN MASUKKAN SUHU DALAM REAMUR: "))

    #CELCIUS_R C = °Ré / 0,8
    celcius_r = input_user_r / 0.8
    print("SUHU DALAM CELCIUS ADALAH",celcius_r, "CELCIUS")

    #FAHRENHEIT_R F = °Ré × 2,25 + 32
    fahrenheit_r = input_user_r * 2.25 + 32
    print("SUHU DALAM FAHRENHEIT ADALAH",fahrenheit_r, "FAHRENHEIT")

    #KELVIN_R °Ré / 0,8 + 273,15
    kelvin_r = input_user_r / 0.8 + 273.15
    print("SUHU DALAM KELVIN ADALAH",kelvin_r, "KELVIN")
    #END ALGORITMA REAMUR
else:
    print("SALAH MEMASUKKAN INPUT, PERHATIKAN INPUT SESUAI! (C/F/R/K)!")
