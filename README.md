# Hello, CSIT!

Это небольшой сайт, созданный специально для первокурсников КНиИТа. Здесь ты сможешь найти интересные статьи, которые помогут тебе получить максимум из первого курса.

## Как работать с репозиторием

1. Создать новую ветку: `article/name-of-article-file`;
1. В этой ветке создать файл `name-of-article-file.md` в папке `articles`;
1. Поместить ссылку на него в начале *Последние статьи* в `index.md`;
1. Написать саму статью, используя только `markdown`. Файл должен полностью
   соответствовать линтеру
   [MarkdownLint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint), кроме
   [MD033](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md#md033)
   (inline html разрешён, например для ссылок, которые должны открываться в
   новой вкладке);
1. Если эта ваша первая статья на сайте и у вас ещё нет странички с информацией,
   создайте `your-name.md` в папке `authors`, где укажите вашу группу или просто
   курс и направление, а также способы с вами связаться;
1. В Самом начале необходимо указать метаданные статьи:

      ---
      layout: default
      nav_order: x
      description: "ОПИСАНИЕ"
      last_modified_date: "2021-08-24"
      ---

1. В самом конце статьи нужно указать себя в качестве автора:

		> Автор: [ТВОЁ ИМЯ](authors/YOUR_NAME.md)

1. Протестировать сайт локально можно, используя
   [этот туториал](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekylltesting-your-github-pages-site-locally-with-jekyll);
1. Если всё готово, создать *Pull request*, добавив в *Reviewers* хотя бы одного
   человека.
