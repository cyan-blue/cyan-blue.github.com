---
layout: post
category : "Python"
tagline: ""

---
{% include JB/setup %}

    ---
    import datetime
    import time
    ---

##datetime转时间戳

    ---
    In [1]: now = datetime.datetime.now()
    In [2]: time.mktime(now.timetuple())
    Out[2]: 1433501775.0
    ---
----------

##datetime转string

    ---
    In [3]: now.strftime('%Y-%m-%d')
    Out[3]: '2015-06-05'
    In [4]: type(now.strftime('%Y-%m-%d'))
    Out[4]: str
    ---
----------

##string转datetime

    ---
    In [5]: time_str = '2015-05-01 12:00:01'
    In [5]: date_time = datetime.datetime.strptime(time_str,'%Y-%m-%d %H:%M:%S')
    In [6]: date_time
    Out[6]: datetime.datetime(2015, 5, 1, 12, 0, 1)
    ---
----------

##时间戳转string
    ---
    In [17]: time.strftime('%Y-%m-%d',time.localtime(aa))
    Out[17]: '2015-06-05'
    ---
