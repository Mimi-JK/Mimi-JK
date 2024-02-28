def create_interactive_message():
    # انشئ رسالتك الإفتتاحية
    message = "مرحبًا صديقي! أتمنى أن تكون دائمًا سعيدًا ومبتسمًا. 😊"

    # قائمة الخيارات التفاعلية
    options = [
        "شكرًا! سأحاول أن أبقى سعيدًا.",
        "أنت أيضًا! دعونا نبقى إيجابيين معًا.",
        "سأحاول، شكرًا لك!"
    ]

    # إضافة الخيارات إلى الرسالة
    for i, option in enumerate(options, start=1):
        message += f"\n{i}. {option}"

    return message

# استدعاء الدالة وطباعة الرسالة
interactive_message = create_interactive_message()
print(interactive_message)

