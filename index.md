---
layout: default
---

Hi, I am Shourya Bose, an aspiring researcher in the field of Control Theory.

Currently I am a research intern at the Department of Electrical Engineering
at the Indian Institute of Science in the [**Control and Network Systems Group**](http://www.ee.iisc.ac.in/people/faculty/pavant/group.html).
I will be graduating from the Dual Degree scheme
at BITS Pilani (Goa Campus) with M.Sc. (_Hons._) Mathematics, and B.E. (_Hons._) Electrical and
Electronics Engineering at the end of December 2019.

My research interests include various aspects of Networked Control Systems.

You can download my CV [**here**](./shourya_bose_curr_vitae.pdf).

# Research

Currently, I am working as a co-author on a journal paper on stabilization of stochastic systems over channels
modeled as **decision-based Markov channels**. For more information on this topic, please refer to the ICC conference paper below.

My previous publications (2) are as follows:

### Event-Triggered Second Moment Stabilization under Markov Packet Drops ([**Link**](https://ieeexplore.ieee.org/document/8715576))

**Presented at the Fifth Indian Control Conference, IIT Delhi, 2019**

This paper deals with networked control system wherein the system evolution is noisy.
Furthermore, in the considered system, state measurements are made by a sensor and control action is apploed by a controller. However,
the sesnor and the controller are not co-located, and must instead communicate over an unreliable communication channel.

In this specific setting, we consider a system whose evolution is linear with additive noise. Furthermore, we model the channel
as a **Markov channel**, which is a class of channels broad enough to cover practical channels with packet-based communications
wherein packet losses are possible. Assuming that the system is stabilizable in closed-loop, we propose a transmission algorithm
which ensures that the stabilization of the channel also takes place over said channel. We provide a theoretical proof to demonstrate
the same.

Furthermore, we carry out a transmission fraction analysis, which demonstrates that our algorithm leads to a judicious use of channel resources.
Simulations carried out in MATLAB to validate the theoretical results are also presented.

### Numerical Solution for a System of Fractional Differential Equations with Applications in Fluid Dynamics and Chemical Engineering ([**Link**](https://www.degruyter.com/view/j/ijcre.2017.15.issue-5/ijcre-2017-0093/ijcre-2017-0093.xml))

**Published in International Journal of Chemical Reactor Engineering (DeGruyter)**

This paper deals with numerical solution of Fractional Order Differential Equations (FODE's) over a finite time horizon.
We consider a system of n nonlinear coupled FODE's, with them possibly having different fractional indices. We decompose the fractional
derivative using the Haar Wavelet as a functional basis, and then use a Galerkin-based residual method to get a finite-basis representation
of the fractional derivative.

The solution methodology involves computing the fractional integral of the haar wavelet, for which a closed-form matrix representation
already exists in literature. We then carry out an error analysis of the residual, and this allows
us to demonstrate that as the number of haar wavelet bases used increases, the error between the proposed numerical method and the
actual solution vanished.

We validate our algorithm by solving several non-trivial ODE's proposed in chemical engineering literature using
our method using MATLAB.


There should be whitespace between paragraphs.
    
There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
