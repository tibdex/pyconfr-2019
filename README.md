Link to the slides: [Dynamic dataviz in Python](https://www.slideshare.net/ThibaultDerousseaux/dynamic-dataviz-in-python)

Python is today the main language for data analysis, but one step remains slow and not optimized: going from the notebook to visualization in BI applications for business users.
In almost all cases, you need to rewrite the code in the language of the BI application, it's slow and badly suited to an agile approach with successive iterations.

At ActiveViam, we wanted to accelerate this process and design a system to skip this step entirely.
The goal of the project is to put the visualization directly inside the notebook, not only static graphs but something truly dynamic.

The result I'm presenting is a Python library with a community edition to visualize data continuously as we load them and work on the model in our Python notebook.
It's useful to make you own analysis but mostly when you need to build dashboards that will be used by other services in the company.
The back-and-forths with the business are much faster and once the content and layout of the dashboard is validated by the end users, going to production is also quick since it can be done in a few clicks.
With this system, you don't just build a preview or a mock-up with Python but really the final analytic application.
