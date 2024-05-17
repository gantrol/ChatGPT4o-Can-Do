# ChatGPT4o Can Do

## PDF copy content to Markdown

For example, copy some content from [PDF of *Distinct Elements in Streams: An Algorithm for
the (Text) Book*](https://arxiv.org/pdf/2301.10191):

```txt
Bounding Pr[Error2 ∩ Bad2]
Let us define the event Error2,q : ‘pm = 2−q and |Xm|
2−q ∈/ [(1 − ϵ)F0,(1 + ϵ)F0] ’
Observe that Pr[Error2,q] ≤ Pr[|Yq,m| ∈/ [(1 − ϵ) ·
F0
2
q ,(1 + ϵ) ·
F0
2
q ]].
```

ChatGPT4o gives:

```markdown
**Bounding $\Pr[\text{Error2} \cap \text{Bad2}]$**

Let us define the event $\text{Error2,q}$: $p_m = 2^{-q}$ and $\left| \frac{X_m}{2^{-q}} \right| \notin [(1 - \epsilon)F_0, (1 + \epsilon)F_0]$.

Observe that $\Pr[\text{Error2,q}] \leq \Pr\left[\left|Y_{q,m}\right| \notin \left[(1 - \epsilon) \cdot \frac{F_0}{2^q}, (1 + \epsilon) \cdot \frac{F_0}{2^q}\right]\right]$.
```

That is:

**Bounding $\Pr[\text{Error2} \cap \text{Bad2}]$**

Let us define the event $\text{Error2,q}$: $p_m = 2^{-q}$ and $\left| \frac{X_m}{2^{-q}} \right| \notin [(1 - \epsilon)F_0, (1 + \epsilon)F_0]$.

Observe that $\Pr[\text{Error2,q}] \leq \Pr\left[\left|Y_{q,m}\right| \notin \left[(1 - \epsilon) \cdot \frac{F_0}{2^q}, (1 + \epsilon) \cdot \frac{F_0}{2^q}\right]\right]$.



The full chat history transforms the full PDF to Markdown: https://chatgpt.com/share/54a5c725-2224-47db-a1d9-f0343aa65507
