---
layout: post
category : python 时间戳 datetime string 转换
tagline: ""

---
{% include JB/setup %}


```
import datetime
import time
```

<h4><a href="#t0">##datetime转时间戳</a></h4>

```
In [1]: now = datetime.datetime.now()
In [2]: time.mktime(now.timetuple())
Out[2]: 1433501775.0
```


----------
<h4><a href="#t1">##datetime转string</a></h4>

```
In [3]: now.strftime('%Y-%m-%d')
Out[3]: '2015-06-05'

In [4]: type(now.strftime('%Y-%m-%d'))
Out[4]: str
```

----------
<h4><a href="#t2">##string转datetime</a></h4>

<code>
In [5]: time_str = '2015-05-01 12:00:01'

In [5]: date_time = datetime.datetime.strptime(time_str,'%Y-%m-%d %H:%M:%S')

In [6]: date_time
Out[6]: datetime.datetime(2015, 5, 1, 12, 0, 1)

</code>


----------
<h4><a href="#t3">##时间戳转string</a></h4>

<code>
In [17]: time.strftime('%Y-%m-%d',time.localtime(aa))
Out[17]: '2015-06-05'
</code>
