# discourse-social-bbcode

Discourse plugin to allow inserting social buttons in topics.

Social buttons can be limited to some categories only by using the `discourse social bbcode categories` setting.

## Example

```
# Discourse Social BBCode Demo

## Twitter

[twitterfollow user=ProjCastafiore size=large][/twitterfollow]

[twittertweet size=large url=https://castafiore.org via=ProjCastafiore]I've just discovered this amazing new project![/twittertweet]

## Facebook

[facebook href=https://www.facebook.com/ProjetCastafiore share=true size=large][/facebook]

## Email

[mailtolink subject="Amazing!" body="I&apos;ve just discovered this amazing new project! www.castafiore.org"]Send to a friend[/mailtolink]

[mailtobutton btnclasses="btn-default btn btn-icon-text" subject="Amazing!" body="I&apos;ve just discovered this amazing new project! www.castafiore.org"]Send to a friend[/mailtobutton]

```

![](screenshot2.png)
