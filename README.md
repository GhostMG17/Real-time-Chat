# Real-time Chat Application

Это Spring Boot приложение для чата в реальном времени с использованием WebSocket и STOMP.

## Функционал
- Реальное время общения между пользователями
- WebSocket соединение через STOMP
- Автоперенаправление на страницу чата при открытии `/`

## Технологии
- Java 17
- Spring Boot 3
- WebSocket + STOMP
- HTML / JS / CSS для фронта

## Запуск локально
1. Собрать проект:
```bash
mvn clean package
```
2. Запустить jar: 
java -jar target/app-0.0.1-SNAPSHOT.jar
```bash
java -jar target/app-0.0.1-SNAPSHOT.jar
```
3. Открыть в браузере:
```bash
http://localhost:8080/
```
## Ссылка на приложение
[Real-time Chat Application](https://real-time-chat-mg-157cfe77fa11.herokuapp.com/chat)