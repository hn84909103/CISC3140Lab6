## CISC3140Lab6


#Lab 6-1

create a directory named Repo_1   	 $ mkdir Repo_1
go into the directory Repo_1      	 $ cd Repo_1
intitialize git repository        	 $ git init
create a file in the directory    	 $ vi file.java

after edited and saved the change in the file

add the file	                	 $ git add --all
add the commits to the changes     	 $ git commit

add the file to github		       	 $ git remote add origin git@github.com:hn84909103/CISC3140Lab6.git
create the main branch			 $ git branch -M main
connect with github			 $ git remote -v
	                          	( origin	git@github.com:hn84909103/CISC3140Lab6.git (fetch) )
                          		( origin	git@github.com:hn84909103/CISC3140Lab6.git (push) )

switch the SSH TO HTTPS			         $ git remote set-url origin https://github.com/hn84909103/CISC3140Lab6.git		
connect with github	            		 $ git remote -v
	                          				( origin  https://github.com/hn84909103/CISC3140Lab6.git (fetch) )
                           					( origin  https://github.com/hn84909103/CISC3140Lab6.git (push)	 )

add the file                  	   	 $ git add --all
push to github	              			 $ git push -u origin main

login github with the username and password
done


--------------------------------------------------------------------------------------------------------------


#Lab 6-2

create a directory named Repo_2   	 $ mkdir Repo_2
go into the directory Repo_2      	 $ cd Repo_2
intitialize svn repository	      	 $ svn co --depth https://github.com/hn84909103/CISC3140Lab6.git
go to CISC3140Lab6.git	        		 $ cd CISC3140Lab6.git
update trunk		                		 $ svn up trunk
update branches		              		 $ svn up --depth empty branches
copy a branch		                		 $ svn copy trunk branches/repo_2
add a commit	                			 $ svn commit - "messages"

login github with the username and password
done
