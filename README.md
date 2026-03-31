# 🌿 Git

Git — система контроля версий, доступная на компьютере каждого разработчика. Она позволяет легко создавать ветвления и объединять изменения. В то же время GitHub значительно упрощает использование Git как для отдельных пользователей, так и для команд, в целях контроля версий и совместной работы 🤝

Вот некоторые команды Git, которые я использовал для создания своего портфолио на GitHub.

## Задание 1

##### Создание, клонирование, отправка и получение репозиториев.
```git
git init dmitriyskachkov                                    # Создайте репозиторий с тем же именем, что и ваше имя пользователя.
git clone git@github.com:skachkovdmitriy/skachkovdmitriy.git      # Cкопируйте репозиторий на свой компьютер в отдельную папку.
git clone git@github.com:testrusau/testrusau.git            # Скопируйте папку github.com/testrusau/testrusau на свой компьютер в отдельную папку
cd testrusau                                                
git push git@github.com:skachkovdmitriy/testrusau.git main:main    # Перенесите данные из репазитория testrusau в свой собственный
git commit -m "commited change description"                 # Откройте файл README.md и замените каждый блок отдельным коммитом: "git push"
git push 

```
## Задание 2

##### Создание и добавление удалённых репозиториев 
```git
git init sql                                                # Создайте отдельный репазиторий для портфолио.
git remote add sql https://github.com/skachkovdmitriy/skachkovdmitriy.git  # Подключить удаленный репазиторий к локальному
README.md edited manually                                   # Добавить ссылки на ваш репазиторий в файл README.md
git commit -m "commited change description"                 # Отправить изменения на удаленный репазиторий
git push                                                     



```