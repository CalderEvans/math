---
title: Calculus 2 Help
author: Dana Ernst
layout: default
---

 <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>

<br>
<p style="font-size: 50px; text-align: center;  font-weight: bold"> Calculus 2 </p>
<br>
<p style="font-size: 30px; text-align: left; font-weight: bold"> Area Between Curves </p>
<b>1.</b> Calculate the area between the curves <span style="color: blue;"> $x=y^2+1$ </span> and <span style="color: red;">$x=9-y^2$</span>. 
<details>
  <summary> Show Solution </summary>
  <p>
    <br>
    Below we can see our curves graphed, you may or may not be given an image for your problem so you should practice knowing what they look like without the image.
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
  </p>
</details>

<br>
<br>
<br>

<b> 2. </b> Calculate the area between the curves <span style="color: blue" > $y=4x$ </span>, <span style="color: red"> $y=2x^2$ </span>, and <span style="color: green"> $x=3$</span>. 
<details>
  <summary> Show Solution </summary>
  <p>
    Below we can see our curves graphed, you may or may not be given an image for your problem so you should practice knowing what they look like without the image.
    <div style="text-align: center;">
    <img src="{{ site.baseurl }}/images/AreaBetweenCurves2.png" style="width: 35%;" />
    </div>
    Again, we will set the two equations equal to each other to find their intersection points.
      <div style="text-align: center;"> 
        <span style="color:blue"> $4x$ </span> $=$ <span style="color:red"> $2x^2$ </span> <br>
        $2x = x^2$ <br>
        $x=0$ &  $x=2$
      </div>
    Now we know that the curves <span style="color: blue"> $y=4x$ </span> and <span style="color: red"> $y=2x^2$ </span> intersect at $0$ and $2$. But we also have another curve, <span style="color: green"> $x=3$</span>, this curve will create another section of area. We can also see that we will have two integrals to add together since there are parts of the graph where<span style="color: blue"> $y=4x$ </span> is on top and parts where<span style="color: red"> $y=2x^2$</span> is on top. <br>
    From $0$ to $2$, <span style="color: blue"> $y=4x$ </span> is on top of <span style="color: red">$y=2x^2$</span>, and from $2$ to $3$, <span style="color: red"> $y=2x^2$ </span> is on top of <span style="color: blue">$y=4x$ </span>. Thus, the resulting integral is
    <div style="text-align: center;"> 
        \[ \int_{0}^{2}4x-2x^2 \hspace{2mm} dx + \int_{2}^{3}2x^2-4x \hspace{2mm} dx \]
    </div>
      <div style="padding-left: 330px;">
        \[
        \begin{aligned} 
          &= (2x^2-\frac{2}{3}x^3)\bigg|_{0}^{2}  + (\frac{2}{3}x^3 - 2x^2)\bigg|_{2}^{3} \\
          &= \Bigl[ (2(2)^2-\frac{2}{3}(2)^3) - (2(0)^2-\frac{2}{3}(0)^3) \Bigr] +  \Bigl[ (\frac{2}{3}(3)^3 - 2(3)^2)- (\frac{2}{3}(2)^3 - 2(2)^2) \Bigr] \\
          &= \Bigl[ 8-\frac{16}{3}\Bigr] + \Bigl[ (\frac{54}{3} - 18) - (\frac{16}{3} - 8)\Bigr]\\
          &= \Bigl[ \frac{24}{3}-\frac{16}{3}\Bigr] + \Bigl[(18 - 18) - (\frac{16}{3} - \frac{24}{3}) \Bigr] \\
          &= \frac{8}{3} + \bigl[0-(-\frac{8}{3})\bigr] \\
          &= \frac{8}{3} + \frac{8}{3} \\
          &= \boxed{\frac{16}{3}} \\
        \end{aligned}
        \]
      </div>
    </p>
</details>
<br>
<br>
<br>