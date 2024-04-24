# Ismet-Bora-Ozturk
meme_dict = {
            "CRINGE": "Garip ya da utandırıcı bir şey",
            "LOL": "Komik bir şeye verilen cevap",
            "ROFL": "Bir şakaya karşılık cevap",
            "SHEESH": "onaylamamak",
            "CREEPY": "korkunç",
            "AGGRO": "agresifleşmek/sinirlenmek",
            }
for i in range(5):       
    word = input("Anlamadığınız kısaltmayı hepsi büyük şekilde yazınız.")

    
    if word in meme_dict.keys():
        print(meme_dict[word])
    else:
        print("Bu kısaltmanın anlamı burada yok")
    
