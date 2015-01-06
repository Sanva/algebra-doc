
.. default-role:: math

.. raw:: html
	
	<script type="text/x-mathjax-config">
		MathJax.Ajax.config.path["Contrib"] = "https://cdn.mathjax.org/mathjax/contrib";
		MathJax.Hub.Config({
			TeX: {extensions: ["[Contrib]/xyjax/xypic.js"]}
		});
	</script>

Probando XyJax
==============

.. math::
	
	\xymatrix{A \ar@{}[dr]|{=} \ar[d] \ar[r] & B \ar[d] \\ B \ar[r] & C }
	
	A
	\begin{xy}
	<-3em,0em>;0**@{-},
	0*[F]{ABCDEF}
	\end{xy}
	B
	
	A\xymatrix{
	(f_1)_*x_1 \ar[r]_a \ar[d]_{(f_1)_*b_1} & (f_2)_*x_2 \ar[d]^{(f_2)_*b_2} \\
	(f_1)_*x'_1 \ar[r]^{a'} & (f_2)_*x'_2.
	}B
	
	A\begin{xy}
	\xymatrix{
	R \ar@<1ex>[r] \ar@<-1ex>[r] &
	U \ar[r]^{a} &
	F
	}
	\end{xy}B
	
	\newdir{m}{!/4.5pt/@{|}*:(1,-.2)@^{>}*:(1,.2)@_{>}}
	\begin{xy}
	0*+{A}="a", <5pc, 1pc>*+{B}="b"
	\ar @{=m} "a";"b"
	\end{xy}
	
	\begin{xy}
	\xymatrix {
	U \ar@/_/[ddr]_y \ar@{.>}[dr]|{\langle x,y \rangle} \ar@/^/[drr]^x \\
	 & X \times_Z Y \ar[d]^q \ar[r]_p & X \ar[d]_f \\
	 & Y \ar[r]^g & Z
	}
	\end{xy}
