---
marp: true
paginate: true
---

<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
section.lead h1 {
  text-align: center;
  font-size: 50pt;
}
section.lead  {
  text-align: center;
  font-size: 25pt;
}
</style>

1. Second derivatives of $u$ is $u''(x)=-1<0$. FOC: 
$u'(x)=p$ which yields 
$$u'(x)=p\Rightarrow x^*(p)=1-p$$ 
2. Aggregate Demand: 
$$D(p)=2x^*(p)=2-2p$$
3. Inverse Demand 
$$P^D(q)=1-q/2$$

---

---

**Exercse 2:** Calculate the 

---



The marginal demand (first derivative) is $D'(p)=-1$ when $p<1$. 

Use the formula: 
$$\epsilon(p)=D'(p)\frac{p}{D(p)}=(-1)\cdot\frac{p}{1-p}$$

The price elasticity of demand for such a demand function is 
$$
\epsilon(p)=
\begin{cases}
0 &\text{ if }p>1\\
-\frac{p}{1-p}&\text{ if }p\le 1\\
\end{cases}
$$ 
For $p\searrow 0$: elasticity goes to zero. For $p\nearrow 1$: elasticity goes to infinity


---
![bg left:66% 90%](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/elasticity.png?raw=true)

**Intuition:**

When $p$ close to 1 demand is small, and  change in prices has large proportional effect on demand.

Opposite holds when $p$ close to 0.

---


**Exercise:** Constant elasticity of demand 

We saw that the elasticity of  linear demand functions depends on the price. 

Another important class of demand functions is constant elasticity demand:

$$D(p)=A/p^\epsilon$$


This demand function has elasticity $-\epsilon$ (Exercise)

---

**Remark**: an equivalent way to define elasticities is 
$$
\epsilon(p)=\frac{d \log D(p)}{d\log p}.
$$

(Exercise!)




---

**Example:** Solving the firms' problem and determine Aggregate Supply

Suppose there are 10 identical firms with cost function $C(q)=10+q^2/2$. 

Average cost: $AC(q)=\frac{10+q^2/2}{q}=\frac{10}{q}+\frac{q}{2}$.

Marginal cost $MC(q)=q$.

Profit (Revenue minus cost) for each firm:
$$\pi(q)=pq-(10+q^2/2)$$

Optimal supply $q^*$ maximizes profit: $p=MC(q^*) =q^*$. 

$\rightarrow$ Each firm supplies $q^*(p)=p$ at price $p$.

Aggregate supply: $S(p)=10p$.

---

![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_cost/fig_cost.png?raw=true)
