# All4s5mCRNs
#### Here, we provide the code and data associated with the preprint, *Hopf Bifurcations of Reaction Networks with Zero-One Stoichiometric Coefficients* (https://arxiv.org/abs/2208.04196), written by Dr. Xiaoxian Tang and Kaizhang Wang.<br>
#### To get all chemical reaction networks with four species and five reactions that admit a Hopf bifurcation, the interested readers can run CalculateAll_4s5m_withHB.nb in Mathematica. It takes a bit long time to have the result. For those who have limited time, the result is directly demonstrated in all4s5mReactionswithHB.txt. <br>
#### We illustrate how to convert the provided data to reactions. For example, the first row in all4s5mReactionswithHB.txt is given by 

<p align="center">
{{1, 1, 1, 1}, {0, 0, 0, 0}}{{0, 0, 1, 0}, {0, 0, 1, 1}}{{0, 0, 0, 0}, {0, 0, 1, 1}}{{1, 0, 0, 0}, {0, 1, 0, 1}}{{0, 0, 0, 1}, {1, 0, 0, 0}}.
</p>

#### Denote the species by X1,X2,X3,X4. The first element {{1, 1, 1, 1}, {0, 0, 0, 0}} represents the first reaction, which is 

<p align="center">
$X_1+X_2+X_3+X_4 \rightarrow 0$.
</p>

#### Then, the rest reactions are given by

<div align="center">
$X_3 \rightarrow X_3+X_4, \;\;0 \rightarrow X_3+X_4,\;\; X_1 \rightarrow X_2+X_4,\;\; X_4 \rightarrow X_1.$ 
</div> 
