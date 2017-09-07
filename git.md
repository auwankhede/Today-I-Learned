mkdir GIT
    2  cd GIT/
    3  mkdir Demos
    4  cd Demos/
    5  mkdir GitTest
    6  cd GitTest/
    7  ll
    8  git config --global user.name "Amol Wankhede"
    9  git config --global user.email "amol_wankhede@persistent.co.in"
   10  git config user.name
   11  git config user.email
   12  git config --list
   13  git init
   14  git status
   15  git add File.txt
   16  git status
   17  git commit -m "File is created and 1 statement is added - first commit"
   18  git status
   19  git status
   20  git add .
   21  git status
   22  git commit -m "Change1 text is added into file "
   23  git status
   24  git status
   25  git commit -am "change2 is added"
   26  git log
   27  git show c830708
   28  git diff
   29  git log
   30  git log --oneline
   31  git log --oneline -1
   32  git log --oneline -2
   33  git log --oneline
   34  git log --since="8-6-2017"
   35  git log --since="8-6-2017" --oneline
   36  git log --unline="8-6-2017" --oneline
   37  git log --unline="8-6-2017"
   38  git log --until="8-6-2017"
   39  git log --help
   40  git log --author"amo"
   41  git log --author="amo"
   42  git log --author="amo" --oneline
   43  git log --grep change
   44  git log --grep="change1"
   45  git log --grep="change1"
   46  git log --grep="This"
   47  git log --grep "This"
   48  git log --since="8-7-2017 15:40"
   49  git log File.txt
   50  git log File.txt --online
   51  git log File.txt --online -2
   52  git status
   53  git status
   54  git status
   55  git status
   56  git commit -am "Added .gitignore and added .java file added not to track"
   57  git statsu
   58  git status
   59  git status
   60  git add .gitignore
   61  git commit -m "Adding .gitignore"
   62  git status
   63  history

