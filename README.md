# Домашнее задание к занятию 1 «Введение в Ansible»

## Основная часть

1. Попробуйте запустить playbook на окружении из `test.yml`, зафиксируйте значение, которое имеет факт `some_fact` для указанного хоста при выполнении playbook.
<p align="center">
  <img src="ansible-01-base_1.png" width="800">
</p>  

2. Найдите файл с переменными (group_vars), в котором задаётся найденное в первом пункте значение, и поменяйте его на `all default fact`.
<p align="center">
  <img src="ansible-01-base_2.png" width="800">
</p>  

3. Воспользуйтесь подготовленным (используется `docker`) или создайте собственное окружение для проведения дальнейших испытаний.
<p align="center">
  <img src="ansible-01-base_3.png" width="800">
</p>  

4. Проведите запуск playbook на окружении из `prod.yml`. Зафиксируйте полученные значения `some_fact` для каждого из `managed host`.
<p align="center">
  <img src="ansible-01-base_4.png" width="800">
</p>  

5. Добавьте факты в `group_vars` каждой из групп хостов так, чтобы для `some_fact` получились значения: для `deb` — `deb default fact`, для `el` — `el default fact`.
<p align="center">
  <img src="ansible-01-base_5.png" width="800">
</p>  

8. Запустите playbook на окружении `prod.yml`. При запуске `ansible` должен запросить у вас пароль. Убедитесь в работоспособности.
<p align="center">
  <img src="ansible-01-base_8.png" width="800">
</p>  

11. Запустите playbook на окружении `prod.yml`. При запуске `ansible` должен запросить у вас пароль. Убедитесь, что факты `some_fact` для каждого из хостов определены из верных `group_vars`.
<p align="center">
  <img src="ansible-01-base_11.png" width="800">
</p>  
