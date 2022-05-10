#Hello
…or create a new repository on the command line
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ForNettiii/test.git
git push -u origin main #origin main lehivasa
…or push an existing repository from the command line
git remote add origin https://github.com/ForNettiii/test.git
git branch -M main
git push -u origin main
További terminál parancsok
git pull origin main
git remote -v #távoli repo lekérdezése
git status #change, stage, commit állapotának lekérdezése
git config --global --list #globális beállitasok listazasa
cd #changedirectory
cd .. #egy mappaval feljebb lep
mkdir #make directory
rmdir #remove directory
ls #list directory
git commit -am "messeage" #elmenti az osszes valtoztatast es acommitot is