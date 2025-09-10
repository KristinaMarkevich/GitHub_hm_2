# GitHub_hm_2


**1. На локальном репозитории сделать ветки для:**
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git branch postman

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git branch jmeter

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git branch checklists

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git branch bug_reports

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git branch mobile_testing; git branch sql; git branch jmeter

```
**2. Запушить все ветки на внешний репозиторий**

```

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git push -u origin bug_reports charles checklists jmeter postman mobile_testing sql

```
**3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта**

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git checkout bug_reports
Switched to branch 'bug_reports'
Your branch is up to date with 'origin/bug_reports'.

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (bug_reports)
$ cat > file_1.txt
  id-
  title-
  Severity-
  Priority-
  Steps to Reproduce-
  Expected Result-
  Actual Result-
  Environment-
  Attachment-
```

**4. Запушить структуру багрепорта на внешний репозиторий**

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (bug_reports)
$ git add .

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (bug_reports)
$ git commit -m "add file_1"
[bug_reports a907efc] add file_1
 1 file changed, 9 insertions(+)
 create mode 100644 file_1.txt

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (bug_reports)
$ git push
```

**5. Вмержить ветку Bag Reports в Main**

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (bug_reports)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git merge bug_reports

```

**6. Запушить main на внешний репозиторий.**

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git push

```

**7. В ветке CheckLists набросать структуру чек листа.**

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (checklists)
$ cat > file_2.txt
id
test case
result

```

**8. Запушить структуру на внешний репозиторий**

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (checklists)
$ git add .


Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (checklists)
$ git commit -m "add file_2"
[checklists 5c7c5d8] add file_2
 1 file changed, 3 insertions(+)
 create mode 100644 file_2.txt

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (checklists)
$ git push

```
**9. На внешнем репозитории сделать Pull Request ветки CheckLists в main**


**10. Синхронизировать Внешнюю и Локальную ветки Main**

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (checklists)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/GitHub_hm_2 (main)
$ git pull

```
