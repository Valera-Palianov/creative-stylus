# Учебное задание по Stylus

____

## Для запуска проекта:

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


## Смена темы со светлой на темную:

- В файле src/variables.styl поменять значение переменной '$isDarkTheme' с 'false' на 'true'
- Выполнить команду:
	- Для пользователей npm: npx stylus ./src/general.styl --out dist/assets/styles/dark.css
	- Для пользователей yarn: yarn stylus ./src/general.styl --out dist/assets/styles/dark.css
- В файле dist/index.html убрать комментарий со строкой подключения стиля.


## Ход выполнения работы:

- Инициализировал git
- Инициализировал Yarn
- Установил пакет Stylus
- Добавил .gitignore
- Создал файл src/variables.styl, где добавил условный оператор и тестовую переменную
- Создал index.html в папке dist, проверил работоспособность stylus
- Проверил темную тему
- Собрал макет страницы
- Добавил больше цветовых переменных, а так же одну переменную с тенями