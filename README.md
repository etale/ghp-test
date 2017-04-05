# アデール

__Z__ は有理整数環，lim は射影極限，colim は帰納極限とする．

- __Z__<sup>^</sup> = lim _n_ \ __Z__
- __Q__ = colim __Z__ / _s_
- __A__ = __Z__<sup>^</sup> &otimes; __R__

- (_∂<sub>t</sub>_ + _H_ ) _ψ_ = 0
- _f_ = _mM_ / _4&pi;r<sup>2</sup>_
- _f_ = _qQ_ / _4πr<sup>2</sup>_

- 有理数体
  - __Q__ = lim __Z__ / _s_

- 有理整数環の副有限完備化
  - __Z__ &circ; = lim _n_ \ __Z__ = &prod;<sub>_p_</sub> __Z__<sub>_p_</sub>

- _p_ 進体
  - __Q__<sub>_p_</sub> = __Z__<sub>_p_</sub> &otimes; __Q__

- 実数体
  - __R__ = __Q__<sub>∞</sub>

- アデール環
  - __A<sub>Q</sub>__ = __Z__&circ; &otimes; __Q__ &times; __R__

- 有限アデールの表現
  - _n_ \ _r_ / _s_

ここで _n_ は法，_s_ は分母，_r_ は分子であり，
アデールの有限部分 __Z__&circ; &otimes; __Q__ の元の近似表示とみなす．
- 0 \ _r_ / _s_ = _r_ / _s_
- _n_ \ _r_ / 1 = _n_ \ _r_
と書く．
- _s_ の逆元が 1/_s_ で _s_ &times; 1/_s_ = 1，
- _r_ の反元が -_r_ で _r_ + -_r_ = 0，
- _n_ の法が _n_ \ 0 で _n_ + _n_ \ 0 = _n_ \ 0
となる．

# 非アルキメディアンな場合
_p_ 進数はリトルエンディアンで表示する．つまり，_p_ を _p_ 進で表示すると 0.1 となる．
また，非零な _x_ に対して
- _x_ = _p_<sup>ord _x_</sup> sgn _x_ exp log _x_
となるようにタイヒミュラー指標 sgn と対数 log を拡張しておく．
もちろん，常識的な定義域の範囲では
- sgn _x_ = lim<sub>_n_ → ∞</sub> _x<sup>p<sup>n</sup></sup>_
- log _x_ = &sum;<sub>_n_ = 1</sub><sup>∞</sup> (1 - _x_<sup>-1</sup>)<sup>_n_</sup>/_n_
である．
- ord : Gm(__Q__<sub>_p_</sub>) → Ga(__Z__)
- sgn : Gm(__Q__<sub>_p_</sub>) → Gm(__Q__<sub>_p_</sub>)
- exp : Ga(__Q__<sub>_p_</sub>) → _p_ __Z__<sub>_p_</sub> → 1 + _p_ __Z__<sub>_p_</sub> → Gm(__Q__<sub>_p_</sub>)
- log : Gm(__Q__<sub>_p_</sub>) → 1 + _p_ __Z__<sub>_p_</sub> → _p_ __Z__<sub>_p_</sub> → Ga(__Q__<sub>_p_</sub>)

ここで，レトラクション（準同型ではない）
- Ga(__Q__<sub>_p_</sub>) → _p_ __Z__<sub>_p_</sub>
をどう選ぶのが妥当かよくわからないが，
a.b ↦ 0.b つまり，
- &sum; _c<sub>n</sub>p<sup>n</sup>_ ↦ &sum;<sub>_n_ > 0</sub> _c<sub>n</sub>p<sup>n</sup>_
に選んでおく．
_p_ = 2 の場合は，さらに修正が必要なのはそのとおり．
もちろん，常識的なところでは
- exp _x_ = &sum;<sub>n=0</sub><sup>∞</sup> _x<sup>n</sup>_ / _n_!
である．

# アルキメディアンな場合
実数や複素数はもちろんビッグエンディアンで表示するが，さらにその続きがある．

τ = 2 &pi; iとする．
0, 1, e, τが複素数体における特別な元となっている．

- abs : Gm(__C__) → Gm(__C__)
- sgn : Gm(__C__) → Gm(__C__)
- exp : Ga(__C__) → τ  Ga(__C__) \stackrel{\sim}{→} Gm(__C__)
- log : Gm(__C__) → τ  Ga(__C__) → Ga(__C__)

ここで，セクション（準同型ではない）
- τ \ Ga(__C__) → Ga(__C__)
は
- τ\(τ/2) ↦ -τ/2
に選んでおく．

