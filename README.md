#getgo

getgo is a simple shell script that I use to setup Django development environments.

It uses virtualenv, pip, and my [django-project-template](https://github.com/ebradbury/django-project-template).

##Requirements

`virtualenvwrapper`

##Usage

Clone the repository and edit the settings in the script.

`chmod +x getgo`

`. ./getgo <project_name>`

Note the "dot space dot slash" format used when executing the script. This will run the script in the current shell.
