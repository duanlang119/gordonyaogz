---
title: hello 我的世界
date: 2016-10-15 12:23:41
categories:  algorithm
tags: 
	- tags1
	- tag2
	- helloWorld
---


您好！ 欢迎来到我的个人技术博客

学习大家的方法。

{% plantuml %}

(*) --> if "Some Test" then

  -->[true] "activity 1"
  
  if "" then
    -> "activity 3" as a3
  else
    if "Other test" then
      -left-> "activity 5"
    else
      --> "activity 6"
    endif
  endif
  
else

  ->[false] "activity 2"
  
endif

a3 --> if "last test" then
  --> "activity 7"
else
  -> "activity 8"
endif

{% endplantuml %}