## LESSON_1

В Этом репозитории находятся шаблон дефолтного конфигурационного файла для Nginx. 
**[nginx.conf]**

## LESSON_2

  
— Ссылки на все репозитории:  
1. [orr-gitlab.wildberries](https://orr-gitlab.wildberries.ru/orr-onboarding/onboarding-vladislav-sokolov)  
2. [gitlab.wildberries.ru](https://gitlab.wildberries.ru/sokolov.v64/onboarding-vladislav-sokolov)  
3. [myPublic-gitlab](https://github.com/jonimuesli/Onboarding-Vladislav-Sokolov)  

— Краткое описание выполнения задания с «удаленным файлом»:

```bash
git-checkout % git log --oneline
2864fd9 (HEAD -> master, origin/master, origin/HEAD) Add file nginx.conf
dfbdad5 del file intitxt
e9dee85 Add new file
73ec3e7 add readmw.md
a1049c0 add tg
1b82ce2 add file mirror
6921b02 add curl.txt
vsokolov@MacBook-Pro-Vladislav git-checkout % git checkout dfbdad5
Note: switching to 'dfbdad5'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at dfbdad5 del file intitxt
vsokolov@MacBook-Pro-Vladislav git-checkout % git log --oneline   
dfbdad5 (HEAD) del file intitxt
e9dee85 Add new file
73ec3e7 add readmw.md
a1049c0 add tg
1b82ce2 add file mirror
6921b02 add curl.txt
vsokolov@MacBook-Pro-Vladislav git-checkout % git show dfbdad5
commit dfbdad5677438fd4df16a838225126a8df1ec569 (HEAD)
Author: ilin.leonid2 <ilin.leonid2@wb.ru>
Date:   Sat Apr 20 14:44:18 2024 +0000

    del file intitxt

diff --git a/intitxt1.txt b/intitxt1.txt
deleted file mode 100644
index 4bbe4ab..0000000
--- a/intitxt1.txt
+++ /dev/null
@@ -1,6 +0,0 @@
-Совсем забыл рассказать про прикольную штуку из закона о применении ККТ. Они на законодательном уровне потребовали делать бекапы:
-
-Статья 4.5 пункт 2:
-"осуществлять резервирование базы фискальных данных и восстанавливать из резервных копий базу фискальных данных в случае их утраты;"
-
-Так что теперь не отвертишься, придется делать и тестировать бекапы 🙂
```

## LESSON_3
— Картинка:

![my_test_pictures](images/example.png "inogda ya govotu 'hz', no ya znau...")

— Таблица:  

| №   | Элемент         | Пример              |  
|-----|------------------|---------------------|  
| 1   | Заголовок        | `# Example`         |  
| 2   | Код              | ```python print()```|  
| 3   | Ссылка           | [empty](https://epmtyresources.empty)|  
