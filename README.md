# notes from TDI
This serves as a note of all the resources and trouble-shootings encoutered while doing TDI projects


Resources
=========
Flask + Heroku （in decreasing order of usefulness)
----------------------------------------------------------------
https://github.com/bev-a-tron/MyFlaskTutorial (by Beverley!)

http://flask.pocoo.org/docs/0.10/quickstart/#quickstart

https://realpython.com/blog/python/python-web-applications-with-flask-part-i/

http://virantha.com/2013/11/14/starting-a-simple-flask-app-with-heroku/


simpleJSON
----------
http://simplejson.readthedocs.org/en/latest/

Heroku
------
https://devcenter.heroku.com/articles/git

Flask-Bootstrap for webapp development
--------------------------------------
https://pythonhosted.org/Flask-Bootstrap/

pandas
------
https://github.com/physiophile/pandas-exercises

http://pandas.pydata.org/

beautiful soup (jQuery + python)
------
http://www.crummy.com/software/BeautifulSoup/bs4/doc/

regular expression
------------------
https://docs.python.org/2/library/re.html

numpy
-----
http://wiki.scipy.org/NumPy_for_Matlab_Users (numpy for matlab users)

http://www.engr.ucsb.edu/~shell/che210d/numpy.pdf

python
------
https://developers.google.com/edu/python/ 

https://www.codecademy.com/tracks/python

http://www.siafoo.net/article/52 (python tricks)


useful python snippet
=============
How to convert time series
```python
ddf = DataFrame(data)
ddf.columns = data_columns
ddf.index = to_date_time(ddf.pop('Date'))
# an slower alternative
# ddf = ddf.set_index('Date')
```
