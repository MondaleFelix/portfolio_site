

How is this project structure different than a Flask (or Node) application? What role are the urls.py and views.py files responsible for?

Django modularizes applications by allowing a project to have different apps. In contrast to Flask, each project is its own applications. The role of the urls.py and views.py is to map custom url patterns to specified views


Why do we use 2 separate urls.py files? How do they interact?

We use separate urls.py files to modularize the components. The urls.py in main application cuts out the slug and sends it to the other urls.py file which then triggers the corresponding view function



When is it desirable to split our code over multiple apps? Why would we want to do so?

When we want to reuse a functionality we already wrote somewhere else. To save time and energy.