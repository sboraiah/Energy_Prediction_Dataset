The	goal	of	this	homework is	to	develop	a	method	to	predict	the electricity load	demand	of	different	
individual	users.

You	are given	separate	datasets	for	10	users that	contain	the	load	demand	(in	kW)	for	each	15-minute	
interval	that	covers 1	year	(12/1/2014	– 11/30/2015).		Your	objective	is	to	utilize	existing	prediction	
methods	or	create	your	own	that	uses	the	past	load	demand	before a	particular	timeslot	as	the	input	to	
predict	the	next	96	15-minute	intervals	(one	full	day	ahead) from and	including	this	timeslot.
The	accuracy	of	the	predictions	will	be	measured	by	the	Mean	Absolute	Error	(MAE) individually	for	
each	step	ahead	into	the	future.		One	baseline	method	to	compare	the	accuracy	to	is	the	Naïve	method	
which	simply	uses	the	last	observed	value	as	the	prediction	for	all	steps	into	the	future.		The	Naïve	
method is	used	to	decide	whether	or	not	to	even	consider	using	a	proposed	method.		Your	method	
ought	to	be	more	accurate	than	the	Naïve	method.
