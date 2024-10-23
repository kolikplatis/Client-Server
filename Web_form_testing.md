_**Задание:**_ написать чек-лист, тест-кейсы (10 шт), баг-репорты (10 шт)

_**Ответы:**_

- [Чек-лист](https://docs.google.com/spreadsheets/d/1JqJy-Op6X_ycz2aTGmpEgXe4OWvt3T2T5-BdnYqisII/edit?gid=0#gid=0)
- [Тест-кейсы](https://docs.google.com/spreadsheets/d/1JqJy-Op6X_ycz2aTGmpEgXe4OWvt3T2T5-BdnYqisII/edit?gid=298107433#gid=298107433)
- [Баг-репорты](https://docs.google.com/spreadsheets/d/1JqJy-Op6X_ycz2aTGmpEgXe4OWvt3T2T5-BdnYqisII/edit?gid=1281624137#gid=1281624137)    



Форма для регистрации http://itcareer.pythonanywhere.com/  

**Требования:**
1. Environment: web 
2. Поля, обязательные для заполнения: "Name", "Email", "Password"
3. Должно быть поле подтверждения пароля. 

**Поле "Name":** 
- Принимает латинские буквы, цифры, спецсимволы только ‘–‘, ‘_’ и пробел 
- Max количество символов – 256
- Min количество символов – 2
- Регистр любой 
- Первой должна быть буква (цифры и символы первыми нельзя), 
- Последней - не имеет значения, 
- Если поле оставить пустым: должно обвестись в красную рамочку и вывестись сообщение: “This field is required”. 
 
**Поле "Surname":** 
- аналогично Name. 
 
**Поле "Email":**
- ознакомиться со стандартами: [Link1](https://tools.ietf.org/html/rfc3696#page-5) [Link2](https://tools.ietf.org/html/rfc2822#section-3.4.1)  
 
**Поле "Password":** 
- min: 5 символов
- max: 16 символов
- буквы только латинские 
- Минимально должен включать 1 заглавную букву, 1 строчную и 1 цифру
- Спецсимволы не принимает



