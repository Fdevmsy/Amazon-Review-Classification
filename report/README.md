- **Descriptive methods**:

	 Clustering, Pattern Mining
	 
-  Nominal
- Ordinal


- **Binary attributes** are a special case of **discrete attributes**

- Asymmetric attributes 
 • Only presence (a non-zero attribute value) is regarded as important – Wordspresentindocuments

- Distances,such as the Euclidean distance, have some well known properties.
	 1. d(p, q)   0 for all p and q and d(p, q) = 0 only if p = q. (Positive definiteness)
- A distance that satisfies these properties is a metric
- For **binary vectors** :
	• Compute similarities using the following quantities
	F10 = the number of attributes where p was 1 and q was 0 
	F00 = the number of attributes where p was 0 and q was 0 
	F11 = the number of attributes where p was 1 and q was 1

	
	
- Mutual Information: 𝐼 (𝑋,𝑌) =𝐻 (𝑋) +𝐻 (𝑌) −𝐻(𝑋,𝑌)


Cosine: Y.dot(X.T)

- Locality sensitive hashing
		
	• A set of functions is locality-sensitive, if, for a random hash function h in the set, for any pair of points p, q:
	
	
	– Pr[h(p) = h(q)] is “low” if p is “far” from q


- IdxJoin 
	- Accumulator (): data structure tracking similarities while being computed
	
- L2AP 
	- Main idea: leverage similarity estimates
	- Filter/prune object pairs not in final graph based


![](/Users/ShiyuMu/Desktop/Screen Shot 2017-03-20 at 20.50.00.png)






![](/Users/ShiyuMu/Desktop/Screen Shot 2017-03-20 at 20.37.45.png)

	   A = [ 10 20 30 40 50 60 70 80 ]
	   IA = [  0  2  4  7  8 ]
	   JA = [  0  1  1  3  2  3  4  5 ]   


- Given high enough # tables and # hashes (hash functions), we can achieve high recall and precision, sometimes at the expense of efficiency.


Sd = （平方和的平均 减去 平均的平方） 开方


Linear: SVD(min reconstruction error) PCA(matain varience)

Non-Linear: LLE(matain local geomatry) Random projection(preserve pairwise distances)

Supervised: LDA (preserve class discriminatory information)

Determine K: cross- validationm