# **Домашнее задание к занятию «Системы контроля версий»**

---

### Задание 1. Создать и настроить репозиторий для дальнейшей работы на курсе

**Создание репозитория и первого коммита**  

Зарегистрировал аккаунт.
Создал публичный репозиторий и сделал как написано в требовании ДЗ.
Так как пока учусь, то листая инет решил согласно рекомендациям установить клиент Sublime Merge -  который позволяет считывать репозиторий git для отображения списка отправлений (коммитов), ветвей и различий самых последних изменений. Пока конечно многое непонятно, но очень интересно.
Также установил Visual Studio Code для редактирования кода.

![image](https://github.com/Byzgaev-I/devops-netology/blob/main/1.png)

### Задание 2. Создание файлов .gitignore и второго коммита

![image](https://github.com/Byzgaev-I/devops-netology/blob/main/2.png) 

![image](https://github.com/Byzgaev-I/devops-netology/blob/main/3.png)

В файле README.md опишите своими словами, какие файлы будут проигнорированы в будущем благодаря добавленному .gitignore.  
Будут проигнорированы данные типы файлов:  
*.tfstate - будут проигнорированы все файлы с расширением tfstate  
звездочка.tfstate.звездочка - будут проигнорированы все файлы с расширением tfstate.* (вместо звездочки ещё любое расширение)  
crash.log - будут проигнорированы все файлы с именем crash и с расширением log  
crash.*.log - будут проигнорированы все файлы с именем crash и с расширением *.log (вместо звездочки еще любое расширение)  
*.tfvars - будут проигнорированы все файлы с расширением tfvars  
*.tfvars.json - будут проигнорированы все файлы с расширением tfvars.json  
override.tf - будут проигнорированы все файлы с именем override и с расширением tf  
override.tf.json - будут проигнорированы все файлы с именем override и с расширением tf.json  
*_override.tf - будут проигнорированы все файлы, в имени которых есть _override и с расширением tf  
*_override.tf.json - будут проигнорированы все файлы, в имени которых есть *_override и с расширением tf.json  
.terraformrc - будут проигнорированы все файлы, заканчивающиеся на .terraformrc  
terraform.rc - будут проигнорированы все файлы с именем terraform и с расширением rc  
Закоммитьте все новые и изменённые файлы. Комментарий к коммиту должен быть Added gitignore.  

### Задание 3. Эксперимент с удалением и перемещением файлов (третий и четвёртый коммит)    

![image](https://github.com/Byzgaev-I/devops-netology/blob/main/5.png)  

![image](https://github.com/Byzgaev-I/devops-netology/blob/main/6.png)  

![image](https://github.com/Byzgaev-I/devops-netology/blob/main/7.png)  

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
