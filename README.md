# void

アデール
- __Z__<sup>^</sup> = prolim _n_  __Z__
- __Q__ = indlim __Z__ / _s_
- __A__ = __Z__<sup>^</sup> &otimes; __R__

- (_∂<sub>t</sub>_ + _H_ ) _ψ_ = 0
- _f _=_ mM _/_ 4&pi;r<sup>2</sup>_
- _f _=_ qQ _/_ 4πr<sup>2</sup>_

# アデール
有理数体　__Q__ = lim __Z__ / _s_

有理整数環の副有限完備化　__Z__&circ; = pro lim _n_  __Z__ = &prod;<sub>_p_</sub> __Z__<sub>_p_</sub>

_p_進体　__Q__<sub>_p_</sub> = __Z__<sub>_p_</sub> &otimes; __Q__

実数体　__R__ = __Q__<sub>∞</sub>

アデール環　__A__<sub>__Q__</sub> = __Z__&circ; &otimes; __Q__ &times; __R__

有限アデールの表現　_n_  _r_ / _s_
ここで _n_ は法，_s_ は分母，_r_ は分子であり，
アデールの有限部分 __Z__&circ; &otimes; __Q__ の元の近似表示とみなす．
0  _r_ / _s_ = _r_ / _s_
_n_  _r_ / 1 = _n_  _r_
と書く．_s_ の逆元が 1/_s_ で _s_ &times; 1/_s_ = 1，_r_ の反元が -_r_ で _r_ + -_r_ = 0，_n_ の法が _n_ 0 で _n_ + _n_ 0 = _n_ 0 となる．

# 非アルキメディアンな場合
_p_進数はリトルエンディアンで表示する．つまり，_p_ を _p_進で表示すると 0.1 となる．
また，非零な _x_ に対して
_x_ = _p_<sup>ord _x_</sup> sgn _x_ exp log _x_
となるようにタイヒミュラー指標 sgn と対数 log を拡張しておく．
もちろん，常識的な定義域の範囲では
sgn _x_ = lim_{n→∞} x^{p^n}
log _x_ = &sum;<sub>n=1</sub><sup>∞</sup> (1 - _x_<sup>-1</sup>)<sup>_n_</sup>/_n_
である．
ord : Gm(__Q__<sub>_p_</sub>) → Ga(__Z__)
sgn : Gm(__Q__<sub>_p_</sub>) → Gm(__Q__<sub>_p_</sub>)
exp : Ga(__Q__<sub>_p_</sub>) → _p_ __Z__<sub>_p_</sub> → 1 + _p_ __Z__<sub>_p_</sub> → Gm(__Q__<sub>_p_</sub>)
log : Gm(__Q__<sub>_p_</sub>) → 1 + _p_ __Z__<sub>_p_</sub> → _p_ __Z__<sub>_p_</sub> → Ga(__Q__<sub>_p_</sub>)

ここで，レトラクション（準同型ではない）Ga(__Q__<sub>_p_</sub>) → _p_ __Z__<sub>_p_</sub>をどう選ぶのが妥当かよくわからないが，
a.b ↦ 0.b つまり，&sum; _c<sub>n</sub>p<sup>n</sup>_ ↦ &sum;<sub>_n_ > 0</sub> _c<sub>n</sub>p<sup>n</sup>_に選んでおく．
_p_ = 2 の場合は，さらに修正が必要なのはそのとおり．
もちろん，常識的なところでは
exp _x_ = &sum;_{n=0}^\∞ x^n/n!
である．

# アルキメディアンな場合
実数や複素数はもちろんビッグエンディアンで表示するが，さらにその続きがある．

τ = 2 &pi; iとする．
0, 1, e, τが複素数体における特別な元となっている．

abs : Gm(__C__) → Gm(__C__)
sgn : Gm(__C__) → Gm(__C__)
exp : Ga(__C__) → τ  Ga(__C__) \stackrel{\sim}{→} Gm(__C__)
log : Gm(__C__) → τ  Ga(__C__) → Ga(__C__)

ここで，セクション（準同型ではない）τ  Ga(__C__) → Ga(__C__)はτ\(τ/2)↦ -τ/2に選んでおく．

τ  Ga(__C__) の元 _x_ を
_x_ = _a.b.c_ = _a.b_ + τ &times; _0.c_
のように書く．また，それがexpで移った先を
x X = exp x
と書く．このように対数表示すれば，乗法・逆元・反元で誤差が発生せず，
e = 1 X
-τ/2 = 0.0.5
i = 0.0.25 X
などとなる．また，ダイナミックレンジの大きな量もコンパクトに表現される．
aがオーダー，bが精度，cが次元を表していると思える．ちなみにlogは
log x = \int_1^x \frac{ds}{s}
と定義されているものとする．

