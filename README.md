# Проект K0T1K1: Веб-интерфейс для анализа покрытия аудитории

![site](img/2024-07-08_01-09.png)

Этот проект представляет собой веб-интерфейс с картой города, разбитого на сектора (полигоны), который позволяет пользователю оптимально определить количество сторон и количество сторон в каждом секторе для обеспечения максимального охвата аудитории.

## Описание

### Функциональность

- **Разбиение города на сектора**: Пользователь может указать количество сторон, на которое нужно сделать расчет. Система автоматически вычисляет оптимальные сектора и количество сторон в каждом секторе для максимального охвата аудитории.
- **Визуализация**: Отображение секторов на карте и предоставление оценки охвата каждого района в цифровом формате.
- **Прогнозирование**: Возможность загрузки набора произвольных точек (включая ранее не использованные в датасете) для получения прогнозного значения охвата по ним.

### Идеальный вариант использования

Пользователь заходит в интерфейс, видит карту города и указывает количество сторон для расчета. Система вычисляет и отображает оптимальные сектора и количество сторон в каждом секторе на карте, а также предоставляет цифровую оценку охвата каждого района. Пользователь также может загрузить собственный набор точек для анализа.

## Технологии

- **Frontend**: JavaScript, HTML, CSS
- **Backend**: Go, Python, PostgreSQL, Redis
- **ML**

## Наш сайт
-  Cайт(http://95.163.223.108:3000/)
