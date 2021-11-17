## [Code Fish](https://nighthawkcodingsociety.com/projectsearch/details/Flask%20Portfolio%20Starter)
Runtime link: https://portfolio.nighthawkcodingsociety.com/
### N22P4 CODEFISH
# Name in Progress
> Be productive and organized, no matter if you're a student or teacher!

## Ideation
The overall idea of our website is to assist all DNHS individuals in their educational experiences in both learning and teaching through effective organization and productivity. We have two modes, for students and teachers, allowing them to document each day through the usage of calendars, planners, quick feedback, etc. 

## Purpose
This is helpful to new teachers who might want to reference things about our school quickly or who might want to take attendance quickly. It gives students and opportunity to plan well and lets them know what they have to do each day, as well as allowing them to quickly communicate with peers and teachers.




| Name | Github Username | Issue | Journals | Commits |
| - | - | - | - | - | - |
| Saumya | saumyapalk233 | [Issues](https://github.com/raad1masum/AP-CSA-Tri-1-Project/issues/assigned/rpeddakama) | [Journal]
(https://docs.google.com/document/d/1EXl1swo0bu7gyd5L3cyih_qrAqvfPnW-5OEac6n07zs/edit?usp=sharing)
| [Commits](https://github.com/raad1masum/AP-CSA-Tri-1-Project/commits?author=rpeddakama) |
| Aryan | raad1masum | [Issues](https://github.com/raad1masum/AP-CSA-Tri-1-Project/issues/assigned/raad1masum) | [Journal](https://docs.google.com/document/d/1XdgObYAPpPuwJi6Kvq3mPO6OQn05WOdcwZ73aTua7e8/edit?usp=sharing) | [Commits](https://github.com/raad1masum/AP-CSA-Tri-1-Project/commits?author=raad1masum) |
| Vidhi | ArnavPalkhiwala | [Issues](https://github.com/raad1masum/AP-CSA-Tri-1-Project/issues?q=is%3Aopen+assignee%3A%40me) | [Journal](https://docs.google.com/document/d/14JUKWkG_LahbXd0Sn64hrhkVfYiie1kDjvrUdF9fts8/edit) | [Commits](https://github.com/raad1masum/AP-CSA-Tri-1-Project/commits?author=ArnavPalkhiwala) |
| Prisha | amanj31 | [Issues](https://github.com/raad1masum/AP-CSA-Tri-1-Project/issues/assigned/amanj31) | [Journal](https://docs.google.com/document/d/1DZxo0UIKQWJ7KLox5hkE96J63tFqWoBb3ydF6jgcSg0/edit?usp=sharing) | [Commits](https://github.com/raad1masum/AP-CSA-Tri-1-Project/commits?author=amanj31) |
| Arushi | amanj31 | [Issues](https://github.com/raad1masum/AP-CSA-Tri-1-Project/issues/assigned/amanj31) | [Journal](https://docs.google.com/document/d/1DZxo0UIKQWJ7KLox5hkE96J63tFqWoBb3ydF6jgcSg0/edit?usp=sharing) | [Commits](https://github.com/raad1masum/AP-CSA-Tri-1-Project/commits?author=amanj31) |
















## Add some color and fun through VANTA Visuals (birds, halo, solar, net)
#### Show some practical and fun links (hrefs) like Twitter, Git, Youtube
#### Show project specific links (hrefs) per page

### Implementation progress (August 13th, 2021)
#### Project entry point is main.py, this enables Flask Web App and provides capability to renders templates (HTML files)
#### The main.py is the  Web Server Gateway Interface, essentially it contains a HTTP route and HTML file relationship.  The Python code constructs WSGI relationships for index, kangaroos, walruses, and hawkers.
#### The project structure contains many directories and files.  The template directory (containing html files) and static directory (containing js files) are common standards for HTML coding.  Static files can be pictures and videos, in this project they are mostly javascript backgrounds.
#### WSGI templates: index.html, kangaroos.html, ... are aligned with routes in main.py.
#### Other templates support WSGI templates.  The base.html template contains common Head, Style, Body, Script definitions.  WSGI templates often "include" or "extend" these templates.  This is a way to reuse code.
#### The VANTA javascript statics (backgrounds) are shown and defaulted in base.html (birds), but are block replaced as needed in other templates (solar, net, ...)
#### The Bootstrap Navbar code is in navbar.html. The base.html code includes navbar.html.  The WSGI html files extend base.html files.  This is a process of management and correlation to optimize code management.  For instance, if the menu changes discovery of navbar.html is easy, one change reflects on all WSGI html files. 
#### Jinja2 variables usage is to isolate data and allow redefinitions of attributes in templates.  Observe "{% set variable = %}" syntax for definition and "{{ variable }}" for reference.
#### The base.html uses combination of Bootstrap grid styling and custom CSS styling.  Grid styling in observe with the "<Col-3>" markers.  A Bootstrap Grid has a width of 12, thus four "Col-3" markers could fit on a Grid row.
#### A key purpose of this project is to embed links to other content.  The "href=" definition embeds hyperlinks into the rendered HTML.  The base.html file shows usage of "href={{github}}", the "{{github}}" is a Jinja2 variable.  Jinja2 variables are pre-processed by Python, a variable swap with value, before being sent to the browser.

### IDE management (things that happened beyond plan)
#### Recall on ".gitignore" solution to the pains of temporary files.  Start a ".gitignore" and avoid promoting temporary files to Git, for instance IDE xml files.
#### A project needs to establish a "requirements.txt" to keep track of Python packages used by the project.  This help in other IDEs and Deployment.  IntelliJ has menu Tool -> Sync Python Requirements to start file. 
