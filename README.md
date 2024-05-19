# git-config

[user]
	email = email@email
	name = name
[alias]

	b = branch 

	bc = rev-parse --abbrev-ref HEAD 


	c = checkout

	cd = checkout develop

	cs = checkout staging

	cm = checkout master
	
	cb = checkout -b 


  po = pull origin 

  pom = pull origin master 

	poc = !git pull origin $(git bc) 


	m = merge 

	ma = merge --abort 

	mc = merge --continue 

	ms = merge --skip 


	bdd = branch -D 


	a = add 


	cm = commit -m 


  pso = push origin 
  psoc = !git push origin $(git bc) 
 
 
	rs = reset --soft 


	l = log 
