Чтобы увидеть список всех веток в нашем репозитории, используем:
>git branch

Чтобы создать ветку, используем:
>git branch branch_name: создается ветка с именем **branch_name**

Чтобы перейти на другую ветку, используем:  
>git checkout branch_name: переход на ветку с именем **branch_name**

Чтобы создать новую ветку и сразу на нее перейти, используем:
>git checkout -b branch_name: создается ветка с именем **branch_name** и она сразу оказывается активной

Чтобы удалить ветку, используем:
>git branch -d branch_name: удаляет ветку с именем **branch_name** если был выполнен merge  

Чтобы принудительно удалить ветку, используем:
>git branch -D branch_name: удаляет ветку с именем **branch_name** даже если merge не был выполнен

Чтобы склонировать удаленный репозиторий на локальный компьютер, используем:
>git clone url-адрес репозитория

Чтобы получить изменения из удаленного репозитория и сделать merge с локальной версией, используем:
>git pull

Чтобы отправить локальную версию на удаленный репозиторий, используем:
>git push