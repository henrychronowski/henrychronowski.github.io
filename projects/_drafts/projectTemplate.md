---
title: "Project Template"
excerpt: "A template for project posts"
---

<!--
   Copyright 2022 Henry R. Chronowski

   Built from Daniel Buckstein's template at https://dbuckstein.github.io/
   
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->


<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


[Home](/projects/../)

[Blog](/blog/)

[Projects](/projects/)

[About](/about/)


# Hello Jekyll

I am trying my hand at creating a basic blog/portfolio site with Jekyll, to be hosted with GitHub Pages.  For all intents and purposes, this simple setup is perfect for both development on my local environment, and displaying on the web.  Check this out: 

![Display comparison](/assets/img/testscreen.png){:width="800px"}

On the left is how it looks like online (the real thing) and on the right is how it looks to me locally.  As you can see, I'm not picky.  I see some code and some math, so I can test and rest assured that it'll likely be fine when published.

If that wasn't enough, this Jekyll serve thing just auto-updates it whenever I save!  Why didn't I do this earlier, it's fantastic!


## Tests

### Code Test

The first trial: hopefully some C code appears here...
```c
/*
    This is a block comment.
    Fun fact: I usually use tabs to indent but spaces look better here.
*/
#ifndef _FSCALAR_H_
#define _FSCALAR_H_

#ifdef __cplusplus
extern "C" {
#endif // __cplusplus

    typedef struct fscalar
    {
        float value;        // the scalar's value
        float valueSq;      // value squared
        float valueInv;     // value inverse (reciprocal)
        float valueSqInv;   // value squared inverse
    } fscalar;
    
    fscalar fscalarNew(float const value);

#ifdef __cplusplus
}
#endif // __cplusplus

#endif // _FSCALAR_H_
```

### Math Test

The second trial: hopefully these right here, $$ y = x^2 $$ and \\( x = \sqrt{y} \\), are some inline math, and some blocks of math appear here...

$$ y = x^2 $$

\\[ x = \sqrt{y} \\]


### Materials

The third trial: I really just need code and math to make this all work, so if those two tests passed, then we're good to go!


Check back for newer and cooler posts soon.


***D. Buckstein***
