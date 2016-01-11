# Heroku Sleep Page

This is a template for Heroku error page showing your sleep hours for free dyno.

![](https://notsobad-jp.github.io/herokusleep/error.png)

[DEMO](https://notsobad-jp.github.io/herokusleep/)


## Usage

Heroku docs for setting custom error page is this:

[Error Pages | Heroku](https://devcenter.heroku.com/articles/error-pages)


If you need no change for this DEMO,  
just run the following command:

    heroku config:set \
    ERROR_PAGE_URL=//notsobad-jp.github.io/herokusleep/


## Customize

If you would like to customize the error page,  
clone this repository and change it as you like.

The background color and text color are defined at about line 129.


## Credit
The page design is from Better Error Pages by StatusPage.io.

[Better Error Pages](https://better-error-pages.statuspage.io/)
