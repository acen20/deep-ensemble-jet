## Deep Ensemble Learning with Jet-Like architecture
1. <b>Tail</b>  > Sparse Autoencoder
2. <b>Wings</b> > Two CNNs
3. <b>Body</b> > Non-Linear PCA
4. <b>Nose</b> > MLP
<img src="https://www.researchgate.net/profile/Muhammad-Khan-608/publication/343318895/figure/fig1/AS:919016663171073@1596122055592/Proposed-DEL-Jet-technique_W640.jpg"/>

## Architectural details
**CNN1 (Left Wing)**
	conv layers = 3
	fc layers = 1
	filter size = (1,4)
	input channels = 1
	output channels = 3
	stride = 1
	padding = none
	output features = 15

**CNN2 (Right Wing)**
	conv layers = 4
	fc layers = 1
	filter size = (1,3)
	input channels = 1
	output channels = 3
	stride = 1
	padding = none
	output features = 15
