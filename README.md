java c
Digital   Signal   Processing   and   Digital   Filters
Practice   Sheet   6
1)      Let   A (ejω) =   1 + e−jω   a   and   B   (ejω) = b.   We   try   to   approximate   a   filter   given   by
The   weight   function   is   W   (ω)   =   1,   ∀ω   ∈   [0,   π].   We   choose   ω   ∈   {0, 4/π,   π}.
(a)    Derive   the   numerical   expressions   of   U   ,   V   and   d   such   that
(b)    Compute   the   real   values   a,b   that   minimize   ∑k|EE(ωk)|2.
2)      In   Optimal IIR filter   design, we   aim to   approximate   a   target   filter   D   (ω)   by   adjusting   the   parameters of a filter   H .   Typically,   the   estimation is   performed   by   minimising   one   of the   two   following   equations

(a)    Given   that   both   equations   involve   nonlinear   operations   due   to   weighting   functions   WS   (ω) , WE   (ω),   explain   what   is   the   challenge   in   optimising   ES   (ω).
(b)    The   optimisation   is   performed   at   frequency   samples      Explain   why 代 写Digital Signal Processing and Digital Filters Practice Sheet 6R
代做程序编程语言  we   can   estimate   the   filter   when   K   is   only   half   of   the   number   of   unknowns,   which   is   K   = 2/M+N+1.
(c)    Explain   what   happens   if K   is   very   large,   e.g.   K   =   100 ·   2/M+N+1.   Select   one   from   the   options   below,   and   explain   the   choice.   
i.    The   estimation   would   fail.
ii.    The   algorithm   would   estimate   D (ω)   with   a   very   high   degree   of accuracy
iii.    The   algorithm   works,   but   the   accuracy   is   limited.      Explain what happens ifK   < 2/M+N+1. Select one from the options below, and explain
the   choice.
i.      The   algorithm   returns   an   error.
ii.      The   algorithm   returns   multiple   solutions.
iii.    The   algorithm   returns   one   correct   solution.
(e)    Let   WE   (ω)   = cos2(p (ω   −   ω0)).   Find   p,   ω0    such   that   EE(k 20/π)   = 0, k   =   1, . . . , 20,   for any   H   (ejω) and   D (ω).









         
加QQ：99515681  WX：codinghelp
