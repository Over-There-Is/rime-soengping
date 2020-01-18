# 粤语双拼/KG KU XB TZ

配方：℞ **`Over-There-Is/rime-soengping`**

基于sgal、狸猫、刘邦后代等人粤拼词库嘅粤语双拼输入方案

原项目主页 https://github.com/rime/rime-cantonese

支持香港语言学协会拼音、国际音标、广州话拼音方案显示。

## 编码方案/TA YR UN LF

### 声母/XZ YU

<table>
  <tr>
    <th colspan="10">声母</th>
  </tr>
  <tr align="center">
    <td>Q</td> <td>W</td> <td>E</td> <td>R</td> <td>T</td> <td>Y</td> <td>U</td> <td>I</td> <td>O</td> <td>P</td>
  </tr>
  <tr align="center">
    <td>-</td> <td>-</td> <td>-</td> <td>b</td> <td>p</td> <td>m</td> <td>f</td> <td>w</td> <td>kw</td> <td>gw</td>
  </tr>
  <tr align="center">
    <td>A</td> <td>S</td> <td>D</td> <td>F</td> <td>G</td> <td>H</td> <td>J</td> <td>K</td> <td>L</td> <td>;</td>
  </tr>
  <tr align="center">
    <td>z</td> <td>s</td> <td>c</td> <td>d</td> <td>t</td> <td>n</td> <td>l</td> <td>j</td> <td>0</td> <td>-</td>
  </tr>
  <tr align="center">
    <td>Z</td> <td>X</td> <td>C</td> <td>V</td> <td>B</td> <td>N</td> <td>M</td>
  </tr>
  <tr align="center">
    <td>zh</td> <td>sh</td> <td>ch</td> <td>g</td> <td>k</td> <td>ng</td> <td>h</td>
  </tr>
</table>

gu gui gun(t) kui音节使用gw kw按键。

gou geoi gon(t) keoi音节使用g k按键。

喺冇开合口对立嘅韵母前边两组按键互通。

为人为构造互补韵母音位，本方案强行拆分z c s与zh ch sh声母，同分韵撮要时期或者赵元任《粤语入门》时期粤语的平翘舌无关，类似广州拼音嘅j q x。

zyu cyu syu si soe音节使用zh ch sh按键。

zou cou sou sei se音节使用z c s按键。

其他韵母前边两组按键互通。

### 韵母/IS YU

<table>
  <tr>
    <th colspan="10">韵母</th>
  </tr>
  <tr align="center">
    <td>Q</td> <td>W</td> <td>E</td> <td>R</td> <td>T</td> <td>Y</td> <td>U</td> <td>I</td> <td>O</td> <td>P</td>
  </tr>
  <tr align="center">
    <td>im (em)</font></td> <td>am</td> <td>aam</td> <td>aa</td> <td>e oe</td>
    <td>o</td> <td>u ou yu</td> <td>aau</td> <td>au</td> <td>iu (eu)</td>
  </tr>
  <tr align="center">
    <td>A</td> <td>S</td> <td>D</td> <td>F</td> <td>G</td> <td>H</td> <td>J</td> <td>K</td> <td>L</td> <td>;</td>
  </tr>
  <tr align="center">
    <td>in (en)</td> <td>an</td> <td>aan</td> <td>on un eon</td> <td>yun (oen)</td>
    <td>oi</td> <td>ui eoi</td> <td>aai</td> <td>ai</td> <td>i ei</td>
  </tr>
  <tr align="center">
    <td>Z</td> <td>X</td> <td>C</td> <td>V</td> <td>B</td> <td>N</td> <td>M</td>
  </tr>
  <tr align="center">
    <td>ing</td> <td>ang</td> <td>aang</td> <td>eng</td> <td>oeng</td> <td>ong</td> <td>ung</td>
  </tr>
</table>

入声韵并入相应嘅阳声韵，括号入边嘅韵母可以喺韵码后边补充个分号来精确选字。

除咗e/oe同带括号嘅口语韵母之外，其余嘅同键位嘅韵母基本互补。

除咗粤拼z c s j声母之外，其他声母后边呢两韵辖字都极少，并且z c j唔能够搭配oe。

音节m ng hm hng当作mim nging mip ngik处理。

### 声调/XZ FP

<table>
  <tr>
    <th colspan="3">声调</th>
  </tr>
  <tr align="center">
    <td>QQ</td> <td>QW</td> <td>QE</td>
  </tr>
    <tr align="center">
    <td>阴平(1)</td> <td>阴上(2)</td> <td>阴去(3)</td>
  </tr>
  <tr align="center">
    <td>WQ</td> <td>WW</td> <td>WE</td>
  </tr>
  <tr align="center">
    <td>阳平(4)</td> <td>阳上(5)</td> <td>阳去(6)</td>
  </tr>
  <tr align="center">
    <td>EQ</td> <td>EW</td> <td>EE</td>
  </tr>
  <tr align="center">
    <td>上阴入(1) 变调入(2)</td> <td>下阴入(3)</td> <td>阳入(6)</td>
  </tr>
</table>

声调用于辅助选字，可省略。

## 音标显示/KW RP MA X;

方案内`soengping_ipa.schema.yaml`为音标显示版。

音标显示区分舌叶音和舌尖音。预设为喺iː、yː、ɵy̯、œː、ɔː前边显示为舌叶音，其他韵母前边显示为舌尖音，可根据个人喜好进行调节。

按本人习惯将ei ou同ing(k) ung(k)韵腹合并为e o。

由于字体原因，两个相同调值嘅音调符号无法连接，所以平调净使用单个嘅音调符号。

## 广州拼音/PN AO TZ KW

方案内`soengping_guongzeo.schema.yaml`为广州拼音显示版。

广州拼音入边所缺嘅粤拼韵母eu em(p) en(t) oen(t)显示为éo ém(b) én(d) ön(d)。

## 反查/UD DR

Q键使用粤拼反查。W键使用普通话（朙月拼音）反查。E键使用仓颉五代反查。

## 安装/KF AN

本方案依赖于

  - [粵語拼音方案](https://github.com/rime/rime-cantonese) ℞ **`cantonese`**

[东风破](https://github.com/rime/plum)安装口令：`bash rime-install Over-There-Is/rime-soengping`

建议喺词库入边对`- jyut6ping3.lettered`一行进行注释屏蔽。

trime目录下有配套嘅trime键盘。
