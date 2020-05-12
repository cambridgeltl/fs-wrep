# fs-wrep
Pretrained function-specific vectors (Gerz et al., ACL 2020)

Arxiv: [Multidirectional Associative Optimization of Function-Specific Word Representations](https://arxiv.org/abs/2005.05264).

The pretrained vectors used in the paper [can be downloaded here](https://drive.google.com/drive/folders/180TNdD-uRmFGCAhcRvjQlJvRdVnVMzfE?usp=sharing).

We share 3 vector spaces:

1. svo_d100: This is a 100-dimensional joint vector space consiting of subject, verb and object vectors.
2. sv_d25: This is a 25-dimensional joint vector space consisting of subject and verb vectors.
3. vo_d25: This is a 25-dimensional joint vector space consiting of verb and object vectors.

We share embedding as well as bias vectors for all spaces. Note that for the main results in the paper, we only used the embedding vectors: subj.emb.txt, verb.emb.txt, obj.emb.txt. Here we additionally share the bias vectors of the trained network, of all directions, in case it is of interest.
