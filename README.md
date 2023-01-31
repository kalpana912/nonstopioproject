"# nonstopioproject" product application

## Setup

The first thing to do is to clone the repository:

```cmd
 git clone  https://github.com/kalpana912/nonstopioproject.git
>>source cd nonstopioproject
```

Create a virtual environment to install dependencies in and activate it:

>> source virtualenv env
>>source env/scripts/activate
```

Then install the dependencies:

```sh
(env)$ pip install django
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
>> nonstopproject\djangoproject>
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/`.


## Walkthrough

To run the application run tha command python manage.py runserver in command prompt.
it will give `http://127.0.0.1:8000/'this url. open this url in any browser.after running it will shoe list of project endpoints url.
type any end point after localhost. it will show you the result.






