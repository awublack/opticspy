
#opticspy  

Opticspy is a python module for optics application. I want to this for a long time. One reason is I know both optics and python, so why no develop some optics tools? The second reason is that there is not much opensource, easy-to-use optics program module(matlab has great fuctions but do not specify to optics application). I want this could be developed in to a core for a future web application for optics.

###There are some examples opticspy module:   
   
####1. [Aperture Methods](http://sterncat.github.io/files/Aperture_Method.html)    
  
####2. [Interferometer Methods](http://sterncat.github.io/files/Interferometer_Method.html)  
  
####3. [Zernike Methods](http://sterncat.github.io/files/Zernike_Method.html)    
  
####This is the [Opticspy project page](http://sterncat.github.io/opticspy/)

####This project is hosted on github in [https://github.com/Sterncat/opticspy](https://github.com/Sterncat/opticspy)

##How to use
```
>>> import opticspy
```

And just have fun with it!

## What I want
<ul>	
  <li>1. After import the module and you will get some functions that can do some calculation and education in optics</li>
  <li>2. Parameters should be very flexible, and the results should be shown in visualized, intuitionistic figures.</li>
  <li>3. After development of core, I want it be dynamic web application(with Javascript)</li>
  <li>4. I even hope one day it will become a part of online optics design application, who knows?</li>
</ul>


## What I want to contain in the module
I think the module should contain bunch of things in optics.
<ul>
  <li>1. Diffraction: generate diffraction pattern</li>
  <li>2. Geometric matrix calculation</li>
  <li>3. PSF, OTF and MTF calculation</li>
  <li>4. Several interferogram(Twyman Green, Shearing, etc)</li>
  <li>5. Ray tracing</li>
  <li>6. Zernike coefficients, surface and surface fitting</li>
  <li>7. Third and high order aberration calculation</li>
</ul>

## What I have done

<ul>
  <li>1. Rectangular, circle diffraction pattern, OTF</li>
  <li>2. Third order ray aberration plot</li>
  <li>3. Twyman_Green interferogram with aberration</li>
  <li>4. Lateral Shear interferogram with aberration</li>
  <li>5. Zernike Coefficient calculation</li>
  <li>6. Zernike Polynomials surface(3D), map(2D), cutoff of 3D(1D)</li>
</ul>

##Authors and Contributors
I am Xing Fan. An optics master student now studying in the [Institute of Optics](http://www.optics.rochester.edu/), [University of Rochester](http://www.rochester.edu/). 

And this is my personal blog [Marvin's Neverland!](http://sterncat.github.io)

##Support or Contact
If you have questions and advice, or want to participate in this project, contact me at marvin.fanxing@gmail.com. I would be very happy to find some one have the same interest!



###MIT License
-----------

Copyright (c) 2014-2015 Xing fan (https://github.com/Sterncat/opticspy)
Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
		
