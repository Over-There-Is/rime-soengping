# 粤语双拼/KG KU XB TZ

## 简介/VD VK

基于sgal、狸猫、刘邦后代等人粤拼词库的粤语双拼输入方案

原项目主页 https://github.com/rime/rime-cantonese

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

无开合口对立的韵母之前两组按键互通。

为人为构造互补韵母音位，本方案强行拆分z c s与zh ch sh声母，与分韵撮要时期粤语的平翘舌无关。

zyu cyu syu si soe音节使用zh ch sh按键。

zou cou sou sei se音节使用z c s按键。

其他韵母前两组按键互通。

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

入声韵同阳声韵，括号内韵母可在韵码后补充一分号进行精确选字。

除e/oe及带括号口语韵母外，其余同键位韵母基本互补。

除粤拼z c s j声母以外，其他声母后两韵辖字均极少，并z c j不搭配oe。

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

音标显示区分舌叶音和舌尖音。预设为iː、yː、ɵy̯、œː、ɔː前显示为舌叶音，其他韵母前显示为舌尖音，可根据个人喜好进行调节。

按本人习惯将ei ou和ing(k) ung(k)韵腹合并为e o。

由于字体原因，两个相同调值的音调符号无法连接，故平调只使用一个音调符号。

## 安装/KF AN

本方案依賴於

  - [粵語拼音方案](https://github.com/rime/rime-cantonese ℞ **`cantonese`**

[东风破](https://github.com/rime/plum)安装口令：`bash rime-install Over-There-Is/Rime-Soengping`
