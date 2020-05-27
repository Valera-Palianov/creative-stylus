# Учебное задание по Stylus

____

##Для запуска проекта:

### Шаг первый
```
npm install 
```

или (для пользователей Yarn)

```
yarn
```

### Шаг второй
```
npx stylus ./src/general.styl --out dist/assets/styles/light.css
```

или (для пользователей Yarn)

```
yarn stylus ./src/general.styl --out dist/assets/styles/light.css
```


##Смена темы со светлой на темную:

- В файле src/variables.styl поменять значение переменной '$isDarkTheme' с 'true' на 'false'
- Выполнить команду:
	- Для пользователей npm: npx stylus ./src/general.styl --out dist/assets/styles/dark.css
	- Для пользователей yarn: yarn stylus ./src/general.styl --out dist/assets/styles/dark.css
- В файле dist/index.html закомментировать строчку <link rel="stylesheet" type="text/css" href="./assets/styles/light.css"> и убрать комментарий со строки следующей за ней.


##Ход выполнения работы:

- Инициализировал git
- Инициализировал Yarn
- Установил пакет Stylus
- Добавил .gitignore
- Создал файл src/variables.styl, где добавил условный оператор и тестовую переменную
- Создал index.html в папке dist, проверил работоспособность stylus
- Проверил темную тему