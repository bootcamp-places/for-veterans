# Як створити запит на сервер?

Для відправки запиту на сервер за допомогою JavaScript в браузері використовується `fetch`. 

Ось простий приклад:

```javascript
// URL, на який ви хочете відправити запит
const apiUrl = 'https://example.com/api';

// Налаштування для запиту
const requestOptions = {
  method: 'GET', // або 'POST', 'PUT', інші методи
  headers: {
    'Content-Type': 'application/json', // тип вмісту (якщо ви відправляєте JSON)
    // Додаткові заголовки можна додати тут
  },
  // body: JSON.stringify(data) // Якщо ви відправляєте дані, наприклад, у форматі JSON
};

// Відправка запиту за допомогою fetch
fetch(apiUrl, requestOptions)
  .then(response => {
    // Перевірка, чи запит відповів з успіхом (з кодом 200-299)
    if (!response.ok) {
      throw new Error(`HTTP error! Статус: ${response.status}`);
    }
    // Повернення відповіді у форматі JSON
    return response.json();
  })
  .then(data => {
    // Обробка отриманих даних
    console.log(data);
  })
  .catch(error => {
    // Обробка помилки
    console.error('Виникла помилка:', error);
  });
```

У цьому прикладі `fetch` відправляє GET-запит на сервер. Ви можете змінити `method` на 'POST', 'PUT', 'DELETE' або інший метод, відповідно до вашого випадку використання.
