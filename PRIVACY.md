# Конфиденциальность / Privacy

**RU.** Avgust Arkstone работает на вашем Mac и ничего о вас не собирает. Модели, чаты, проекты, картинки, память и база знаний
хранятся только в папке Arkstone на вашем диске. По умолчанию интернет выключен: пока тумблер «Интернет» выключен, ни
один запрос не уходит в сеть. Когда вы его включаете, Avgust Arkstone обращается в сеть только по вашему действию: скачать
модель или движок из открытого каталога, скачать набор для базы знаний, найти что-то в интернете по вашему вопросу
(поисковикам уходит только текст запроса), проверить обновление на GitHub. Ваши чаты и файлы в эти запросы не входят.
Режим «Облако» (FreeLLMAPI) выключен по умолчанию. Если вы его включите и выберете облачную модель, текст разговора,
приложенные картинки и найденные фрагменты уходят тому облачному провайдеру, чей бесплатный ключ вы добавили (Google,
Groq, OpenRouter и др.), и обрабатываются по его правилам. Ключи провайдеров хранятся зашифрованными в `Data/Cloud` на
вашем диске. Офлайн-модели по-прежнему ничего никуда не отправляют.
Отчёты о сбоях пишутся в `Data/Logs/Crashes` на диске и уходят автору только если вы сами нажмёте «Отправить отчёт»
(письмо создаётся в вашей почте, ничего не загружается). Голос записывается только пока вы держите кнопку микрофона и
обрабатывается локальной моделью. Связь: a_a_avgust@icloud.com.

**EN.** Avgust Arkstone runs on your Mac and collects nothing about you. Models, chats, projects, images, memory and the
knowledge base stay in the Arkstone folder on your disk. The internet is off by default: while the “Internet” switch is
off, no request leaves your Mac. When you turn it on, Avgust Arkstone goes online only when you act: downloading a model or an
engine from the open catalogue, downloading a knowledge pack, searching the web for your question (search engines
receive only the query text), checking GitHub for an update. Your chats and files are never part of these requests.
“Cloud” mode (FreeLLMAPI) is off by default. If you turn it on and pick a cloud model, the conversation text, attached
images and found snippets go to the cloud provider whose free key you added (Google, Groq, OpenRouter and others) and are
handled under its terms. Provider keys are stored encrypted in `Data/Cloud` on your disk. Offline models still send
nothing anywhere.
Crash notes are written to `Data/Logs/Crashes` on your disk and reach the author only if you press “Send report”
yourself (a mail is drafted in your mail app; nothing is uploaded). The microphone records only while you hold the
microphone button, and the audio is processed by a local model. Contact: a_a_avgust@icloud.com.
