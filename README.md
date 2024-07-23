# «БАЗОВЫЕ ОБЪЕКТЫ K8S»

### Задание 1. 
*Создать Pod с именем hello-world*

*Создать манифест (yaml-конфигурацию) Pod.*

*Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.*

*Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).*

Нарисан манифест:

![](img/1.png)

Создан и запущен pod.

С помощью port-forward пробрасываю порт пода.

![](img/2024-07-21_19-51.png)

GET запрос:

![](img/2024-07-21_19-51_1.png)

-



### Задание 2. Создать Service и подключить его к Pod

*1. Создать Pod с именем netology-web.*

*2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.*

*3. Создать Service с именем netology-svc и подключить к netology-web.*

*4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).*



Манифест для создания пода и сервиса:

![](img/5.png)

Запускаю под и сервис:

![](img/2024-07-21_19-58.png)

Подключаюсь локально к Service с помощью kubectl port-forward:

![](img/2024-07-21_20-06.png)

 GET запрос:
 
 ![](img/2024-07-21_20-08.png)
 
 Ссылки на манифест:
 
 https://github.com/dmistus/Kubernetes_02/tree/main/src

