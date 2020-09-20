

## 1. Introduction


There are two ways in which economists have studied market economies:
- General equilibrium (Leon Walras): whole economy
- Partial Equilibrium (Alfred Marshall): a single sector in isolation

Here we study **Partial Equilibrium**:
 - Clearing of market for a **single** good independently from other markets. 
- Prices of substitutes and complements \& income levels of consumers  taken as given. 
- Surplus, welfare, comparative statics: all effects studied in one market in isolation




Partial equilibrium model much simpler than General Equilibrium Models.


**But:** Does not appropriately model real-world economic phenomena (cross-effects)

Differences to General Equilibrium: 
- No trade between consumers
- No trade between firms
- Consumers own "money" which they give to firms in exchange for goods


| |Partial Equilibrium| General Equilibrium|
|-|---|---|
| Developed by| Alfred Marshall| Léon Walras|
| Considers| One good vs "everything else"| Whole Economy|
| Underlying Assumption | Markets for different goods independent    | Markets for different goods are interdependent. |
| Equilibrium| Price based on prices of other goods being constant| Prices of goods are determined simultaneously   |
| Pros| Tractable, welfare analysis and comparative statics feasible | More realistic|
| Cons| Some interactions are ignored | More difficult|





## 2. Consumers





**General assumptions**: Consumers are rational!

- Maximize their own "utility"
- Understand all aspects of the market
- Unlimited computational power




#### Quasi-linear utility model


- Partial model: consider one good $x$ as a "tiny" part of the economy

- Bundle everything else together and call it "money" (denoted by $m$)

- That the market for $x$ is negligable implies...
  - **negligable wealth effects**: tiny portion of income allocated to $x$
  - **price independence**: change in the price for $x$ does not change prices in rest of economy and vice versa.
  
  
**These assumptions motivate "quasi-linear" preferences of consumers!**


In a quasi-linear utility model, consumers' preferences are represented by

$$\begin{aligned}U(x,m) = u(x)+m\end{aligned}$$

  - $x$ is the good
- $m$ is money (= everything else)
- $p$ is the market price for $x$
- $u$ is increasing and concave (=inverse u-shape)





#### Individual demand in quasi-linear model

<br>

Consumer $i$ maximises  utility:

  $$\max_{x,m}\ u(x)+m  $$
  subject to the budget constraint 
  $$px+m=I$$

  where $I$ is the given income of the consumer.

We rearrange the budget constraint and substitute for $m$ to obtain the unconstrained problem:
 $$\max_{x}\ u(x)-px+I  $$
To maximize, solve first-order condition
$$u'(x)=p$$
<br>

The demand of this consumer is a function $x^*(p)$ such that $u'(x^*(p))=p$ for all $p$






**No wealth-effects in the quasi-linear model**
<br>

![center ](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_quasi_linear/fig_quasi_linear.png?raw=true)


 





##### Fundamental Law of Demand

How does demand react to price changes?

- Recall: demand function $x^*(p)$ solves $u'(x^*(p))=p$
- Suppose the price increases: $\hat p>p$, so that $u'(x^*(p))<\hat p$
- $u$ is concave, so $u'(x)$ decreases in $x$
- Therefore: $x^*(\hat p)<x^*(p)$ 

Decreasing demand function:  **Fundamental Law of Demand** 



#### Aggregate Demand



- Suppose $n$ individuals in the market with demands $x_1^*(p)$, $x_2^*(p)$, ..., $x_n^*(p)$
- **Aggregate demand** = sum of individual demands 
$$
    D(p)=x_1^*(p)+...+x_n^*(p)=\sum_{i=1}^n x^*_i(p).
$$
- If identical preferences $x_i^*(p)=x^*(p)$, then $D(p)=n x^*(p).$

 




#### Inverse demand

If demand is strictly decreasing, we can invert it:

- **Demand curve:** quantity $q=D(p)$ demanded at price $p$.

- **Inverse demand function:** price $p=P^D(q)$ such that consumers demand $q$. 

Graphically, this corresponds to mirroring the demand curve along the $45^o$ line.





![center 120%](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_demand/fig_demand0001.png?raw=true)






#### Inverse demand and marginal utility

For simplicity, suppose there are n identical consumers. 

Recall that for each $p$, the demand function of each consumer solves:
$$u'(x^*(p))=p$$

For given $q$, we have $x^*(p)=q/n$, and $p=P^D(q)$, so we can write
$$
u'(q/n)=P^D(q)
$$

