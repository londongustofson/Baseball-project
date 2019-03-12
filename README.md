# Baseball-project

Analyzed various statistics and outcomes regarding stolen bases, pitching accuracy, and salary earnings. Visualized and illuminated current trends in baseball using Flask, MySQL, JavaScript, HTML, and Python. Displayed the visualizations on a dashboard, these included a heat map, bubble charts and other informative plotting’s.
The Story:

Data analytics within baseball is one of the fastest growing aspects of professional sports. All components of the game are now thoroughly analyzed by analyst and various metrics. In our group project, we selected some popular aspects of the game in hopes of examining presumed trends surrounding them.

Data Source

Data Source: For this project we used a python api ,PyBaseball, that pulls recorded statistics from FanGraphs and Baseball Savant.

Follow along!

Run Create_DB_and_Tables.sql in MySQL Workbench.
Change mysql password in data-clean-import-sql.ipynb
Run data-clean-import-sql.ipynb in jupyter notebook.
To run Flask server:

Open Terminal and change you directory to "Flask" folder.
Change mysql password in app.py Note: each route has its own DB connection, password needs to be updated for all of them
Run chmod +x run.sh
Run ./run.sh
Open http://localhost:5000/
