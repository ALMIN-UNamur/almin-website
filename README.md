# ALMIN Website

_[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio (via Blogdown), generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with widgets, themes, and language packs._

- 👉 [**Get Started**](https://wowchemy.com/templates/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-modules/releases)

## Adding elements to the Website

### Committee members

Team members are listed in [content/authors/](content/authors/). Each team member has its own subdirectory, corresponding to their **firstname-lastname**. *Please use this identifier of the members of the team (i.e., firstname-lastname) instead of their full name when encoding authors for publications, projects, and news to ensure proper linking on the website.*

Each user must be part of one of the following user groups (`user_groups:` in the `_index.md` of the user):
- Présidence
- Membres
- 'Ancien membres'

More groups can be added in the [content/people/people.md](content/people/people.md) file.

Check [Wowchemy documentation](https://wowchemy.com/docs/content/authors/) to know more about profiles content.


Hugo command to add a team member:

```
hugo new --kind authors authors/firstname-lastname
```

### Posts and news

News are available in [content/post/](content/post/). Each news has its own subdirectory respecting the format `year-month-day-id`. Check the documentation on blog posts at [https://wowchemy.com/docs/content/blog-posts/](https://wowchemy.com/docs/content/blog-posts/).

Hugo command to add a news:

```
hugo new --kind post post/2020-10-08-mynews
```

### Events

Events are available in [content/event/](content/event/). Each event has its own subdirectory respecting the format `year-month-day-id`. Check the documentation on blog posts at [https://wowchemy.com/docs/content/events/](https://wowchemy.com/docs/content/events/).

Hugo command to add a news:

```
hugo new  --kind event event/2020-10-08-myevent
```

### Checklist before commit

Please check before comiting your changes that:

- authors of the committee have been added using their identifier, corresponding to the name of the folder [content/author/](content/author/) (for example, `xavier-devroey`), to ensure proper referencing on the website;
```
authors:
  - john-doe
  - Jane-doe
  - Another Author
```