余談ながら，慣用の指数表示は，例えば基数をrとして
x =
(sgn x)exp\left((log r) \left\\{\frac{log \|x\|}{log r}\right\\}\right) &times;
exp\left((log r) \left\lfloor\frac{log \|x\|}{log r}\right\rfloor\right) =
(sgn x) \alpha.\beta &times; 10^\nu
としているわけで，これに比べれば
x = exp log x = a.b.c X
が単純だと思う．例えば，2進表記されたものを2&times; 5進表記に変換する手間を考えてみて欲しい．

# 次元の除去
物理量や情報量を単位抜きで扱いたい．[数について](http://qiita.com/etale/items/26c7d4836e6e836fa525)の対数表示を利用すれば十分実用的だと思われるし，古典物理学や量子力学を具体的な数値として量的に把握することができるような気がする．

4 &pi; G = c = &epsilon;<sub>0</sub> = &mu;<sub>0</sub> = k = h/2 &pi; i = 1とする．

普通は\hbar = h/2&pi; = 1とするが，それでは次元が退化しすぎる感じだし，
pq - qp = h/2&pi; iだけ見ても，h = 2&pi; iとみなしたくなる．

これらの量を慣用の単位系で表して
c = 299792458 m \s^{-1}
h = 6.626070040 &times; 10<sup>-34</sup> kg m<sup>2</sup> s<sup>-1</sup>
G = 6.67408 &times; 10<sup>-11</sup> kg<sup>-1</sup> m<sup>3</sup> s<sup>-2</sup>
とすれば， __C__ で解いて
kg =  18.908488.125 X = exp(17.642958 + 2&pi; i &times; 0.125)
m  =  78.844871.125 X
s  =  98.363472.125 X
となる．ついでに
k = 1.3806488 &times; 10<sup>-23</sup> J K<sup>-1</sup> = 1
&mu;<sub>0</sub> = 4&pi; &times; 10<sup>-7</sup> N A<sup>-2</sup> = 1
とすれば，
K  = -72.765617.125 X
A  = -56.280327  X
となる．また，
b = log 2 = 0.693147 = -0.366513 X
B = log 2<sup>8</sup> = 8 log 2 = 1.712929 X
KiB = 2<sup>10</sup> B = 8.644400 X
miB = 2<sup>20</sup> B = 15.575872 X
GiB = 2<sup>30</sup> B = 22.507344 X
などとなる．

シンプルな構成

分数
剰余
実数
複素数
_p_進整数
_p_進数
アデール

ニュートン
マクスウェル
ボルツマン
プランク

基本的な数のタイプ

__Z__

__Ẑ__

__Z&circ;__ = lim _n_  __Z__

__Q__ = colim __Z__ / _s_

__A__ = __Zˆ__ × __R__

__A<sub>Q</sub>__ = __A__ ⊗ __Q__

加法と乗法との関係

log _x_ = ∑<sub>_k_=1</sub><sup>∞</sup> (1 − 1/_x_)<sup>_k_</sup> / _k_

exp _x_ = ∑<sub>_k_=0</sub><sup>∞</sup> _x_<sup>_k_</sup> / _k_!

複素数の semver 表示

ニュートン

_F_ = _G_ _Mm_ / _r_<sup>2</sup>

_G_ = ν<sub>_G_</sub> m<sup>3</sup> kg<sup>−1</sup> s<sup>−2</sup> = 1

kg = ν<sub>_G_</sub> m<sup>3</sup> s<sup>−2</sup>

N = kg m s<sup>−2</sup> = ν<sub>_G_</sub> m<sup>4</sup> s<sup>−4</sup>

J = N m = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−4</sup>

W = J / s = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−5</sup>

マクスウェル

_c_ = ν<sub>_c_</sub> m s<sup>−1</sup> = 1

s = ν<sub>_c_</sub> m

kg = ν<sub>_G_</sub> ν<sub>_c_</sub><sup>−2</sup> m

N = ν<sub>_G_</sub> m<sup>4</sup> s<sup>−4</sup> = ν<sub>_G_</sub>ν<sub>_c_</sub><sup>−4</sup>

J = N m = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−4</sup>

W = J / s = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−5</sup>


_F_ = _Qq_ / 4π_r_<sup>2</sup>

ボルツマン

_k_ = ν<sub>_k_</sub> J K<sup>−1</sup> = 1

K = ν<sub>_k_</sub> J
