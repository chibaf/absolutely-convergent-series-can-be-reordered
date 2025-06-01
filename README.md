# absolutely-convergent-series-can-be-reordered

## 主結果
$\sum a_n,  a_n \in \mathbb{C}$ が絶対収束するなら

任意の置換 $\sigma: \mathbb{N} \rightarrow \mathbb{N}$ について

$\sum a_{\sigma(n)}$ は絶対収束し、 $\sum a_n=\sum a_{\sigma(n)}$ となる

## 補助定理 1
$\sum a_{\sigma(n)}$ は絶対収束する。

 $S$ を $|a_1|,|a_2|,\dots$ の任意の有限和の全体。 $T$ を $|a_{\sigma(1)}|,|a_{\sigma(2)}|,\dots$ の有限和の全体。

とするとき、 $S=T$ である。

故に $\sum a_n$ が絶対収束する時、 $S$ は上に有界で、 $\sup T=\sup S<\infty$

## 主結果の証明
以下で $\sum a_n=\sum a_{\sigma(n)}$ を示す。

$\epsilon>0$ を任意にとる。 $\sum a_n$ は収束するから

$|\sum^p_{n=1} a_n-\sum^q_{n=1} a_n|<\epsilon$

はCauchy列。

特に $q=N_1$ の場合を考えると、

$k>N_1$ について

$|\sum^k_{n=N_1+1} a_n|<\epsilon$ 

$B=\lbrace k \in \mathbb{N} ; k>N_1,\exists N_2 <\infty, k<N_2 \rbrace$

とすると、

$|\sum_{n\in B}a_n| < \epsilon$

$A=\lbrace \sigma^{-1}(1), \dots ,\sigma^{-1}(N_1) \rbrace$ とおく

$k>N_1,k<\max A$ なる $k$ について

$$\sum^k_{n=1} a_{\sigma(n)}=\sum_{n\in A}a_{\sigma(n)}+\sum_{n\in\lbrace 1,2,\dots k \rbrace \setminus A}a_{\sigma(n)}$$
$$\sum^{N_1}_{N=1}a_n + \sum_{n \in B}a_n$$

## References 
絶対収束する無限級数は和の順序を並べ替えても同じ値に収束する https://youtu.be/qKTdnL6B9oI?si=bJzkmxiLn1-7xel_ via @YouTube 
