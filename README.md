# Отчёт по lab04

## Homework

1. Создаём директорию и удалённый репозиторий

_cd Dan10022002/workspace/tasks<br/>
mkdir task_timp_lab04<br/>
cd task_timp_lab04_

2. Клонируем файлы из прошлой лабораторной работы и удаляем ненужные (оставляем только заголовочные файлы, фалы реализаций и CMakeLists.txt 

_git clone https://github.com/Dan10022002/task_lab03.git .<br/>
git remote remove origin<br/>
git remote add origin https://github.com/Dan10022002/task_lab04.git_

3. Создаём файл .travis.yml и редактируем его

_touch .travis.yml<br/>
vim .travis.yml_

![travis](https://github.com/Dan10022002/task_lab04/blob/master/travis.png)

4. Заливаем на гитхаб

_git add .<br/>
git commit -m "First commit"<br/>
git push origin master_

5. Авторизируемся на  https://travis-ci.org и запускаем тест сборки

![test](https://api.travis-ci.org/Dan10022002/task_lab04.svg?branch=master&status=passed)
