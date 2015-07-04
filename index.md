---
layout: page
title: 嗖嗖
tagline: 嗖嗖
---
{% include JB/setup %}


## Hello EveryOne


    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do


<div ng-app="blogposts" ng-init="names=[
{name:'Jani',country:'Norway'},
{name:'Hege',country:'Sweden'},
{name:'Kai',country:'Denmark'}]" ng-controller="personController">
  <p>在输入框中尝试输入：</p><p ng-bind="name"></p>
  <p>姓名：<input type="text" ng-model="name"></p>
  <h2>价格计算器</h2>

数量： <input type="number" ng-model="quantity">
价格： <input type="number" ng-model="price">

<p><b>总价：</b> {[{ quantity * price }]}</p>

  <p>使用 ng-repeat 来循环数组</p>
  <ul>
  <li ng-repeat="x in names">
    {[{ x.name + ', ' + x.country }]}
  </li>
  </ul>


<button ng-click="toggle()">隐藏/显示</button>

<p ng-show="myVar">
名： <input type="text" ng-model="person.firstName"><br>
姓： <input type="text" ng-model="person.lastName"><br>
<br>
姓名： {[{person.firstName + " " + person.lastName}]}
</p>

<p>
<button ng-disabled="mySwitch">点我！</button>
</p>

<p>
<input type="checkbox" ng-model="mySwitch">按钮
</p>


<button ng-click="count = count + 1">点我！</button>
<p>{[{ count }]}</p>
</div>




