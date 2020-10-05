# CISC3140Lab6


Lab 6-1

1. create a directory named Repo_1   	 $ mkdir Repo_1
2. go into the directory Repo_1      	 $ cd Repo_1
3. intitialize git repository        	 $ git init
4. create a file in the directory    	 $ vi file.java

5. after edited and saved the change in the file

6. add the file	                	 $ git add --all
7. add the commits to the changes     	 $ git commit

8. add the file to github		       	 $ git remote add origin git@github.com:hn84909103/CISC3140Lab6.git
9. create the main branch			 $ git branch -M main
10. connect with github			 $ git remote -v
	                          	( origin	git@github.com:hn84909103/CISC3140Lab6.git (fetch) )
                          		( origin	git@github.com:hn84909103/CISC3140Lab6.git (push) )

11. switch the SSH TO HTTPS			         $ git remote set-url origin https://github.com/hn84909103/CISC3140Lab6.git		
12. connect with github	            		 $ git remote -v
	                          				( origin  https://github.com/hn84909103/CISC3140Lab6.git (fetch) )
                           					( origin  https://github.com/hn84909103/CISC3140Lab6.git (push)	 )

13. add the file                  	   	 $ git add --all
14. push to github	              			 $ git push -u origin main

15. login github with the username and password
16. done


--------------------------------------------------------------------------------------------------------------


Lab 6-2

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
