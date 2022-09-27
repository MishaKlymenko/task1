  # MarkDown
  MarkDown файли стали популярними через свою простоту та широки можливості, та як файли .md можна переводити в багато типів даних таких як .pdf, .docx, .txt  і тд.

  Альтернативою до MD є формат [asciidoc.org](https://asciidoc.org), але він не отримав такої популярності.

  Місця крім документації де можна зустріти синтаксис MD це наші месенджери такі як Telegram а також ми можемо використовувати конструкції даної мови розмітки даних на різних сайтах, в тому числі stack overflow та github-питання.
  
## Заголовки
Заголовки в _MD_ файлах пишуться за допомогою знаку *#*, так як і **в _HTML_ в _MD_ є 6 рівнів заголовків**, а _також є можливість прописати текст і на __новому__ рядку поставити 3 нижні підкреслення що зробить той текст **'заголовком'**_
# text
## text
### text
#### text
##### text
###### [google][1]
_ _ _

## Курсивний та жирний текст
Курсив в MD записується за допомогою конструкцій _2 нижні підкреслення і між ними текст_ або *2 знаки зірочки і між ними текст*. Якщо використати 4 знаки зірочки і мід кожними 2 знаками поставити текст, то він буде **жирним**. Якщо ж і між ними буде ще 2 знаки зірочки то текст буде ***жирним та курсивним***

## Додаткове форматування тексту
### Абзаци
Для того щоб додати абзац потрібно зробити 2 переноси рядка
text

new line. інший спосіб це добавити тег _br_  в текст <br>
text
new line two

## ~~Перекреслення тексту~~ ~

### Списки

1. text 

   tеxt

2. dsfsd 
   - dsdss
1. fdf 
* dsd

## Картинка
![Фото](https://i.ytimg.com/vi/C9ZF4VokOxM/maxresdefault.jpg)

## Підсвітка коду та команд
Підсвітка коду та команд відбувається за допомогою обратних лапок якщо це 1 рядок або тройних обратних лапок якщо це багаторядкове виділення. Також можна показати код чого ми вставляємо і таким чином буде виділений синтаксис коду.
`git push`
```javascript
let myVariable = 10;
consle.log(myVariable);
```

## Таблиці

| ПІБ                           | Група |    Статус    |
|-------------------------------|:-----:|:------------:|
| Клименко Михайло Володиирович |  all  | **Викладач** |
| Сегін Ігор Миронович |  ІПЗ, КН  | **Викладач** |
| Клименко Оксана Вікторівна |  ІПЗ, КН  | **Викладач** |

## Цитати
> Вчіться якщо не хочете бути як русня <br>
> ось так


[1]: https://google.com
