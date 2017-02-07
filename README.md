# sfblog

# aby sprawdzic powiazanie wpisz  git remote -v

# powinno zapodac

#origin  https://github.com/erdiart/sfblog.git (fetch)
#origin  https://github.com/erdiart/sfblog.git (push)

#ale to nie znaczy ze dziala ????

git add .  // z kropka na koncu dodaje wszystkie pliki do commitowania ale jeszcze tego nie robi
git status  // pokazuje status aktualnych plikow

git commit -m 'poczatkowy files commit' // to dopiero powoduje ze pliki sa  commitowane ale nie sa widocze w gitHubie !!!

erdiart:~/workspace (master) $ git push  // to dopiero wysyla na GitHuba
Username for 'https://github.com': erdiart // pyta sie o uz i pass
Password for 'https://erdiart@github.com': 
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 657 bytes | 0 bytes/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/erdiart/sfblog.git
   babcc55..6837a18  master -> master
   
   