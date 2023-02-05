# FLASK PROJECT - TODO LIST

1) Install pip3 virtualenv -- 
![img](img/flask1.PNG)
![img](img/flask2.PNG)
<code> python3 -m venv myenv</code> <br>
<code>myenv\Scripts\activate.bat</code>
<br>
<code> pip3 install flask flask-sqlalchemy</code> <br>
<code>python3 app.py</code>
![img](img/flask3.PNG)
2) create new folder (static, templates)
3) import render_template
4) create index.html - return index

![img](img/flask4.PNG)

5) Template inheritence - create skeleton
   - one master html side
   - all have to do it once

![img](img/flask5_block.PNG)
![img](/img/flask_block_base.PNG)

6) Create css file, link to HTML file as so:
![img](img/flask6_csslink.PNG)

7) Initialize DB ( import from flask_sqlcademy)
8) Create Todo class 
- create ID column of each entry 
- text column - what holds each task
- date time when created auto
- 
9) Create function to return string when create new element

![img](/img/flask-db.PNG)