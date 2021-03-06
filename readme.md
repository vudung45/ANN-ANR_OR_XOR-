@Author : David Vu

Application: Artificial Neural Network for AND OR XOR logic problem

Implementation: ANN (Artificial Neural Network) algorithm, DEAP python.

To learn more about Aritificial Neural Network : <a href="https://en.wikipedia.org/wiki/Artificial_neural_network">Click here ( Wikipedia ) </a>

Sample result:
> AND logic weights:  [-0.18959636984322603, 7.897154478201223, 12.167765493884689,
> -14.751600422231201, -9.707496739356303, 14.421051249881726, -23.002494697989373,
> 41.782478940259494, -115.41612522095801]
> 
> OR logic weights:  [5.548746051403271, 15.69354299306821, 17.94538105505678,
> -12.409269144132383, -15.519391727454433, 22.594299287588065, 5.617215792993443,
> 104.8221094633886, -67.90548056830667]
> 
> XOR logic weights:  [-13.431153578440316, 14.683184218522543, 7.7130901754413745, 
> -3.8436072240865107, 2.7745265757906408, -20.391967987532986, 46.01746484217755, 
> -41.56858800548493, 79.49211277345418]

To test these weights:

	+ Use this function: 
		getNeuralOutput([sample weights], [inputs]), 
	whereas:
	[inputs] is the tuple [x1,x2] (x1,x2 ∈ [0,1]). 
	[sample weights] is one of the sample result up there.
		
	+ You can generate your own [sample weights] by running the solution file


Here are the tests for those sample weights listed up there:
		

	---Testing weights---

	AND logic weights: 

	Truth Values:

	[0, 1] : 7.56111153543e-51 ~ 0

	[1, 0] : 1.03801804673e-52 ~ 0

	[1, 1] : 1.0

	[0, 0] : 7.52556745288e-51 ~ 0


	OR logic weights: 

	Truth Values:

	[0, 1] : 1.0

	[1, 0] : 1.0

	[1, 1] : 1.0

	[0, 0] : 3.22881187481e-30 ~ 0


	(Prob 3)XOR logic weights: 

	Truth Values:

	[0, 1] : 1.0

	[1, 0] : 1.0

	[1, 1] : 8.85107398114e-19 ~ 0

	[0, 0] : 8.85098512361e-19 ~ 0
