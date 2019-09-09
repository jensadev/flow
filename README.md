# flow

## Arbetsgång

Skapa git repo
copy paste på start koden, dvs.

Se till att du är i rätt mapp
c:\code\PROJEKT
eller
/mnt/c/code

    FIL
    git init
    
    git add FIL
    git commit -m "First commit"
    git remote add URL TILL REPO
    git push -u origin master

Skapa filer lokalt.

    git add .
    git commit -m "meddelande"
    git push

### arbeta sedan utifrån följande ordning

Skapa en gren, kolla vilka du har / aktiva och byt sedan med checkout

    git branch NYGREN
    git branch
    git checkout NYGREN

Arbeta och gör dina saker

    git add .
    git commmit -m "beskriv dina ändringar"

Du kan här pusha din branch, eller jobba vidare och göra fler commits.
Testa sedan så allt är synkat och klart.

För att merga tillbaka till master.

    git checkout master
    git merge NYGREN
    git branch -d NYGREN
    git push

Du mergar alltid till den branch som är aktiv.