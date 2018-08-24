Welcome to Etherpad!

This pad text is synchronized as you type, so that everyone viewing this page sees the same text. This allows you to collaborate seamlessly on documents!

Get involved with Etherpad at \url{http://etherpad.org}

#**Attendance(Friday):** \url{https://goo.gl/forms/xTw08gsfuJ2fOoqB2}


post workshop survey: \url{https://www.surveymonkey.com/r/swc\_post\_workshop\_v1?workshop\_id=2018-08-16-okstate}


#Day 1

ls -F /
pwd
ls
ls -F
ls --help
ls -l
ls -h
ls -l -h
ls -lh
ls -lhF

Download file: \url{http://swcarpentry.github.io/shell-novice/data/data-shell.zip}
Save to your desktop and extract

ls -F Desktop/data-shell
cd Desktop
cd data-shell
cd data
cd data-shell         (this command won't work, gives an error: "No such file or directory")
cd ..
cd ..
ls -a
cd
pwd
cd Desktop/data-shell/data


cd
cd Desktop/data-shell
ls
ls north-pacific-gyre
mkdir thesis
ls
cd thesis
ls
nano draft.txt

   * Type in some textcd
touch my\_file.txt
cd Desktop/data-shell/thesis
ls
rm draft.txt
ls
touch draft.txt
ls
cd ..
rm thesis       (this will produce an error)
rm -i -r thesis
mkdir thesis
touch thesis/draft.txt
mv thesis/draft.txt thesis/quotes.txt
ls thesis/
mv thesis/quotes.txt .
cp quotes.txt thesis/quotations.txt
rm quotes.txt
ls quotes.txt thesis/quotations.txt
cd data
mkdir backup
cp amino-acids.txt animals.txt backup/
ls backup/
cp amino-acids.txt animals.txt morse.txt       (this will produce an error)
cp amino-acids.txt animals.txt morse.txt backup/ls
ls a*
ls a*.txtih
ls animal?.txt
la anima??.txt

cd ..
(Should be in the data-shell folder)
cd molecules
ls
wc *.pdb
wc -l *.pdb
wc -l *.pdb > lengths.txtcat lengths.txtless lengths.txt

   * hit the q key to exit lesssort -n lengths.txt
sort -n lengths.txt > sorted-lengths.txt
head -n 1 sorted-lengths.txt
wc -l *.pdb | sort -n | head -n 1
cd ..
cd data
cat animals.txt
cat animals.txt | head -n 5
cat animals.txt | head -n 5 | tail -n 3
cat animals.txt | head -n 5 | tail -n 3 | sort -r
cat animals.txt | head -n 5 | tail -n 3 | sort -r > final.txt
cd ../creatures
ls
cp *.dat original-*.dat        (doesn't work)
for filename in basilisk.dat unicorn.dat; do head -n 3 $filename; done
cd ../molecules
for datafile in *.pdb; do ls *.pdb; done
for datafile in *.pdb; do ls $datafile; done
cd ..
cd creatures
for filename in *.dat; do echo $filename; head -n 100 $filename | tail -n 20; done
for filename in *.dat; do cp $filename original-$filename; done


#AFTERNOON - Python day 1

Agenda:
1. Variables \& Data Types
2. Storing multiple values - lists
3. For loops and conditionals
4. Errors and help


Markdown: \url{https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet}

**INDEX**  

|  N  |  A |   T |   H |   A |   L |   I |   A |
|------|------|------|------|------|------|------|------|------|
|  0  |   1  |    2 |   3  |    4 |   5 | 6 |  7|


**SLICING**

| |  N  |  | A |  | T |  | H |  | A |  | L |  | I |  | A |
|------|------|------|------|------|------|------|------|------|
|    0  |   | 1  |   |  2 |   | 3  |   |  4 |   | 5 | | 6 | | 7| | 8|


#
#Day 2


Download file: \url{http://swcarpentry.github.io/python-novice-gapminder/files/python-novice-gapminder-data.zip}
Save to desktop and extract







#underlineFurther Resourcesunderline

Phillip Doehle—OSU High Performance Computing Center: doehle@okstate.edu
Gautham Ponnaganti - OSU Library  Git and GitHub: gautham.ponnaganti@okstate.edu
    
    Carpentries: \url{https://carpentries.org/}
    Software Carpentry Lessons: \url{https://software-carpentry.org/lessons/}
    Data Carpentry Lessons: \url{https://datacarpentry.org/lessons/}
    Github Desktop: \url{https://desktop.github.com/}
    Source tree: \url{https://www.sourcetreeapp.com/}