**Lesson:** 

    For a given aggregate demand q, the inverse demand measures the corresponding 
    consumers' marginal utility


---

**Exercise:** Let a consumer's quasi-linear utility function be given by 
$$U(x,m)=u(x)+m$$ 
where $u(x)=x-x^2/2$.
1. Verify that $u''(x)<0$ and calculate the consumer's demand function.
2. Suppose there are 2 consumers with quasi-linear utility $U(x,m)$. Calculate Aggregate Demand.
3. Calculate the inverse demand.

---





## 3. Firms



#### Profit maximisation and cost functions

Assumptions:
- Firms convert money into the consumption good
- The cost of producing an amount $q$ of the good is given by a cost function $C(q)$
- Firms are negligable in size compared to the market (= price-takers)
- Maximize profits



#### Cost Functions

The total cost of production is the sum of fixed and variable costs
$$
C(q)=c(q)+F
$$

where
-  $F$: fixed costs, e.g., set-up costs
-  $c(q)$: costs that vary with output, e.g., labor.









**Marginal cost**: the cost of an additional (infinitesimal) unit of output; the slope of the cost curve at a given output level
$$
MC(q):=c'(q)
$$


**Average cost**: "cost per unit".  For $q>0$ the firm's average total cost function is
$$
AC(q)=\frac{c(q)}{q}+\frac{F}{q}
$$
**Notation**: we write $AVC_j$ for the *average variable cost* and $AFC_j$ for the *average fixed cost*.





#### Convexity of costs

We typically assume that the cost function is convex: $C''(q)>0$

Reflects **Law of diminishing returns from production**: Using production processes more intensively makes it over-proportionally less efficient

Convexity of costs implies
- profit maximisation problem has a unique solution
- marginal cost increasing 
- average cost curve has an inverse u-shape
- marginal cost curve and intersects average cost at its minimum.


**Why intersections marginal cost the average cost at its minimum??**

- Average cost is $AC(q)=C(q)/q$
- If we produce one more item 
    - at a price below average cost, then the new average cost will be lower
    - at a price above average cost, then the new average cost will be higher
- With convex cost, $MC$ is increasing, so $MC$ and $AC$  must intersect once, at the minimum of $AC$



![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_cost/fig_cost_2.png?raw=true)



#### Individual supply of the firm
<br>

- Firm maximises profits:
$$
\max_q \pi(q)=pq-C(q)
$$
- The first-order condition for optimal output is 
$$
p=C'(q)
$$
- The supply of the firm is a function $y^*(p)$ such that $p=C'(y^*(p))$ for all $p$. 





#### Aggregate supply


- Suppose $m$ firms in the market with supplies $y_1^*(p)$, $y_2^*(p)$, ..., $y_n^*(p)$
- **Aggregate supply** = sum of individual supplies 
$$
    S(p)=y_1^*(p)+...+y_n^*(p)=\sum_{j=1}^n y^*_j(p).
$$
- If identical supply functions: $y_i^*(p)=y^*(p)$, then $S(p)=m y^*(p).$



#### Properties of aggregate supply 

- If each $c_j$ is convex, then $S(p)$ is increasing!  **Intuition:** if $p$ increases, produce additional units until marginal cost reaches the new price  
- Inverse supply: we can invert $S(p)$ and obtain a function $P^S(q)$ which gives the price that induces a given supply $q$.



**Exercise:** Consider the cost function 
$$
C(q)=10+\frac{q^2}{2}
$$

1.  Draw  marginal cost, average cost average variable cost and the average fixed cost corresponding to $C(q)$
2.  Derive the firm's indidivual supply function
3.  Suppose there are 10 firms. Find the Aggregate Supply. 








<!-- _class: lead -->

## 6. Competitive Equilibrium

- We now take the aggregate demand and supply function to characterize market equilibria. 

- **Basic idea:** find a price such that aggregate demand meets aggregate supply.

- Formally, we want find a price $p$ such that $D(p)=S(p)$
- This is called the "market clearing condition". 






#### Short-run competitive market equilibrium
<br>
We first consider competitive equilibrium in the short-run. 

Short-run: 
 - Fixed cost are sunk, so firms ignore them
 - No entry of new firms
 - No exit of existing firms





**Definition**: A **short-run competitive market equilibrium** consists of a price $p^*$ and an allocation $(x_1^*,\ldots, x_n^*)$ of individual demands and an allocation $(y_1^*,\ldots, y_m^*)$ of individual supplies such that

