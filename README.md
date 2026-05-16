# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Алексей Сидоров`
---

### Задание 1. Кеширование

Приведите примеры проблем, которые может решить кеширование.

1. Отказ системы при пиковых нагрузках
2. Высокая нагрузка на базу данных
3. Медленная загрузка страниц сайта
4. Нестабильный трафик



---

### Задание 2. Memcached

Установите и запустите memcached.


`Cкриншот, где видно, что memcached запущен:`

![img1](https://github.com/PhartomX/netology_redis_memcached/blob/main/img/img1.png)


---

### ЗЗадание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Введено 3 ключа: key1, key2 и key3.
У key1 и key2 установлен TTL 5, у key3 - 20.
Спустя 5 секунд key1 и key2 удалились из базы.

`Cкриншот с результатом выполнения:`

![img2](https://github.com/PhartomX/netology_redis_memcached/blob/main/img/img2.png)

---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями.

Введено 3 ключа: key1, key2 и key3.

`Cкриншот с результатом выполнения:`

![img3](https://github.com/PhartomX/netology_redis_memcached/blob/main/img/img3.png)


Для примера зададим для key1 TTL 10:

`Cкриншот с результатом выполнения:`

![img4](https://github.com/PhartomX/netology_redis_memcached/blob/main/img/img4.png)


---

### Задание 5*. Работа с числами

Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.

![img5](https://github.com/PhartomX/netology_redis_memcached/blob/main/img/img5.png)