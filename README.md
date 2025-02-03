# Lukatov

Разрабатывается телеграм-бот для продаж деталей

файл main.py исполняемый

    Подключение телеграм-бота
    import telebot
    TOKEN = 'your token'
    bot = telebot.TeleBot(TOKEN)
    @bot.message_handler(content_type=['text'])
    def start(message):
    ____bot.sen_message(message.chat.id,message.text)

    bot.polling(none_stop=True,interval=5)
