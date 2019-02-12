# PDI-clickhouse

В данном репозитарии собраны все необходимые jar для подлкючение к Clickhouse. Версия драйвера clickhouse-jdbc-0.1.50.jar.
Все содержимое папки jdbc нужно скопировать в папку ../lib и произвести подлючение через Generic Database как на картинке:
- Custom connection URL: jdbc:clickhouse://IP:8123/database
- Custom driver class name: ru.yandex.clickhouse.ClickHouseDriver
![Connect](/img/Click_connect.png)

# Технические характеристики
- openjdk-8-jdk
- PDI CE 8.2.0.0-342 или PDI CE 7.1.0.0-12
