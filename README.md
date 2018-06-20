# OctoberCMS RainLab Blog 
###### Adding the author's functionality to the blog pages

To add the functionality of the author's page, I use a component that I call inside the author's page.

The author's page in my case shows all the articles of the blog that the specific user of the system created.

The functionality of the author's page is similar to the category page or the main page of the blog.

This component is also connected to components:
 * blogCategories
 * searchForm
 * CategoryBreadCrumbs
 * blogPost. 

You can see this at the beginning of the code.

Also, this component is filled with a php-section, which facilitates the output of the ID-user, who is the author of the article.

You can print the author using:
1. {{ post.user.first_name }} - will output user first name
2. {{ post.user.last_name }} - will output user last name
3. {{ post.user.login }} - will output user login

*The code is commented, you can edit it if necessary.*


# OctoberCMS RainLab Blog 
###### Добавление функциональности автора к страницам блога

Для добавления функциональности страницы автора я использую компонент, который вызываю внутри страницы автора.

Страница автора в моём случае показывает все статьи блога, который создал определенный пользователь системы. 

Функциональность страницы автора схожая на страницу категории или главную страницу блога. 

Данный компонент подключен также к компонентам: 
 * blogCategories
 * searchForm
 * CategoryBreadCrumbs
 * blogPost. 

Вы можете увидеть это в начале кода. 

Также, у данного компонента заполнена php-секция, которая способствует выводу ID-пользователя, который является автором статьи. 

Выводить автора можно с помощью:
1. {{ post.user.first_name }} - выведет имя пользователя
2. {{ post.user.last_name }} - выведет фамилию пользователя
3. {{ post.user.login }} - выведет логин пользователя 

*Код снабжён комментариями, Вы можете отредактировать его по необходимости.* 