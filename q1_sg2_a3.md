# Chinese Zodiac Sign

## Requirements

The program asks the user to enter their year of birth, using 1900 as the baseline year. It validates that the year is not earlier than 1900. If the user enters an invalid year, the program displays an appropriate message and stops. Otherwise, the program determines the Chinese zodiac sign based only on the year of birth.

## Python Code

```python
year = int(input("Enter your birth year: "))

if year < 1900:
    print("Invalid year. Please enter a year that is 1900 or later.")
else:
    zodiac_signs = [
        "Rat (鼠 / Shǔ)",
        "Ox (牛 / Niú)",
        "Tiger (虎 / Hǔ)",
        "Rabbit (兔 / Tù)",
        "Dragon (龙 / Lóng)",
        "Snake (蛇 / Shé)",
        "Horse (马 / Mǎ)",
        "Goat (羊 / Yáng)",
        "Monkey (猴 / Hóu)",
        "Rooster (鸡 / Jī)",
        "Dog (狗 / Gǒu)",
        "Pig (猪 / Zhū)"
    ]

    zodiac_index = (year - 1900) % 12
    zodiac = zodiac_signs[zodiac_index]

    print("Your Chinese Zodiac Sign is :", zodiac)
