< [К содержанию](/readme.md)

Команды при совместной работе 
===

`git fetch`
--

*Чтобы с репозиторием на GItHube связаться и спросить, что изменилось с тех пор, как ты последний раз туда заходил, и чтобы все новое себе забрать, команду `git fetch [имя или адрес репозитория]`*

*Команда эта только данные забирает к себе, но не сливает их с имеющимися наработками и не изменяет то, над чем работаешь ты. Эти данные потребуется еще вручную слить и конфликты при возникновении решить.* 

***

`git pull`
--

*Работает команда за двоих - за `git fetch` и `git merge`. И с удаленного репозитория изменения забирает и тут же их с текущей веткой сливает.*

***
`git push`
--

*Чтобы наоброт свои изменения в удаленный репозиторий отправить, запушить, используй команду `git push`, но помни, что право на зпись должно быть в него. И если кто-то запушил уже, то твой пуш отклонят, пока ты версию свою не обновишь, локально проблемы не решишь. Вот тогда можешь снова в общий репозиторий залить.*

***
`git remote`
--

*Чтобы в длинных адресах репозиториев путаться не начать, их можно коротко обозвать:*

    git remote add <имя> <URL>.

