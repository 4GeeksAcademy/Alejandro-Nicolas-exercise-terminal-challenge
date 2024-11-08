# COMMAND LINE
---

Lista de arhivos

```ls```
---
---
Meterse en el archivo thecmdchallenge

```cd thecmdchallenge/```
---
---
Print current directory path

```pwd```
---
---
List all the files from the current directory including the hidden ones

```ls -la```
---
---
Now list all the files inside the project, recursively (all files in the hierarchy)

```tree -a    /   ls -R```
---
---
Clear all the clutter from the command line

```Clear```
---
---
Go to the last level below the small-name folder and show on the console the content of the trophy.txt file

```cd small-name /    cd bigger-name-than-before/    /      cd omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type/this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious/   /   cat trophy.txt```
---
---
Move one level up and get to the funcode directory and list all files with the JavaScript typical extension

``` cd .. /  cd .. / cd .. /  cd funcode/   /    find . -type f -name "*.js"```
---
---
Create a new directory inside funcode/the-most-funny/ called “not-that-funny“

```cd the-most-funny/   /    mkdir not-that-funny```
---
---
Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt

```cd ..    /    cd .. / cd boringfolder/    /  $ cd even-more-boring/    /     $ cd $(find . -type d -print | sort | tail -n 1)    /     mv the-mostboring-text.txt lol.txt```  
---
---
Move funcode/kids.jpg inside funcode/images/hello/

```cd ..   /     cd ..    /   cd ..    /    cd ..    /    cd funcode/     /    mv kid.jpg images    /      cd images     /      mv kids.jpg hello```
---
---
Remove the “small-name“ directory

```cd ..   /     rm -r small-name```
---
---
Print in the command line the content of the-ultimate-joke.txt

```cd funcode/the-most-funny/lol/     /     cat the-ultimate-joke.txt```
---
---
Remove all the contents from the boringfolder, they are extremely boring…

``` cd ..    /    cd ..      /     rm -r boringfolder/ ```ç
---
---
Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor

```cd kamehameha     /vi dragon-ball-jokes.md.swp```
---
---
Update the file kamehameha/dragon-ball-jokes.md by removing the first joke you read on the file, finally save and close the text editor

```nano dragon-ball-jokes.md```