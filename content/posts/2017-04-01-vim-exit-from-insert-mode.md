---
title: Выход из режима вставки
date: 2017-04-01
categories:
    - develop
tags: 
    - vim
    - rus
---

Помимо стандартных способов выхода из режима вставки в Vim:

* \<esc\>
* \<c-c\>
* \<c-[\>

Можно предложить такой **inoremap jk \<esc\>**. Разгружает левую руку, 
единственный минус - слова с буквами jk.
