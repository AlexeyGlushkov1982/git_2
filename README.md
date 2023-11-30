# Контроль версий углублённо (GIT) (семинары)

## Урок 2. Работа с изменениями

1. Просмотрите историю коммитов в своём проекте и выберите три случайных коммита. Просмотрите изменения, которые были в них сделаны.

2. Верните эти изменения командой git revert последовательно, чтобы в итоге получилось тоже три коммита.

![revert.png](revert.png)

3. Попробуйте отменить эти три коммита:


* последний — командами git reset --soft и git restore;

![reset--soft.png](reset--soft.png)

![restore_reset--soft.png](restore_reset--soft.png)


* предпоследний — командой git reset --mixed и git restore;

![reset--mixed.png](reset--mixed.png)


* первый — командой git reset --hard.

![reset--hard.png](reset--hard.png)