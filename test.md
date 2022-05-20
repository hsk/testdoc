```tex
$$
\begin{array}{lr}
新しい構文形式\\
\begin{array}{llr}
\bbox[gray]T ::= & …    & \hspace{170px} 型：\\
      & \bbox[gray]{Bool} & ブール値型\\
\end{array}\\
\\
\begin{array}{cr}
新しい型付け規則 \hspace{100px} & \bbox[3px,border:1px solid black]{t : T}\\
\bbox[gray]{true : Bool}                          & \text{(T-True)}\\
\bbox[gray]{false : Bool}                         & \text{(T-False)}\\
\bbox[gray]{
\dfrac{t_1 : Bool \quad t_2 : T \quad t_3 : T}
{if\;t_1\;then\;t_2\;else\;t_3 : T}} & \text{(T-If)}\\
\end{array}
\end{array}
$$
```

$$
\begin{array}{lr}
新しい構文形式\\
\begin{array}{llr}
\bbox[gray]T ::= & …    & \hspace{170px} 型：\\
      & \bbox[gray]{Bool} & ブール値型\\
\end{array}\\
\\
\begin{array}{cr}
新しい型付け規則 \hspace{100px} & \bbox[3px,border:1px solid black]{t : T}\\
\bbox[gray]{true : Bool}                          & \text{(T-True)}\\
\bbox[gray]{false : Bool}                         & \text{(T-False)}\\
\bbox[gray]{
\dfrac{t_1 : Bool \quad t_2 : T \quad t_3 : T}
{if\;t_1\;then\;t_2\;else\;t_3 : T}} & \text{(T-If)}\\
\end{array}
\end{array}
$$
