# Heroku Sleep Page

This is a template for Heroku error page showing your sleep hours for free dyno.

[DEMO](https://notsobad-jp.github.io/herokusleep/sleep.html)

The page design from Better Error Pages by StatusPage.io.

[Better Error Pages](https://better-error-pages.statuspage.io/)


## Usage

Heroku docs for setting custom error page is this:

[Error Pages | Heroku](https://devcenter.heroku.com/articles/error-pages)


If you want to use DEMO page as it is,  
just run the following command:

    heroku config:set \
    ERROR_PAGE_URL=//notsobad-jp.github.io/herokusleep/


## Customize

If you would like to customize the error page,  
clone this repository and change as you like.

The background color and text color are defined at about line 129.
