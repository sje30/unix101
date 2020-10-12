# unix101
Unix introduction


# starting off

     getting help
	 man ls
	 ls --help

    echo $PATH

    which R

## repl

history, tab completion, arrow keys

# making files

nano, 

    date > now.txt


# making folders

    pwd, cd, rmdir "tilde"
	
	/tmp
	
# wildcards

   touch several files.
   
# little case study

    Rscript -e "write.table(iris, file='iris.txt', row.name=FALSE)"

head, tail, cat, grep, wc

## part 1 - a shell script

    grep 'setosa' iris.txt > setosa.txt
	cut -d' ' -f1 setosa.txt > setosa_sepal_length.txt
	sort setosa_sepal_length.txt | tail -10
	
## part 2 - pipes


# accessing a remote machine


ssh

sftp

filezilla client https://filezilla-project.org/

top
uptime
nice

# next steps


