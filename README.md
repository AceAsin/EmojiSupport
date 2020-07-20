# Heroku Buildpack for Custom Fonts

Fonts used by [SimplyAgree](https://www.simplyagree.com) for generating custom PDF documents.

__WARNING: DO NOT POINT YOUR BUILDPACK CONFIG TO THIS PROJECT__

Heroku buildpack for installing various fonts on a SimplyAgree heroku instance.
This buildpack is very specific to our needs. It can __AND WILL__ change and __YOUR APP WILL BREAK__.

To recreate the `fonts.tar.gz` file on the command line use the following command 
inside the project directory:
`tar -zcvf fonts.tar.gz fonts`


## Original Inspiration
* https://github.com/debitoor/heroku-buildpack-converter-fonts
* https://raw.githubusercontent.com/lawgical/heroku-buildpack-custom-fonts