-  $D(p^*)=S(p^*)$,
-  $x_i^*$ maximizes consumer $i$'s utility at price $p^*$ for each $i$, 
-  $y_j^*$ maximizes the profit of firm $j$ at price $p^*$ for each $j$.



#### Properties of the competitive equilibrium: 


- In equilibrium, the market clears 
    - Each buyers receives the quantity she demands
    - Each firm sells the quantity it wants to supply 
-  There is neither excess demand nor excess supply     §
- There is no way to improve the outcome! $\to$ Efficiency!





![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_equilibrium.png?raw=true)






#### Long-run equilibria

- Does the fact that equilibria are efficient rule out firm profits or losses? No! 
- Not a stable equilibrium in the long-run

Long-run equilibrium allows for entry and exit: 

  -  profits attract new firms, supply increases, market price falls
  -  lfirms who shut down exit, supply falls and market price increases

$\rightarrow\,$ profits or losses to disappear in the long-run*. 






**Definition:** A **long-run competitive equilibrium** consists of a price $p^*$, a number of firms $m^*$, an allocation of demands $(x_1^*,\ldots, x_n^*)$ of individual demands and an allocation $(y_1^*,\ldots, y_m^*)$ of individual supplies such that such that $(p^*,x^*,y^*)$ is a short-run equilibrium and 
$$
\pi_j^*(p^*)=0
$$
for all $j=1,2, \ldots,m$.




**Difference between short-run and long-run in short:**
- Short-run equilibrium: $MC=p$
- Long-run equilibrium: $MC=AC=p$ 

Or in words:
- Short-run: firms only consider marginal cost ignore fixed consists
- long-run: firms take marginal and fix cost into account


**Diagram 1**: Losses in the short run

- Average cost above price
- Firms make losses 
- Firms exit!

![bg right:55% w:15cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/compet_eq_exit.png?raw=true)




**Diagram 2**: Profits in the short run
- Average cost below price
- Firms make profits 
- New firms enter!

![small](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/compet_eq_entry.png?raw=true)









**Technical note:** Integer Problems


 - Sometimes the number of firms in the long run is not a whole number
 - Two solutions:
    1. Redefine equilibrium. No firm in the market makes losses and no additional firm can make a profit
    2. Make firms "infinitesimal" (negligibly small). Then $m^*$ represents a "mass" of firms (infinitely many points)









**Exercise**: Derive an equilibrium mathematically

Consider the following market: 
- 800 consumers with income $I$ maximise utility utility $\log(x)+m$ subject to the budget constraint $px+m=I$. 

- 200 suppliers with cost function $C(y)=y^2/2$.








<!-- _class: lead -->


--- 

## 4. Elasticities



#### 4.1 Demand Elasticity

- *elasticity* = sensitivity of demand changes in response to price changes

- How to measure? Slope of demand curve would work:
$$D'(p)=\frac{\Delta D(p)}{\Delta p}$$

- But then our measure of elasticity will depend on how we measure things (smaller units, larger change)

- Solution: measure changes **proportionally** in %



**Informal definition of demand elasticity**
<br>

$$\text{demand elasticty}=\frac{\text{\% change in demand}}{\text{\% change in price}}$$

In words: 

    The elasticity of demand is defined as the % change in demand resulting 
    from a price increase, divided by the % change in price




We distinguish between two measures of elasticity 
  - Arc-price elasticity: sensitivity of demand between two different prices 
  - Point-price elasticity: sensitivity of demand "locally" at a given price $p$



#### 4.2 Notions of elasticity

**Arc-price elasticity**


Arc-price elasticity measures sensitity of demand to large changes in price.

