# Необходимый функционал, который был дан в ТЗ для реализации:
	1. Страницы добавления, изменения и удаления человека.
	2. Страницы добавления, изменения и удаления книги
	3. Страница со списком всех людей (люди кликабельные - при клике осуществляется
	переход на страницу человека).
	4. Страница со списком всех книг (книги кликабельные - при клике осуществляется
	переход на страницу книги).
	5. Страница человека, на которой показаны значения его полей и список книг, которые он
	взял. Если человек не взял ни одной книги, вместо списка должен быть текст "Человек
	пока не взял ни одной книги".
	6. Страница книги, на которой показаны значения полей этой книги и имя человека,
	который взял эту книгу. Если эта книга не была никем взята, должен быть текст "Эта
	книга свободна".
	7. На странице книги, если книга взята человеком, рядом с его именем должна быть кнопка
	"Освободить книгу". Эта кнопка нажимается библиотекарем тогда, когда читатель
	возвращает эту книгу обратно в библиотеку. После нажатия на эту кнопку книга снова
	становится свободно и пропадает из списка книг человека.
	8. На странице книги, если книга свободна, должен быть выпадающий список (<select>)
	со всеми людьми и кнопка "Назначить книгу". Эта кнопка нажимается библиотекарем
	тогда, когда читатель хочет забрать эту книгу домой. После нажатия на эту кнопку, книга
	должна начать принадлежать выбранному человеку и должна появится в его списке
	книг.
	9. Все поля должны валидироваться - с помощью @Valid и Spring Validator, если это
	требуется.

# Использованные технологии:
	1.Spring MVC
	2.JdbcTemplate
	3.Hibernate Validator
	4.Postgresql
	5.Thymeleaf


# Necessary functionality that was given  for implementation:
	1. Pages for adding, changing and deleting a person.
	2. Pages for adding, editing and deleting a book
	3. A page with a list of all people (people are clickable - when clicked,
	go to person's page).
	4. A page with a list of all books (books are clickable - when clicked,
	go to the page of the book).
	5. The person's page, which shows the values of his fields and the list of books that he
	took. If the person did not take any books, instead of the list should be the text "Man
	I haven't picked up a single book yet."
	6. A page of a book, which shows the values of the fields of this book and the name of the person,
	who took this book. If this book has not been taken by anyone, the text "This
	the book is free.
	7. On the page of the book, if the book is taken by a person, next to his name there should be a button
	"Release book". This button is pressed by the librarian when the reader
	returns this book back to the library. After pressing this button the book again
	becomes loose and disappears from the list of the person's books.
	8. On the page of the book, if the book is free, there should be a drop-down list (<select>)
	with all people and the "Assign Book" button. This button is pressed by the librarian
	when the reader wants to take this book home. After pressing this button, the book
	must begin to belong to the selected person and must appear in his list
	books.
	9. All fields must be validated - with @Valid and Spring Validator if so
	required.

# Technologies used:
	1.Spring MVC
	2.JdbcTemplate
	3. Hibernate Validator
	4. PostgreSQL
	5.Thymeleaf