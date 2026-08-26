def calculations(year):
    remainder = year % 12
    if remainder == 0:
        print("Your Chinese Zodiac Sign is: Monkey — 猴 (Hóu)",
        "Traits: Sharp, smart, curious.")

    elif remainder == 1:
        print("Your Chinese Zodiac Sign is: Rooster — 鸡 (Jī)",
        "Traits: Observant, hardworking, courageous.")

    elif remainder == 2:
        print("Your Chinese Zodiac Sign is: Dog — 狗 (Gǒu)",
        "Traits: Lovely, honest, prudent.")

    elif remainder == 3:
        print("Your Chinese Zodiac Sign is: Pig — 猪 (Zhū)",
        "Traits: Compassionate, generous, diligent.")

    elif remainder == 4:
        print("Your Chinese Zodiac Sign is: Rat — 鼠 (Shǔ)",
        "Traits: Clever, resourceful, versatile.")

    elif remainder == 5:
        print("Your Chinese Zodiac Sign is: Ox — 牛 (Niú)",
        "Traits: Diligent, dependable, strong.")

    elif remainder == 6:
        print("Your Chinese Zodiac Sign is: Tiger — 虎 (Hǔ)",
        "Traits: Brave, confident, competitive.")

    elif remainder == 7:
        print("Your Chinese Zodiac Sign is: Rabbit — 兔 (Tù)",
        "Traits: Quiet, elegant, kind.")

    elif remainder == 8:
        print("Your Chinese Zodiac Sign is: Dragon — 龙 (Lóng)",
        "Traits: Powerful, lucky, hot-headed.")

    elif remainder == 9:
        print("Your Chinese Zodiac Sign is: Snake — 蛇 (Shé)", 
              "Traits: Enigmatic, intelligent, wise.")

    elif remainder == 10:
        print("Your Chinese Zodiac Sign is: Horse — 马 (Mǎ)", 
              "Traits: Animated, active, energetic.")

    elif remainder == 11:
        print("Your Chinese Zodiac Sign is: Goat — 羊 (Yáng)",
        "Traits: Gentle, shy, sympathetic.")

def zodiacSign(year):
    if year < 1900:
        print("Invalid Year, it should not be earlier than 1900")
        return
    if year >= 1900:
        calculations(year)

year = int(input("Enter year of birth: "))
zodiacSign(year)


<img width="966" height="927" alt="image" src="https://github.com/user-attachments/assets/77fb0e80-a4be-4ae8-9d74-7d9a49daffde" />


