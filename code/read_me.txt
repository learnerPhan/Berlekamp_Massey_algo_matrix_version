Si algo_naif renvoie "failed,1", c-a-d algo_naif ne trouve pas le résultat.
Si algo_naif renvoie un vecteur colonne x = (x_1, x_2, .., x_n), la relation de récurrence est u_(n+1) = x_1*u_1 + x_2*u_2 + ... + x_n*u_n.

Si algo_BM renvoie un vecteur ligne x = (x_n, x_(n-1), .., x_1), la relation de récurrence est x_n*u_n + ... + x_2*u_2 + x_1*u_1 = 0

algo_BM propose des différentes testes, pour effectuer un teste, il suffit d'enlever #. 
