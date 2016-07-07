Selenium plugin for Selenium. This is very heavily based on the official redis plugin.

    dokku selenium:selenium:create chrome
    dokku selenium:link chrome <app>
    dokku selenium:promote chrome banking-check

The URL you then need is something like:

    http://dokku-selenium-chrome:4444/wd/hub