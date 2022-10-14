# modifiedBessel
Generating the modified Bessel functions relevant to strong field QED

# The modified Bessel functions
![alt text](modifiedBessel.png)


$$dW_\mathrm{QED} = \frac{\alpha mc^2}{\sqrt{3}\pi\hbar\gamma} \left[ \left(1-\xi+ \frac{1}{1-\xi} \right)K_{2/3}(\delta) - \int_\delta^\infty K_{1/3}(s)ds  \right] d\xi$$
$$dP_\mathrm{QED} = \frac{\hbar\omega}{mc^2} dW_\mathrm{QED}=\frac{\alpha mc^2}{\sqrt{3}\pi\hbar} \left[ \left(1-\xi+ \frac{1}{1-\xi} \right)K_{2/3}(\delta) - \int_\delta^\infty K_{1/3}(s)ds  \right] \xi d\xi$$
$$\delta=\frac{2\xi}{3\chi(1-\xi)};\,\xi=\frac{\hbar\omega}{\gamma mc^2}$$

$$ P_\mathrm{QED} = \frac{\alpha mc^2}{\sqrt{3}\pi\hbar}  \int_0^1 f_e(\xi,\chi)\xi d\xi$$

$$ f_e(\xi,\chi) = \left(1-\xi+ \frac{1}{1-\xi} \right)K_{2/3}(\delta) - \int_\delta^\infty K_{1/3}(s)ds $$

$$ W_\mathrm{QED}\approx 1.46 \frac{\alpha mc^2}{\hbar \gamma}\chi_e^{2/3}\,\,\,\,\text{for}\,\,\,\,\chi>>1$$

![alt text](total_QED.png)

# Classical limit, $\hbar\rightarrow 0$
$$dW_\mathrm{cl} = \frac{\alpha mc^2}{\sqrt{3}\hbar\pi\gamma} \left[   2K_{2/3}(\delta) - \int_\delta^\infty K_{1/3}(s)ds  \right] d\xi $$

$$dP_\mathrm{cl}  = \frac{\hbar\omega}{mc^2} dW_\mathrm{cl}= \frac{\alpha mc^2}{\sqrt{3}\pi\hbar}  \left[   2K_{2/3}(\delta) - \int_\delta^\infty K_{1/3}(s)ds  \right] \xi d\xi$$
$$\delta=\frac{2\xi}{3\chi}$$

$$ P_\mathrm{cl} = \frac{\alpha mc^2}{\sqrt{3}\pi\hbar}  \int_0^\infty f^e_\mathrm{cl}(\xi,\chi)\xi d\xi$$

$$ f^e_\mathrm{cl}(\xi,\chi) = 2K_{2/3}(\delta) - \int_\delta^\infty K_{1/3}(s)ds = \int_\delta^\infty K_{5/3}(s)ds $$

![alt text](total_cl.png)
