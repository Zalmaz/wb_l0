# wb_l0

Запустить докер командой

docker-compose up --build -d

![img.png](img.png)

сервер будет находиться на локалхост 8080
http://localhost:8080/

![img_1.png](img_1.png)

Для входа в бд необходимо открыть контейнер с бд и в терминалле ввести:

psql -U almaz -d l0

После того как вы войдете в своего пользователя введите:

select id from orders;

![img_2.png](img_2.png)