**Definition**: The *arc-price elasticity* of a demand  $D$ between prices $p$ and $p'>p$ is 
$$
\epsilon_A(p,p')=\left|\frac{\left(\frac{D(p')-D(p)}{D(p)}\right)}{\left(\frac{p'-p}{p}\right)}\right|.
$$

Note: demand is decreasing, so we have $\epsilon(p)\in [0,\infty)$.



**Point-price elasticity**

Point-price elasticity measures sensitity of demand to marginal changes in price at a given point.


**Definition**: The *point-price elasticity* of a differentiable demand function $D$ at price $p$ is defined as
$$
\epsilon_P(p)=\lim_{p'\to p}\left|\frac{\left(\frac{D(p')-D(p)}{D(p)}\right)}{\left(\frac{p'-p}{p}\right)}\right|=\left|D'(p)\frac{p}{D(p)}\right|.
$$

Note: demand is decreasing, so we have $\epsilon(p)\in [0,\infty)$.





![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/elasticity2.png?raw=true)




**Terminology:** Elastic vs inelastic demand

We call a demand function $D(p)$  ...

- ... elastic at $p$ if $\epsilon(p)>1$
- ... unit-elastic at $p$ if $\epsilon(p)=1$ 
- ... inelastic at $p$ if $\epsilon(p)<1$





#### 4.3 Supply Elasticity

Supply elasticity is defined in the same way as demand elasticity
<br>
$$\text{supply elasticty}=\frac{\text{\% change in supply}}{\text{\% change in price}}$$

- The definition of arc- and point-price elasticities are analogous to the demand case



**Exercises:** 
- Calculate the arc-price elasticity of the demand $D(p)=\max\{1-p,0\}$
- Derive the point-price elasticity of $D(p)=1/p^e$, where $e$ is an arbitrary positive number
- Calculate the arc-price elasticity of the supply function $S(p)=p^2$






<!-- _class: lead -->


---

## 5. Surplus and Welfare



#### 5.1 Consumer Surplus

- How should we measure market performance and "gains from trade"?


- In his seminal book Principles of Economics (1890), Alfred Marshall  proposes to measure "surplus pleasure":

  > The price which a person pays for a thing can never exceed, and seldom comes up to that which he would be willing to pay rather than go without it [...]; and he thus derives from the purchase a surplus of pleasure. **The excess of the price which he would be willing to pay rather than go without it, over that which he actually does pay**, is the economic measure of this **surplus pleasure.** 

*(Alfred Marshall, 1890)*





In other words: consumer surplus are the consumers' **gains from trade**

For simplicity: infinitely many identical consumers of mass 1

Each consumer has utility $U(x,m)=u(x)+m$. 
- Utility of consumer with wealth $m$ and without trade: $u(0)+m$
- Utility of consumer with wealth $m$ who buys $x$ goods at price $p$: $u(x)+m-px$

Consumer surplus from such a trade at given price $p$:
$$CS(x)=u(x)-u(0)-px$$




**How can we illustrate consumer surplus in our diagrams?**
#


$$
\begin{aligned}
CS(x)&=u(x)-u(0)-px\\
&=\int_0^x(u'(q)-p)dq\\
&=\int_0^x(P^D(q)-p)dq\\
\end{aligned}
$$


![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/consumer_surplus.png?raw=true)


**Calculate Surplus with linear demand**

![center w:20cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/consumer_surplus_2.png?raw=true)



**Lesson:**

    Consumer surplus at a given quantity and price, is the area bounded 
    above by the inverse demand curve and below by the horizontal price line 



#### 5.2 Producer Surplus


The producer surplus is defined in a similar way. 

**Producer surplus:** profits = the revenue a firm receives from selling a good at a given price minus the cost of producing it

Since firms are price-takers, at a fixed price $p$, producer surplus at quantity $q$ is
$$PS(q)=pq-c(q)$$



Similar to the consumer surplus case, we can represent this in our standard diagrams.

Marginal profit is: 
$$PS'(q)=p-c'(q)$$

Recall from profit maximisation problem: $c'(q)=P^S(q)$ (recall that $P^S$ is the inverse supply function). Substitute
$$PS'(q)=p-P^S(q)$$

The total producer surplus is thus the area underneath the price line and above the inverse supply curve, up to total quantity: 
$$PS(\hat q)=\int_0^{\hat q}(p-P^S(q))dq$$


![center w:23cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/producer_surplus.png?raw=true)







#### 5.3  Welfare 

The "welfare" generated in the market which is the total gains it generates. 

**Definition:** The **(Social) Welfare** is the sum of consumer and producer
$$W(q):=CS(q)+PS(q)$$




![bg left:60% contain](https://core-econ.org/the-economy/book/images/web/figure-08-05-01-02.jpg)


Welfare represents the sum of consumers surplus (utility gain) and producer surplus (profits)







---





**Exercises:** 

1. Calculate the consumer surplus for the demand functions
    - $D(p)=\max\{1-p,0\}$ 
    - $D(p)=\max\{\sqrt{1-p},0\}$
2. Calculate the producer surplus for the  supply function $S(p)=p^2$. 
3. For a given pair of demand and supply functions, at which price is welfare maximised?




---





<!-- _class: lead -->

## 6. Taxes



- We now use the notions of consumer surplus to evaluate the effect of a goverment tax. 
- Quantity tax $t$: for any purchase of $q$ units, pay tax $t\cdot q$
- In equilibrium, consumers and producers face different prices:
  - Price paid by consumers: $\hat p_c$
  - Price paid by firms: $\hat p_f$
  - Price difference: $\hat p_c=\hat p_f+t$



**Equilibrium with taxation:**
- Tax is equivalent to a shift in demand or a shift in supply
- In equilibrium, markets must clear: 
  - quantity demanded by consumers must equal the quantity supplied by firms 
  - at the equilibrium quantity $q^*$, the difference between price paid by consumers and received by firms must equal the tax
$$
P^D(q^*)=P^S(q^*)+t
$$

What about surplus?


![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_deadweight/fig_deadweight0005.png?raw=true)



#### Tax Incidence: who pays the tax? 

- The distribution of tax burden determined by relative elasticities of demand and supply
  - consumers bear more burden if demand more inelastic than supply
  - firms bear more burden if supply more inelastic than demand
- The higher the elasticity of demand and supply, the larger the deadweight loss


**Consumers bear burden when demand perfectly inelastic:**


![center w:30cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/tax_incidence/tax_incidence_producers.png?raw=true)


**Firms bear burden when supply perfectly inelastic:**

![center w:30cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/tax_incidence/tax_incidence_consumers.png?raw=true)







<!-- _class: lead -->

## 7. Market Power



#### 7.1 Monopoly

A *monopoly*  is a market for a good that is supplied by a single firm (from ancient greek *monopolion*, "a right of exclusive sale"), supplier in a monopoly is called a *monopolist*. 

**Examples of monopolists:**


  -  Microsoft, market for operating systems. Market share ' 90\%.
  -  Google: 70\% of US web searches, 70\% of online advertising market.
  -  Gillette, razor blades market, 72\% market share. 
  -  Utilities (electricity, water, telephone, rail, etc.)





#### Monopoly profits


Market price at supply $q$ is $P^D(q)$. 

Monopolist's profits
$$
\pi_m(q)=P^D(q)q - C(q) .
$$






To solve for the optimal level of output,  solve the f.o.c. 
$$
\pi_m'(q)=\underbrace{\frac{d}{dq}P^{D}(q)q +P^D(q)}_{:=MR(q)} \ - c'(q)=0
$$

Denote the solution by $q_m$. 




#### Properties of monopoly output

- Comparison with competitive equilibrium   

    - competitive equilibrium: output $q^*$ solve $MC(q)=P^D(q)$
    - monopoly output: output $q_m$ solves $MC(q)=MR(q)$ 

- Demand is decreasing $\frac{d}{dq}P^{D}(q)<0$, hence $MR(q)<P^D(q)$, 

- $\Rightarrow$ monopolist under-supplies the market: $q_m<q^*$!! 




![center w:25cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/monopoly-pricing.png?raw=true)




#### Inverse Elastiticy Rule

Intuitively, a monopolist can exploit the fact that demand is inelastic.

The relationship between the profit for the monopolist and elasticity of demand s captured by the **Inverse Elasticity Rule**.

Consider the marginal revenue for the monopolist:
$$
(*) \ \ \ MR(q)=P^D(q) + P^{D'}(q)q= P^D(q) \Big(1 + {\color{red}\underbrace{P^{D'}(q)\frac{q }{P^D(q)}}_{=-1/\epsilon}}\Big)
$$




Since $P^D(q)$ is the inverse of $D(p)$:
$$D(P^D(q))=q\Rightarrow D'(P^D(q))P^{D'}(q)=1\Rightarrow P^{D'}(q)=\frac{1}{D'(P^D(q))}$$

Further, recall the definition of elasticity of demand

$$P^{D'}(q)\frac{q }{P^D(q)}=\frac{1}{D'(P^D(q))}\frac{D(p)}{p}=-\frac{1}{\epsilon(p)}$$


Substituting the first and then the second identity into into equation $(*)$ on the previous slide, we find 
$$(**)\ \ \ MR(q)=P^D(q) \left(1 - \frac{1}{\epsilon(P^D(q))}\right)$$




If we now substitute $(**)$ into the first-order condition for the monopolist's profit maximization problem, we have
$$
P^D(q) \left(1 -\frac{1}{\epsilon(P^D(q))}\right)=MC(q)
$$
If we now rearrange this equality, we obtain
$$
L:=\frac{P^D(q)-MC(q)}{P^D(q)}=\frac{1}{\epsilon(P^D(q))}
$$
This equation is known as the **inverse elasticity rule**.  The expression on the left-hand side is called the Lerner index and the difference $P^D(q)-MC(q)$ is the "mark-up". 



**Why do we need the inverse elasticity rule**?
 - Can be used to calculate monopoly price directly when elasticity of demand is known
 - Monopolist operates in elastic region of demand $(\epsilon>1)$! Why? 
$$
\begin{aligned}
\frac{1}{\epsilon(P^D(q))}=\frac{P^D(q)-MC(q)}{P^D(q)} < 1&
\Longrightarrow\ 
\epsilon(P^D(q))>1
\end{aligned}
$$
*(Recall: When demand is inelastic, a price increase leads to a less than proportionate decrease in quantity demanded)*



#### Two-Part Tariffs

- So far we assumed the monopolist sets a uniform price. 

- The monopolist can do better with so-called two-part tariffs!

- Basic idea: in addition to a per unit price, charge an upfront fee

- With a "two-part" tariff, the monopolist supplies the efficient amount

- BUT: the monopolist extracts the entire surplus!!


**Optimal two-part tariff**

- Principal supplies $q$ at price $p=P^D(q)$. 
- Consumer willing to pay $T\le CS(q)$ upfront. 
- Price equal to competitive price: $p^*$ $\rightarrow$ demand $q^*=D(p^*)$
- Fee equal to surplus $T^*=CS(q^*)$. 
- Monopolists extracts all surplus: 
    - Consumers demand efficient quantity
    - Monopolist is paid upfront





![](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/two_part_tariff.png?raw=true)









#### 7.2 Oligopoly: Cournot model



- Two symmetric firms that supply entire market. 
- Not price takers: they affect price through outputs
- Firms sets their outputs 
  - independently (no coordination)
  - simultaneously (cannot observe the choice of the other firm)



Profit of firm $i$:
$$\pi_i(q_1,q_2)=P^D(q_1+q_2)q_i-C(q_i)$$
<br>

**Market Equilibrium:** A Cournot Equilibrium is a pair of outputs $(q_1^*,q_2^*)$ such that output $q_1^*$ maximizes the profit of firm 1 given $q^*_2$, and vice versa.





#### Linear Cournot

For simplicity, suppose we have an inverse demand function 
$$P^D(q)=a-bq$$
and linear cost $C(q)=c q$




The profit maximization problems of both firms are
$$
\begin{aligned}
\max_{q_1} \big(a-b(q_1 + q_2^*)\big)q_1 - c q_1,\\
\max_{q_2} \big(a-b(q_1^* + q_2)\big)q_2 - c q_2.
\end{aligned}
$$









The first-order conditions associated with these maximization problems are
$$
\begin{aligned}
a-2bq_1^* - bq_2^* - c =0\Longrightarrow q_1=\frac{a-c-bq_2^*}{2b}\\
a-bq_1^* -2 bq_2^* - c =0\Longrightarrow q_2=\frac{a-c-bq_1^*}{2b}.
\end{aligned}
$$

Two find the Cournot equilibrium, we solve the second equation for $q_2^*$ and substitute in the first to solve for $q_1^*$. This yields the solution
$$
q^*:=q_1^*=q_2^*=\frac{a-c}{3b}.
$$








![center w:15cm](https://github.com/peteawag/ECO00001I-A-Microeconomics-II-2019/blob/master/img/fig_cournot/fig_cournot0001.png?raw=true)


---


**Exercise:** Suppose our demand function is $D(p)=8-p$ and firms have  zero cost $c(\cdot)=0$. 

1. Calculate the competitive equilibrium
2. Calculate the monopoly output and price
3. Calculate the Cournot equilibrium price and quantity
4. Rank each allocation in terms of the total welfare it generates





---


## Review Questions

- What is the purpose of the Partial Equilibrium model?
- What is quasi-linear utility, and why do we use these types of preferences?
- What is the purpose of "elasticity", and why do we define it in terms of %-changes? 
- How do we calculate social welfare, and how is welfare represented in a price/quantity diagramme?
- Why does a monopolist undersupply the market?
- What is the meaning of the "inverse elasticity rule" and why do we need it?
- What is the difference between an oligopoly and a perfectly competitive market?







