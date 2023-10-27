# 2D-PCEDE

Each of the 12 classes is as a data set of 10 instances for the 2D-PCEDE. Each instance is composed of the number of available object types, number of item types, number of production periods, lengths and widths of object types and item types, demand for each item type in each period, production capacity of each period and availability of each type of object in each period. Thus, each instance is given by:

K

M

T

L_1 L_2 ... L_K

W_1 W_2 ... W_K

l_1 l_2 ... l_M

w_1 w_2 ... w_M

d_11 d_12 ... d_1T
 .     .  ...   .
 .     .  ...   .
 .     .  ...   .
d_M1 d_M2 ... d_MT

C_1 C_2 ... C_T

e_11 e_12 ... d_1T
 .     .  ...   .
 .     .  ...   .
 .     .  ...   .
e_K1 e_K2 ... d_KT

Where:

K: number of available object types;

M: number of item types;

T: number of production periods;

L_k: length of object type k, k=1,...,K;

W_k: width of object type k, k=1,...,K;

l_i: length of item type i, i=1,...,M;

w_i: width of item type i, i=1,...,M;

d_it: demand of item type i in period t, i=1,...,M, t=1,...,T;

C_t: production capacity of period t, t=1,...,T;

e_kt: availability of object type k in period t, k=1,...,K, t=1,...,T.
