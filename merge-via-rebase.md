# merge (слияние) и rebase (перебазирование)
## В данной статье мы рассмотрим обе операции и отличия между ними, а также обозначим моменты, требующего особого внимания.
## https://medium.com/nuances-of-programming/владеешь-merge-освой-и-rebase-412e36bddce2

### Сначала с помощью анимационных средств разберем каждую операцию по отдельности, а на заключительном этапе проведем параллельное сравнение. Если вам уже знакомы принципы работы этих действий, то сразу переходите к сравнительным характеристикам.
### Согласно официальному руководству Git rebase “повторно применяет коммиты поверх другой базовой ветки”, тогда как merge “объединяет две или более историй разработки”. Иначе говоря, основное отличие между ними в том, что слияние сохраняет историю в первозданном виде, а перебазирование ее перезаписывает.