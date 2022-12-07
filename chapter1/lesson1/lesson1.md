<!--
{variables}
metamaskBasicSkill=2459994d-33fd-4bb3-8b90-858d874ee5ae;
author1=f3b699cd-2a08-4c2d-af78-d1b149e4297c;
author0=0;
testGoalId=9977d222-1961-45ed-bc0c-3aa0a1eaa649;
{/variables}
-->

<!--{group}-->
<!--{message type=TRANSFER_WALLET|successAnswer=SUCCESS!|wrongAnswer=Error!|amount=0.03|walletAddress="0x68A133aeEb048c687c2e82cFb7ed7CFCD138591c"}-->
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=CONNECT_WALLET|successDescription=SUCCESS!|wrongAnswer=Error!}-->
Need to connect your wallet here
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=WEB3_INTERACTIVE_INPUT|web3CommandType=CALL_FAUCET|successAnswer=SUCCESS!|wrongAnswer=Error!|isInteractiveBlockPromotion=true}-->
test cloud for call faucet, pls set eth ropsten address here
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=DIALOG|authorId=<%author0%>}-->
test dialog empty student with var
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=DIALOG|authorId=0}-->
test dialog empty student with inline
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=MARKDOWN}-->

# Урок 1. Собеседование

На почту приходит **свежее письмо** от партнёрской компании, которая неделю назад объявила набор разработчиков ПО в блокчейн-стартап. Вы сразу отправили тестовое задание и совершенно забыли про этот момент. Напрасно — они вернулись, причём с выгодным предложением:

```bash
cd home/hello-wold
```

<!--{/message}-->
<!--{/group}-->

// assesment
<!--{group}-->
<!--{message type=ASSESMENT|totalSeconds=1800|nextButtonText=Check Result}-->
Assesment Content



// card input example in assesment
<!--{insideMessage type=CARD_INPUT|skills=[<%metamaskBasicSkill%>]|successAnswer=success text|wrongAnswer=wrong text|difficulty=EASY|nextButtonText=next btn text|title=test title unused|answers=[1, 2, 3]}-->
test content message
<!--{/insideMessage}-->

// quiz example in assesment
<!--{insideMessage type=QUIZ|skills=[<%metamaskBasicSkill%>]|successAnswer=success text|wrongAnswer=wrong text|difficulty=EASY|nextButtonText=next btn text|title=test title unused|optionType=radio|isInteractiveBlockPromotion=true}-->
What is the array method for flipping an array (reverse)?

<!--{option hint=Wrong option|isCorrect=false}-->
.map
<!--{/option}-->

<!--{option hint=Right option!|isCorrect=true}-->
.reverse()
<!--{/option}-->

<!--{/insideMessage}-->


<!--{/message}-->
<!--{/group}-->


// markdown example two
<!--{group}-->
<!--{message type=MARKDOWN}-->
test content message markdown?
<!--{/message}-->
<!--{/group}-->

// card input example
<!--{group}-->
<!--{message type=GOAL_EVENT|targetGoalId=<%testGoalId%>}-->
test content message
<!--{/message}-->
<!--{/group}-->

// card input example
<!--{group}-->
<!--{message type=CARD_INPUT|skills=[<%metamaskBasicSkill%>]|successAnswer=success text|wrongAnswer=wrong text|difficulty=EASY|nextButtonText=next btn text|title=test title unused|answers=[1, 2, 3]}-->
test content message
<!--{/message}-->
<!--{/group}-->

// quiz example
<!--{group}-->
<!--{message type=QUIZ|skills=[<%metamaskBasicSkill%>]|successAnswer=success text|wrongAnswer=wrong text|difficulty=EASY|nextButtonText=next btn text|title=test title unused|optionType=radio|isInteractiveBlockPromotion=true}-->
What is the array method for flipping an array (reverse)?

<!--{option hint=Wrong option|isCorrect=false}-->
.map
<!--{/option}-->

<!--{option hint=Right option!|isCorrect=true}-->
.reverse()
<!--{/option}-->

<!--{/message}-->
<!--{/group}-->

<!--{group closeGoal=<%testGoalId%>}-->
<!--{message type=DIALOG|authorId=<%author1%>}-->
test dialog empty
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=DIALOG|authorId=<%author1%>}-->

Привет, Кевин!

Меня зовут _Жаклин_, и я представляю компанию CChainBroSSS.

Мы рассмотрели ваше резюме на позицию blockchain-разработчика и спешим поздравить с прохождением вступительного этапа отбора! Ваш опыт на текущем месте работы в качестве разработчика ПО автоматически закрыл ряд требований по hard & soft skills к потенциальным кандидатам. Теперь мы ждём вас, чтобы пообщаться лично и принять финальное решение.

Буду откровенна, среди ваших коллег нашлось достаточно желающих сменить профиль с разработки обычного ПО на блокчейн-технологии, и сейчас осталась лишь тройка самых сильных кандидатов. Все они хотят выпускать токены, подключать кошельки, развивать DEX и браться как за fork’и, так и запуск собственных chain’ов. В будущем, разумеется, и предварительно нам придётся вас обучить. Если, конечно, пройдёте.

Чтобы вы точно понимали, с чем придётся иметь дело, я отмечу, что CChainBro является MVP-проектом, который стремится к собственному DEX. Кому нужны все эти посредники и болезненные комиссии, когда можно организовать собственную биржу?

Я зарезервировала для вас календарь на следующий вторник в 2 часа дня. Думаю, что тогда, по прошествии финального тура, мы обсудим и график работы, и условия оплаты, которые наверняка вам понравятся. Если у вас есть какие-либо вопросы или пожелания по поводу встречи — пишите в ответном письме или Telegram, и мы обсудим детали.

До скорых встреч, Жаклин, HR-менеджер CChainBro»

Вы принимаете приглашение на встречу, которое приходит следом за письмом HR, и настраиваетесь на собеседование.

<!--{/message}-->
<!--{/group}-->


<!--{group}-->
<!--{message type=UNAVALIBLE_TEST_TYPE|authorId=<%author1%>}-->
Тесстовое сообщение с несуществующим типом
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=UNAVALIBLE_TEST_TYPE|authorId=<%author1%>}-->
Тесстовое сообщение с несуществующим типом
<!--{/message}-->
<!--{/group}-->

<!--{group}-->
<!--{message type=CREATE_DROPLET|authorId=<%author1%>|nextButtonText=Go to Virtual Machine|courseDropletId=d065124d-6421-447e-b68e-2f57559a6664|skills=[<%metamaskBasicSkill%>]}-->
<p>По <code>SSH</code>, это Ubuntu машина, сейчас попрошу DevOps создать и скину адрес</p>
<!--{/message}-->
<!--{/group}-->
