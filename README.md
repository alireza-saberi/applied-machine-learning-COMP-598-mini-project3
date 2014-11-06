<h1>Machine Learning Digits Classification Project</h1>
<p style="text-align:justify">For mini-project #3, we are tasked with automatically classifying handwritten digits displayed in images.
To make things a little more challenging, the images are rotated and various background textures have been added in.
A set of labeled training data is privided(i.e. images and category) as well as a set of unlabeled test data (i.e. images).
Image	has	been	modified	using	the	 following	transformations:
<ul>
<li> Embossing	of	the	digit.
<li>Rotation (by	a	random	angle,	sampled	from	[0,	360deg].</li>
<li>Rescaling	(from	28x28	pixels	to	48x48	pixels).</li>
<li>Texture	pattern	(randomly	selected,	and	overlayed	on	background)</li>
</ul>
</p>

<p style="text-align:justify">This	dataset	was	constructed by	researchers	from the	LISA	lab	at	the	
University	of	Montreal	(Pierre	Luc	Carrier,	Aaron	Courville).	It	is	shared	
under	the	understanding	that	it	can	only	be	used	for	the	purposes	of	this	
project,	and	cannot	be	shared	outside	of	the	course.<p>

<p style="text-align:justify">In this report, authors have approached \hard digit classifcation" task using dierent classiers and preprocessing steps. The raw dataset is a modied version of the popular MNIST digit classication dataset. The performances of logistic regression, feed forward neural network, linear SVM and convolutional neural net have been compared. Convolutional neural network shows the best accuracy 93.69% (submitted on Kaggle), followed by SVM (38.1%), Feed forward neural network (35.37%) and logistic regression (25.58%), respectively.</p>

<p>We got 2nd place on class competition! among 21 teams</p>
