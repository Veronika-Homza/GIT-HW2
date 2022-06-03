# GIT-HW2

1. На локальном репозитории сделать ветки для:  
                 
- Postman 
- Jmeter
- Checklists
- Bug-Reports
- SQL
- Charles
- Mobile-Testing

   **```Repositories -> New -> Repository name (GIT-HW2) -> Create repository```**
   
   **```git clone git@github.com:Veronika-Homza/GIT-HW2.git```<br>** 
   **```cd GIT-HW2```** 

   **```git branch Postman```<br>**
   **```git branch Jmeter```<br>**  
   **```git branch Checklists```<br>**
   **```git branch Bug-Reports```<br>**
   **```git branch SQL```<br>**
   **```git branch Charles```<br>**
   **```git branch Mobile-Testing```<br>**
 
2. Запушить все ветки на внешний репозиторий.

   **```git push --all```** 

3. В ветке Bug-Reports сделать текстовый документ со структурой баг репорта.

   **```git checkout Bug-Reports```<br>**
   **```touch bug_report.txt```** 

4. Запушить структуру баг репорта на внешний репозиторий.

   **```git add .```<br>**
   **```git commit -m "add bug_report.txt"```<br>** 
   **```git push --set-upstream origin Bug-Reports```**

5. Вмержить ветку Bug-Reports в main

   **```git checkout main```**
   **```git merge Bug-Reports```** 

6. Запушить main на внешний репозиторий.

   **```git push```**

7. В ветке Checklists набросать структуру чек листа.

   **```git checkout Checklists```<br>**
   **```touch checklist.xlsx```**

8. Запушить структуру на внешний репозиторий.

   **```git add .```<br>**
   **```git commit -m "add checklist.xlsx"```<br>** 
   **```git push --set-upstream origin Checklists```**

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main.

   **```Pull request -> Merge pull request -> Confirm merge```**

10. Синхронизировать Внешнюю и Локальную ветки Main

    **```git fetch```<br>**
    **```git pull```*

#
