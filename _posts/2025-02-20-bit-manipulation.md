---
title: Bit Manipulation 
---
### XOR
I noticed that duplicate number can be detected 
by xor operations. like same numbers have
exact same bits in their positions so according 
to xor operations 1^1 = 0 also 0^0 =0. only
two different bits make 1 like 1^0 = 0 and
also 0^1 = 1

### And
I noticed that if number is 2based log and 
its previous number can make the results 0
because if you observe this 8 and 7 which
binaries are 1000 and 0111 and And operation does
the opposite the XOR operations like 1&0 = 0
also 0&1 = 0 besides 0 & 0 = 0  and only 1 & 1 = 1
so It can be proven 2^n & 2^n-1 = lowest value 0
and (2^n-1) & (2^(n+1) - 1) = 2^(n+2) -1 gives
you the highest value
