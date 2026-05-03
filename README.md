def chatbot():
    print("Бот: Здравствуйте! Я помощник университета Синергия.")

    while True:
        user_input = input("Вы: ").lower()

        if user_input == "выход":
            print("Бот: До свидания!")
            break

        elif "привет" in user_input:
            print("Бот: Привет! Чем могу помочь?")

        elif "поступление" in user_input:
            print("Бот: Вы можете подать заявку через сайт университета.")

        elif "стоимость" in user_input:
            print("Бот: Стоимость зависит от программы обучения.")

        elif "онлайн" in user_input:
            print("Бот: Да, доступно дистанционное обучение.")

        else:
            print("Бот: Извините, я не понял вопрос.")

chatbot()
