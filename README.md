# drf_2

## Task
ДЗ:
1. Переписать все существующее api (юзеры, посты, категории) используя ModelSerializer и ModelViewSet.  # Done

2. Реализовать токен аутентификацию (можно использовать сторонние библиотеки)  # 50/50

3. Реализовать проверку пермишенов по таким критериям:

    создавать пользователя (регистрироваться) может любой пользователь,  # Done

    просматривать посты и категории может любой пользователь,  # Done

    создавать посты могут только аутентифицированные пользователи,  # Done

    редактировать/удалять пост может только автор поста,  # Done

    создавать/редактировать/удалять категории могут только пользователи с is_staff=True  # Done

4. При создании поста, автор не должен указываться вручную - подставлять залогиненого пользователя  # Done

5. Использовать вложенные структуры данных в представлениях (например в представлении поста отображать не pk юзера, а сериализированный инстанс юзера)  # Done

6. Подключить сваггер, ознакомиться  # Done

## Install

create env

activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver