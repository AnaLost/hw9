# hw9
## 1) Чтобы удалить все пустые строки, я использовала регулярное выражение и искала \n\r, заменила все вхождения на \0 в поле замены.
![](https://pp.userapi.com/c840332/v840332947/8e58e/sXfFTipsO7Q.jpg)
![](https://pp.userapi.com/c840332/v840332947/8e598/d0N161WZOT0.jpg)
Также я решила проверить свои действия, использоввав другое регулярное выражение. В тексте никаких изменений не произошло, поэтому я решила, что сделала все правильно.
![](https://pp.userapi.com/c840332/v840332947/8e5a2/3OCnQiBzxiQ.jpg)


## 2) Чтобы найти всех князей и города, имя и название которых оканчивается на "слав", я использовала регулярное выражение (^|\s)+[А-Я][а-я]*(слав). 
![](https://pp.userapi.com/c840332/v840332947/8e5ac/2MLXd97apzY.jpg)
Всего было найдено 592 вхождения.

## 3) Чтобы найти все варианты написания города Новгород, я использовала регулярное выражение (^|\s)+[Н][а-я]*(город). 
![](https://pp.userapi.com/c840332/v840332947/8e5b6/j6sPSQIJRTY.jpg)
Всего упоминаний Новгорода нашла: 32.
