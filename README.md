java c
Digital Signal Processing and Digital Filters 
Practice Sheet 1
1)      Which   of the   following   statements   is   true   and   why?   (Multiple   choices   may   be   correct)
i)    All   discrete-time   signals   are   digital   signals.
ii)    All   digital   signals   are   discrete-time   signals.
iii)    Some   discrete-time   signals   are   digital   signals.
iv)    Some   digital   signals   are   discrete-time   signals.
2)    Let   us   define   a   sequence   by,
x[n]   =   (r1)nu   [n] − (r2   )nu   [− (n +   1)]                                                                                                                   (1)
where   r1      =   −1/3   and   r2      =   1/2.
•    On   the   z-plane,   plot   the   poles   and   zeros   together   with   the   region-of-convergence.
•      In   the   above   sequence   in   (1),   what   happens   if we   exchange   r1    and   r2?
3)    For   some   linear-time-invariant   system,   the   transfer   function   is   given   by,

Suppose   x [n]   is   the   input   to   the   system   and   y [n]   is   the   output.
Derive   the   difference   equation   that   is   satisfied   by   x [n]   and   y [n].
4) Filter Specification via Z-transform Suppose   t代 写Digital Signal Processing and Digital Filters Practice Sheet 1C/C++
代做程序编程语言hat   a   function   is   given   by,

•    Is   ϕ (t)   a   symmetric   function?   Argue   by   plotting   this   function.
•    Convert   ϕ (t)   into   an   FIR   filter   by   sampling   it   at   integer   points,   that   is,   ϕ (t) ,   t   =   k   where   k   = 0, ±1, ±2, . . ..
Let   Φ (z)   be   the   z-transform   of   this   FIR   filter   sequence.   Write   the   explicit   form   of   Φ (z).
•      Inverse   filter   design.   Suppose   that   the   FIR   filter   is   defined   by
p [k] =   ϕ (t)|t=k,   k   = Z                        (that   is,   k   takes   integer   values). 
Then,   we   say   that pinv [k]   is   an   inverse-filter   when,
Identify   the   transfer   function   of pinv [k]   in   terms   of   Φ (z).
Write   down   the   impulse-response   of pinv [k]   given   the   definition   of   ϕ (t).   Is pinv [k]   an   FIR   or   IIR   filter?
Plot   the   impulse   response   of pinv [k].
5) Filter Identification 
The   pole-zero   plot   of a   discrete   filter   is   given   below.
When   the   input   x [n] =   1   for   all   n,   the   output   is   exactly   the   same.
What   is   the   impulse   response   of such   a   filter?






         
加QQ：99515681  WX：codinghelp