τ \ Ga(__C__) の元 _x_ を
_x_ = _a.b.c_ = _a.b_ + τ &times; _0.c_
のように書く．また，それがexpで移った先を
_x_ X = exp _x_
と書く．このように対数表示すれば，乗法・逆元・反元で誤差が発生せず，
- _e_ = 1 X
- -τ/2 = 0.0.5
- _i_ = 0.0.25 X
などとなる．また，ダイナミックレンジの大きな量もコンパクトに表現される．
aがオーダー，bが精度，cが次元を表していると思える．ちなみにlogは
- log _x_ = &int;<sub>1</sub><sup>_x_</sup> _ds_ / _s_
と定義されているものとする．

# 次元の除去

- _4&pi;G_ = _c_ = _&epsilon;_<sub>0</sub> = _&mu;_<sub>0</sub> = _k_ = _h_ / _2&pi;i_ = 1
とする．

普通は _h_ = _2&pi;_ とするが，それでは次元が退化しすぎる感じだし，
_pq_ - _qp_ = _h_ / _2&pi;i_ だけ見ても，_h_ = _2&pi;i_ とみなしたくなる．

これらの量を慣用の単位系で表して
- _c_ = 299792458 m \s^{-1}
- _h_ = 6.626070040 &times; 10<sup>-34</sup> kg m<sup>2</sup> s<sup>-1</sup>
- _G_ = 6.67408 &times; 10<sup>-11</sup> kg<sup>-1</sup> m<sup>3</sup> s<sup>-2</sup>
とすれば， __C__ で解いて
- kg =  18.908488.125 X = exp(17.642958 + 2&pi; i &times; 0.125)
- m  =  78.844871.125 X
- s  =  98.363472.125 X
となる．ついでに
- _k_ = 1.3806488 &times; 10<sup>-23</sup> J K<sup>-1</sup> = 1
- &mu;<sub>0</sub> = 4&pi; &times; 10<sup>-7</sup> N A<sup>-2</sup> = 1
とすれば，
- K  = -72.765617.125 X
- A  = -56.280327  X
となる．また，
- b = log 2 = 0.693147 = -0.366513 X
- B = log 2<sup>8</sup> = 8 log 2 = 1.712929 X
- KiB = 2<sup>10</sup> B = 8.644400 X
- MiB = 2<sup>20</sup> B = 15.575872 X
- GiB = 2<sup>30</sup> B = 22.507344 X
などとなる．

シンプルな構成

分数
剰余
実数
複素数
_p_ 進整数
_p_ 進数
アデール

ニュートン
マクスウェル
ボルツマン
プランク

基本的な数のタイプ

- __Z__
- __Z&circ;__ = lim _n_ \ __Z__
- __Q__ = colim __Z__ / _s_
- __A__ = __Zˆ__ × __R__
- __A<sub>Q</sub>__ = __A__ ⊗ __Q__

加法と乗法との関係

- log _x_ = ∑<sub>_k_=1</sub><sup>∞</sup> (1 − 1/_x_)<sup>_k_</sup> / _k_
- exp _x_ = ∑<sub>_k_=0</sub><sup>∞</sup> _x_<sup>_k_</sup> / _k_!

- 複素数の semver 表示

ニュートン

- _F_ = _G_ _Mm_ / _r_<sup>2</sup>
- _G_ = ν<sub>_G_</sub> m<sup>3</sup> kg<sup>−1</sup> s<sup>−2</sup> = 1
- kg = ν<sub>_G_</sub> m<sup>3</sup> s<sup>−2</sup>
- N = kg m s<sup>−2</sup> = ν<sub>_G_</sub> m<sup>4</sup> s<sup>−4</sup>
- J = N m = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−4</sup>
- W = J / s = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−5</sup>

マクスウェル

- _c_ = ν<sub>_c_</sub> m s<sup>−1</sup> = 1
- s = ν<sub>_c_</sub> m
- kg = ν<sub>_G_</sub> ν<sub>_c_</sub><sup>−2</sup> m
- N = ν<sub>_G_</sub> m<sup>4</sup> s<sup>−4</sup> = ν<sub>_G_</sub>ν<sub>_c_</sub><sup>−4</sup>
- J = N m = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−4</sup>
- W = J / s = ν<sub>_G_</sub> m<sup>5</sup> s<sup>−5</sup>
- _F_ = _Qq_ / 4π_r_<sup>2</sup>

ボルツマン

- _k_ = ν<sub>_k_</sub> J K<sup>−1</sup> = 1
- K = ν<sub>_k_</sub> J
