# Задача "Чистый код S1E1"

## Описание: 

![image](clean-code.png)

Перед вами небольшое одностраничное [веб-приложение TODO-list](https://github.com/ViktoryiaYatskova/clean-code-s1e1).
Ваша задача – навести порядок внутри файлов кода (_рефакторинг_) согласно следующим руководствам:
 [тут](html-and-css.md)
 и [тут](html-and-css-extended.md) (только html- и css-файлы). 
При этом функционал приложения должен остаться рабочим после ваших изменений.

## Требования к выполнению

**Внимание!** Задача не может быть принята, если все условия ниже не выполнены:

- Используйте личный ПУБЛИЧНЫЙ репозиторий в GitHub для выполнения данного задания.
 Сделайте fork существующего проекта или просто создайте пустой проект и скопируйте туда файлы.
- Один git-коммит должен содержать изменения согласно одному пункту из руководств
(можно несколько коммитов на один пункт руководства, но не наоборот).
Обязательно укажите, какой пункт покрывают изменения в данном коммите.
- Покрытие коммитом двух правил допустимо, если соблюдение одного правила автоматом гарантируем соблюдение другого.
В этом случае оба правила должны быть указаны в commit message.
- Коммит-сообщения должны быть составлены согласно [следующим правилам](commits.md).
- Изменения делайте в ветке `clean-code-s1e1`, созданной от `main`.
 Изучите и используйте максимально возможности вашей IDE для рефакторинга (ниже есть ссылки для VS Code)

_Пример:_
```
fix: add Html5 DOCTYPE tag according to rule 2.2 in html-and-css.md
refactor: adjust HTML-formatting according to rule 2.1 in html-and-css.md
```

- Весь функционал приложения должен исправно работать после ваших изменений, а именно:

    - Добавление нового элемента в список задач "TODO".
    - Редактирование элемента в списке задач "TODO".
    - Удаление элемента из списка задач "TODO".
    - Установка элемента в статус завершенного и перенос в список "COMPLETED" через checkbox.

    - Удаление элемента из списка "COMPLETED".
    - Редактирование элемента в списке "COMPLETED".
    - Установка элемента в статус незавершенного и перенос в список "TODO" через checkbox.

    - Внешний вид приложения не изменился.
    - Анимация на кнопке удаления работает.

## Критерии оценки

**Максимальный балл за задание +45**

- Каждый из 15 пунктов [первого](materials/html-and-css.md) руководства соблюден:
    - +2 за каждое ПОЛНОСТЬЮ выполненное правило
    (т.е. правило должно быть соблюдено для всего документа, а не только для кусочка кода).
- Каждый из 3 пунктов [расширенного руководства](materials/html-and-css-extended.md) соблюден: 
    - +5 за каждое ПОЛНОСТЬЮ выполненное правило.

Внимание! Аккуратно выполняйте переименование атрибутов, не пропустив ни единного их вхождения, включая JS-файлы.

## Cross-check
- форма для проверки задания: https://rolling-scopes-school.github.io/checklist/ (пункт "Clean code S1E1");
- инструкция по проведению cross-check: https://docs.rs.school/#/cross-check-flow.
