_Each individual code looked great. However, two types of problems emerged when merging._

### **Type 1 problem:**
The actual merging can be tricky/desastrous to perform.
* For example, not everyone had the right folder and subfolder structure; not all .html and .css had the same location. That created a cascade of problems that took ages to solve.
* The git conflicts were surprisingly easy to manage, probably because we anticipated them to some extent. Carefull html comments to divide up the code into the different sections were very useful to the team member that managed the conflicts.  
#### **Solutions:**
* Each team member must make sure that their branch has everything up-to-date in terms of file names, folders, paths, etc.
* Each team member has to make sure their chunks of code are easy to understand/identify for the conflict handler.


### **Type 2 problem:**
After merging into dev, the different sections of the dev were not exactly rendered as they were when they were developed within their respective branches.
* Some rendered text color was different
* Some headings were not rendered right (size, font,..)
* Whole sections were shifted to the left
#### **Solution:**
* Class names, hierarchy, inheritance,...: a detailed skeleton has to be decided before the team begins branching out. If some of it has to change, then every team member has to be notified and they will have to make sure their code is respectful of that change.


### *Other problem(s):**
* Html identation is **very important**, fixing the dev's .html becomes a nightmare if everyone uses different conventions/habits in identation. Making an effort to ident everything correctly is showing basic respect for fellow team members.
