# Sign-in
Sign in. Asks age, mail, phone number 
# Вход на сайт. Спрашивает возраст, если младше(не пускает), больше равно 18 (пускает) и спрашивает:
# как зовут, почта, номер телефона
age = int(input('Введите ваш возраст:'))
if age < 18:
    print('Вы слишком молоды')
elif age >= 18:
    name = input('Введите Ваше имя:')
    email = input('Введите Вашу почту:')
    number = int(input('Введите Ваш номер телефона:'))
