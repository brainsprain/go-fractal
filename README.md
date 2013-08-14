go-fractal
==========

[![Build Status](https://travis-ci.org/brainsprain/go-fractal.png)](https://travis-ci.org/brainsprain/go-fractal)

Playing around with go.

Use a REST service to pass in parameters used to render a fractal.

- [x] render fractal as an image based on parameters
- [ ] use standard parameters
- [ ] pluggable color model for image
- [ ] pluggable algo
- [ ] rendering as idiomatic go library
- [ ] render fractal in parallel
- [ ] distributed rendering using clustering library or zeromq custom
- [ ] other performance enhancements
- [ ] progressive jpeg, not sure if go supports for rendering
- [ ] as web service


Fractals
- [Mandelbrot Atlas](http://www.miqel.com/fractals_math_patterns/mandelbrot_fractal_guide.html)
- [Mandelbrot Algorithms](http://www.mrob.com/pub/muency/algorithms.html)
- [Fractal programs](https://www.fractalus.com/fractal-art-faq/faq06.html)

REST libs
- [Ripple REST framework for Go](https://github.com/laurent22/ripple)
- [Revel web framework for Go](http://robfig.github.io/revel/)

```bash
GET /mandelbrot/real/imaginary/zoom
```

- size (fractal or image)
- dwell_limit
	- The "Dwell Limit" is the setting in a Mandelbrot program that controls the maximum number of iterations to use when generating an image.  It is also known by the names "Maximum Dwell", "Maximum Iterations", "Iteration Limit", and N-Max (or N_max or NMAX).
- algorithm
- color map