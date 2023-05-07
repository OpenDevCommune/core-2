## **Project Model**

---


### **Описание :**

В этом файле представлены основные  данные в которых есть необходимость запрашивать , сохранять , извлекать , удалять , изменять. Есть несколько этапов на которых требуюется запросить некоторые данные пользователя.

---

## **Добавление проекта**

При регистраций пользователя , платформа запрашивает следующие поля : 
 
| №     |  ИМЯ ПОЛЯ  | КРАТКОЕ ОПИСАНИЕ
|:-----:|:------------:|----------------- 
| 1     | Название проекта      | Является обязательным полем. Представляет собой строку в виде название проекта
| 2     | Описание идеи проекта    | Является обязательным и представляет собой описание проекта
| 3     | Документация проекта    | Является обязательным полем. Представляет собой архив нескольких файлов, описывующие документацию проекта.
| 4     | Стадия проекта      | Является обязательным полем для заполнения, указывается текущая стадия проекта(Проектирование/Аккумуляция/Реализация/Сопровождение)
| 5     | Бюджет проекта    | Является обязательным и представляет собой оценочную стоимость проекта, желательно в токенах платформы.
| 6     | Автор проекта    | Является обязательным полем. Представляет собой перечисление авторов проекта который принимали участие в разработке проекта

После того как пользователь ввел данные проекта в предоставленную форму , проекты должны отображаться в профиле пользователя в разделе **Проекты**.

---

## Раздел редактирования проекта пользователя 

После возвращени пользователю страницы с его профилем , у пользователя будет возможность редактировать данные проекта. Для этого на странице пользователя будет находится кнопка **Edit Project** после нажатия на которую пользователя адресует на страницу где предоставлены следующие поля для редактирования : 



| №     |  ИМЯ ПОЛЯ                                |
|:-----:|:----------------------------------------:|
| 1     | name                                  |
| 2     | description                                 | 
| 3     | documentation                                |
| 4     | stage                              | 
| 5     | budget                                 | 
| 6     | author                                   |  


Пользователь может редактировать каждое из них. После того как пользователь внес изменения в некоторые поля , он может нажать на кнопку save после чего данные отправятся на платформу , откуда потом должны сохранится в некотором хранилище данных.