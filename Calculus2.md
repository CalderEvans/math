---
title: Calculus 2 Help
author: Dana Ernst
layout: default
---

 <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>

<br>
<p style="font-size: 40px; text-align: center;"> Calculus 2 </p>
<br>
<p style="font-size: 30px; text-align: left; font-weight: bold"> Area Between Curves </p>
<b>1.</b> Calculate the area between the curves <span style="color: blue;"> $x=y^2+1$ </span> and <span style="color: red;">$x=9-y^2$ </span>. 
<br>
<div style="text-align: center;">
<img src="{{ site.baseurl }}/images/AreaBetweenCurves.png" style="width: 30%;" />
</div>
<body>
To find the area between the curves we need to first find their intersection points by setting the equations equal to each other.
</body>
<div style="text-align: center;">
    <span style="color: blue;"> $y^2+1$ </span> = <span style="color: red;"> $9-y^2$ </span> <br>
    $2y^2=8$ <br>
    $y^2=4$ <br> 
    $y=\pm 2$
</div>

<body>
We now know that the bounds for our integral will be $-2$ and $2$. Next, we have to set up our integral. When integrating in terms of $y$, always integrate "right - left", as opposed to when we integrate in terms of $x$ and integrate "top - bottom". In our shaded region, <span style="color: red;"> $9-y^2$ </span> is to the right of <span style="color: blue;"> $y^2+1$ </span>, so we shall integrate <span style="color: red;"> $9-y^2$ </span> $-$ (<span style="color: blue;"> $y^2+1$ )</span>.
</body>
<body>
  <div style="text-align: center;">
    \[ \int_{-2}^{2} \left(9 - y^2 - (y^2 + 1)\right) dy \]
  </div>

  <div style="padding-left: 30px;">
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
