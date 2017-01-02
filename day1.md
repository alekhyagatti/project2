# Day 1

+  Downloaded & extracted mobaxterm
+  Changed the password in https://common.hclets.com
+  Run mobaxterm --> start local session --> give command 
	ssh alekhya.gatti@10.137.251.91 -p 41019

## Have to Look at home
1. Know about ssh
2. Have to learn Linux
3. [CoreUtils](http://www.gnu.org/software/coreutils/manual/coreutils.html)
4. [Shell Scripting](http://www.tldp.org/LDP/Bash-Beginners-Guide/html/)
5. [ING Training](http://ing-training.kramarao.com/basic/machine-basics/)
6. [Mkdocs](http://www.mkdocs.org/user-guide/styling-your-docs/)
7. [Markdown](https://daringfireball.net/projects/markdown/syntax)
8. [Pandoc](http://pandoc.org/demos.html)


## Points to be Noted

1. [To get Machine Stats](http://www.tecmint.com/command-line-tools-to-monitor-linux-performance/)
2. To get ip number of some site in linux --> dig google.com
3. To get ip number of some site in cmd   --> ping google.com
4. Install pandoc and create word document --> sudo apt-get install pandoc
						vi a.md
						pandoc -s -S a.md -o example29.docx


## GIT
> To install git in linux
>	1. sudo apt update
>	2. sudo apt-get update
>	3. sudo apt-get install git

> Give global variables
>	1. git config --global user.name "alekhya.gatti"
>	2. git config --global user.email "alekhya.gatti@hcl.com"

> Create a repository in github (project1)
>	1. echo "# project1" >> README.md
>	2. git init
>	3. git add README.md
>	4. git commit -m "first commit"
>	5. git remote add origin git@github.com:alekhyagatti/project1.git
>	6. git push -u origin master 
>
> Create branch
>	
>	1. git checkout -b [name_of_your_new_branch]
>	2. git push origin [name_of_your_new_branch]

