---
title: Here's Some Math Nandor
author: Dana Ernst
layout: default
---

 <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>

## Playground

Edit this page to include either the Fundamental Theorem of Calculus, the First Isomorphism Theorem for Groups, or the Central Limit Theorem.  Use correct mathematical typesetting.

If $\phi: G \rightarrow H$ is a homomorphism of groups, then $\ker(\phi) \unlhd G $ and $\frac{G}{\ker(\phi)} \cong \phi(G)$ 

## Calc 2 Preperation: 
<b>1.</b> Calculate the area between the curves <p style="color: blue;"> $x=y^2+1$ </p> and <p style="color: red;">$x=9-y^2$ <p>.
<img src="{{ site.baseurl }}/images/AreaBetweenCurves.png"/>
<body>
  <div style="text-align: center;">
    \[ \int_{-2}^{2} \left(9 - y^2 - (y^2 + 1)\right) dy \]
  </div>

  <div style="padding-left: 110px;">
    \[
    \begin{aligned}
      &= \int_{-2}^{2} -2y^2 + 8 \; dy \\
      &= \left(-\tfrac{2}{3}y^3 + 8y\right)\bigg|_{-2}^{2} \\
      &= \left(-\tfrac{16}{3} + 16\right) - \left(\tfrac{16}{3} - 16\right) \\
      &= -\tfrac{32}{3} + 32 \\
      &= 2\left(\tfrac{32}{3}\right) \\
      &= \boxed{\dfrac{64}{3}}
    \end{aligned}
    \]
  </div>
</body>