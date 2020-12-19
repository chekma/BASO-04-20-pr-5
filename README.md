# BASO-04-20-pr-5

1 )Сначала устанавливаем утилиту :

<a href="https://ibb.co/J5x9VJF"><img src="https://i.ibb.co/J5x9VJF/image-2020-12-19-144805.png" alt="image-2020-12-19-144805" border="0"></a>

узнаём тип hash

<a href="https://ibb.co/1z5FKPX"><img src="https://i.ibb.co/1z5FKPX/image-2020-12-19-145145.png" alt="image-2020-12-19-145145" border="0"></a>

<a href="https://ibb.co/9vqYkjB"><img src="https://i.ibb.co/9vqYkjB/image.png" alt="image" border="0"></a>


2)Теперь будем создавать hash в Linux.

сначала создаём нового пользователя

<a href="https://ibb.co/YDmN13p"><img src="https://i.ibb.co/YDmN13p/image.png" alt="image" border="0"></a>

Далее нужно было заметить hash и пароль , но это у меня не получилось.

3)Проверка контрольных сумм

Берём в копируем group в домашнюю папку

<a href="https://ibb.co/6w2VGJJ"><img src="https://i.ibb.co/6w2VGJJ/image.png" alt="image" border="0"></a>

Далее, считаем контрольную сумму с помощью команды sha1sum group

<a href="https://ibb.co/FxJK597"><img src="https://i.ibb.co/FxJK597/image.png" alt="image" border="0"></a>


<a href="https://ibb.co/QNxqmxB"><img src="https://i.ibb.co/QNxqmxB/image.png" alt="image" border="0"></a>

Мы удалили первую строчку и видим 

<a href="https://ibb.co/XY4fR1v"><img src="https://i.ibb.co/XY4fR1v/image.png" alt="image" border="0"></a>

<a href="https://ibb.co/yy6mGHK"><img src="https://i.ibb.co/yy6mGHK/image.png" alt="image" border="0"></a>

4)Шифрование файлов с помощью пароля

Создадим пустой файл с помощью команды touch и поставим на него пароль

<a href="https://ibb.co/kKvCqv3"><img src="https://i.ibb.co/kKvCqv3/image.png" alt="image" border="0"></a>

<a href="https://ibb.co/XJtcmc3"><img src="https://i.ibb.co/XJtcmc3/image.png" alt="image" border="0"></a>

5)шифрование с помощью ключа

Создадим файл + ключик к нему

<a href="https://ibb.co/8YjF6jq"><img src="https://i.ibb.co/8YjF6jq/image.png" alt="image" border="0"></a>

ключи созданы

доступные ключи 

<a href="https://ibb.co/rbSfkxH"><img src="https://i.ibb.co/rbSfkxH/image.png" alt="image" border="0"></a>

Экспортируем, потом импортируем

<a href="https://ibb.co/S3cZ9n1"><img src="https://i.ibb.co/S3cZ9n1/image.png" alt="image" border="0"></a>

воспользуемся редактором ключей, чтобы повысить уровень достоверности

<a href="https://ibb.co/0CRZhpP"><img src="https://i.ibb.co/0CRZhpP/image.png" alt="image" border="0"></a>

6)Подписи и шифрование

До изменения 

<a href="https://ibb.co/Vm0JjtT"><img src="https://i.ibb.co/Vm0JjtT/image.png" alt="image" border="0"></a>

после

что-то пошло не так 

<a href="https://ibb.co/BKmfhWD"><img src="https://i.ibb.co/BKmfhWD/image-2020-12-19-154304.png" alt="image-2020-12-19-154304" border="0"></a>






