# This is a part of GIT homework - JSON
## 1. Create an external repository called "json": 
```
GitHub > New repository > Create repository 
```
***
## 2. Clone the JSON repository to a local machine: 
```
$ git clone HTTPS
```
***
## 3. Inside the local JSON create a “new.json” file": 
```
$ cd JSOM
$ touch new.json
```
***
## 4. Add changes to indexed files section: 
```
$ git add touch new.json
```
***
## 5. Commit the file: 
```
$ git commit -m "First commit"
```
***
## 6. Push the file to the external GitHub repository: 
```
$ git push
```
***
## 7. Edit the content of the file “new.json” - write information about yourself. Everything is written in json format:
```
$ vim new.json
press i
{
	"Person" :
	{
	"name" : "Olga",
	"surname" : "Rozina",
	"age" : 24,
	"hobby" : "hiking",
	"country" : "Lithuania",
	"city" : "Vilnus"
	}
}

press Esc > :wq
```
***
## 8. Push changes the an external repository:
```
$ git add new.json
$ git commit -m "JSON"
$ git push
```
***
## 9. Create a file "preferences.json":
## 10. In the file "preferences.json", add information about your preferences in json format:
```
$ cat > preferences.json
{
"Prefences":
    {
     "eat":"pizza",
     "film": "Interstellar",
     "series": "Force_majeure",
     "time of year": "summer"
     }
}
```
***
## 11. Create a file "skills.json" and add information about the skills that will be studied in the course in json format:
```
$ cat > skills.json
{
"skill_1": "GIT",
"skill_2": "SQL",
"skill_3": "Postman",
"skill_4": "Fiddler", 
"skill_5": "Android_Studio",
"skill_6": "Charles",
"skill_7": "HTTP",
"skill_8": "JSON", 
"skill_9": "XML"
{
```
***
## 12. Send two files at once to the external repository:
```
$ git add .
$ git commit preferences.json skills.json -m "First commit"
$ git push
```
***
## 13.On the web interface, create a file "bug_report.txt":
```
Add file > Create new file
```
***
## 14. Press "Commit changes", save changes on the web interface:
```
> Commit new file
```
***
## 15. On the web interface, modify the file "bug_report.json" and add a bug report in json format:
```
{
"ID": 1,
"Enviroment": {
               "OS": "Win_10",
               "Browser": "Chrome_112"
               },
"Summary": "404 error when user is accessined the purchase order report page as a sales manager",
"Actual result" : "The report isn't showed as per the criteria selected",
"Expected result": "The report should show as per the criteria selected",
"Step to reproduce": {
                      "1) Login as Sales Manager",
                      "2) Go to the Reports page and choose \"Purchase Order Report\"",
                      "3) Select any filter criteria",
                      "4) Click the \"Show Report\" button"
                      },
"Severity": "Medium",
"Priirity": "Normal",
"Repruducibility": "Always",
"Symptom": "Missing_feature",
"Workaround": "No",
"Attachment": "Link",
"Status": "Open",
"Author": "Olga Rozina",
"Sign to": "Olga Fefilova",
}
```
***
## 16. Press "Commit changes" and save changes on the web interface:
```
> Commit changes
```
***
## 17. Synchronize the external and the local JSON repository:
```
$ git pull
```
***
