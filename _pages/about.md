---
permalink: /
title: "Prof Paul D Stevenson Academic Website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Professor in the School of Maths and Physics of the [University of Surrey](http://www.surrey.ac.uk),  member of the [Nuclear Physics Group](https://www.surrey.ac.uk/theoretical-nuclear-physics-group) and the [Quantum Foundations and Technology](https://www.surrey.ac.uk/quantum-foundations-centre) group, and an AWE William Penney Fellow.

My research is mainly in theoretical nuclear physics and quantum computing, with some occasional projects in quantum biology and chemsitry, and in computational methods.  Further details can be found in the [Research](/research) tabs, with a full list of outputs in the [Publications](/publications) tab.

I write a blog about nuclear physics (loosely) called [blog of the isotopes](http://blogoftheisotopes.blogspot.com) and contribute occassionally to blogs about [plotting](http://spplotters.blogspot.com), and the [Physics Department's blog](http://blogs.surrey.ac.uk/physics).

See also my [official University of Surrey Page](https://www.surrey.ac.uk/people/paul-stevenson) page.

You can contact me on [p.stevenson@surrey.ac.uk](mailto:p.stevenson@surrey.ac.uk)

{% include base_path %}
{% for post in site.posts limit:1 %}
  {% include archive-single.html %}
{% endfor %}
  
