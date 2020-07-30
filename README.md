# DM-Kmeans
we	will implement	and	use	the	K-means	clustering	algorithm.	First	we	will	learn	to	
cluster	a	simple	2D	dataset,	next	you	will	learn	a	method	to	evaluate	the	performance	of	
clustering	and	finally	we	will	learn	about	the	restrictions	of	KMeans	by	running	it	on	a	complex	
dataset.	
	
As	discussed	in	the	class,	the	main	idea	behind	KMeans	is	an	iterative	process	that	starts	by	
guessing	the	initial	cluster	centers,	and	then	improves	this	guess	by	repeatedly	assigning	data	
points	to	their	closest	cluster	center	and	then	recalculating	the	centers	based	on	the	
assignment.	The	pseudo-code	of	K-means	is	as	follows:	
1. Choose the number of clusters(K) and obtain the data points 
2. Place the centroids c_1, c_2, ..... c_k randomly 
3. Repeat steps 4 and 5 until convergence or until the end of a fixed number of iterations
4. for each data point x_i:
       - find the nearest centroid(c_1, c_2 .. c_k) 
       - assign the point to that cluster 
5. for each cluster j = 1..k
       - new centroid = mean of all points assigned to that cluster
6. End 

A) After	completing	the	algorithm,	run	it	on	Dataset1.	Set	number	of	iteration	to	at	least	15	
and	run	K-means	with	k=2,	3,	4.	After	each	run	plot	the	clustered	data	points	with	each	
cluster	having	a	different	color.

B) After	the	clustering	is	done,	compute	for	each	cluster,	the	average	distance	between	the	
cluster	center	and	the	data	points	in	that	cluster	(this	average	distance	is	called	cluster	
error).	

C) compute	the	average	cluster	error	and	report	it	as	the	clustering	error.		
	
D) run	the	k-means	with	0<k<15	on	Dataset1	and	compute	the	clustering	error	and	plot	
these	errors.	

E) Use	the	“elbow”	algorithm	to	find	the	optimum	K.	
	
F) Run	the	clustering	once	again	on	Dataset2,	explain	why	KMeans	fails	on	this	dataset.



# Extra report in pdf file , kmeans section


