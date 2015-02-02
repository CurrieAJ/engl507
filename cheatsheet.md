# Getting Started with Git + GitHub

1. Enter: cd ~/desktop (move to desktop)
2. Enter: git init engl507test
3. Enter: cd engl507test (move to directory)
4. Enter: touch index.md (create file)
5. Enter: open index.md (open file)
6. Enter: git remote -v (verify)
7. Enter: git add --all (add changes)
8. Enter: git commit -m "message" (record and describe changes)
9. Enter: git push origin master (push changes to your repo)
10. Repeat

# WGet

* Like using a browser without the browser

Pulling stuff from Walt Whitman Archive
1. Enter: cd ~/desktop (move to desktop)
2. Enter: mkdir walt (create directory)
3. Enter: cd walt (change directory)
4. Enter: wget http://www.whitmanarchive.org/published/LG/index.html
5. In 'walt' file, it should have a file

Pulling stuff from Gutenberg
1. Wget makes an exception with Gutenberg
2. Enter: cd ~/desktop (move to desktop)
3. Enter: mkdir allthebooks (create directory)
4. Enter: cd allthebooks (change directory)
5. Enter: wget -w 2 -m -H "http://www.gutenberg.org/robot/harvest?filetypes[]=text" (wait two seconds; mirrors the entire website; span hosts)
6. To stop: ctrl C

Internet Archive
1. Go to archive.org/advancedsearch.php
2. Query: creator: Jane Austen
3. Fields to return: identifier
4. Sort results by: identifier asc
5. Enter: CSV format
6. Search
7. Highlight all links from downloaded spreadsheet
8. Copy to sublime
9. Move to the command line
10. Enter: cd ~/desktop (move to desktop)
11. Enter: mkdir austen (create directory)
12. Enter: cd austen (change directory)
13. Enter: wget –r –H –nc –nH –np --cut-dirs=3 –e robots=off –A .pdf –A .txt –l1 –i austen.txt –B 'http://archive.org/download/' (recursive retrieval; span hosts; no clobber; skip directory; no parent; cut three directories; execute; robots off; accept only pdf; accept only txt; level one text; input; begin with)