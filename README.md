# microstrip-patch-antenna
Design and simulation of a Microstripline Rectangular Patch Antenna using CST Studio Suite
> **Note:** The patch and feedline dimensions mentioned here are based on standard design equations for a 2.4 GHz antenna.
> The actual dimensions used in the CST simulation may slightly differ, as fine-tuning was done during the design process.
Basic Design Equations

For a rectangular microstrip patch antenna:

Resonant Frequency (f₀):

𝑓
0
=
𝑐
2
𝐿
𝜖
𝑒
𝑓
𝑓
f
0
	​

=
2L
ϵ
eff
	​

	​

c
	​


Effective Dielectric Constant (ε_eff):

𝜖
𝑒
𝑓
𝑓
=
𝜖
𝑟
+
1
2
+
𝜖
𝑟
−
1
2
(
1
1
+
12
ℎ
/
𝑊
)
ϵ
eff
	​

=
2
ϵ
r
	​

+1
	​

+
2
ϵ
r
	​

−1
	​

(
1+12h/W
	​

1
	​

)

Patch Width (W):

𝑊
=
𝑐
2
𝑓
0
2
𝜖
𝑟
+
1
W=
2f
0
	​

c
	​

ϵ
r
	​

+1
2
	​

	​


Patch Length (L):

𝐿
=
𝑐
2
𝑓
0
𝜖
𝑒
𝑓
𝑓
−
2
Δ
𝐿
L=
2f
0
	​

ϵ
eff
	​

	​

c
	​

−2ΔL

Length Extension (ΔL):

Δ
𝐿
=
0.412
ℎ
(
𝜖
𝑒
𝑓
𝑓
+
0.3
)
(
𝑊
/
ℎ
+
0.264
)
(
𝜖
𝑒
𝑓
𝑓
−
0.258
)
(
𝑊
/
ℎ
+
0.8
)
ΔL=0.412h
(ϵ
eff
	​

−0.258)(W/h+0.8)
(ϵ
eff
	​

+0.3)(W/h+0.264)
	​


👉 Here:

c = speed of light (3×10⁸ m/s)

εr = dielectric constant (FR-4: ~4.4, Rogers 5880: ~2.2)

h = substrate thickness (1.6 mm typical for FR-4)
