# retailcrm-payments

Тестирование, как будет вести себя TDD на проекте, приближенном к реальности.
Разработаем приложение, отображающее список заказов retailcrm с типом, суммой и статусом оплаты.
v1.0: Сначала используем API v4. В этой версии API поля оплаты включены в сущность заказа. Здесь для получения необходимых полей нужен всего 1 запрос к API методу /orders
v1.1: Мигрируем наше приложение на API v5. Теперь в одном заказе может быть несколько оплат, но нас не интересуют оплаты отдельно, а лишь общая сумма оплаченных счетов. Меняем только функции доступа к API, но не пользовательский интерфейс
v1.2: Заказчик решает, что нужно отображать оплаты для каждого заказа отдельно. Дорабатываем пользовательский интерфейс и добавляем функционал

Production: <https://makcrx-retailcrm.netlify.com>

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
