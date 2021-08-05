# Qwickly

![Qwickly layout](https://github.com/qwickly-org/Qwickly/blob/master/Qwickly.png)

**TL;DR**
- choose **Qwickly** as the easier to learn layout from QWERTY (compared to Colemak or other QW/ZXCV-preserving layouts)
- choose **Qwickly-KZ** for least finger movement (or the matrix version for ortholinear keyboard hardware)
- choose **Qwickly-matrix** for ortholinear keyboard hardware (or Qwickly-KZ-matrix)
- learn the Qwickly layout fast using the [4 QwickStep layouts](https://github.com/qwickly-org/QwickSteps)

Qwickly and the QwickSteps layouts have been designed for typing English prose. Efficiency for arbitrary word lists or other languages is not a goal.

## Installation

#### Mac OS

- Open (double-click) the `Qwickly.dmg` file which will show its contents with two icons.
- Open (double-click) the icon named `Keyboard Installer` which will show a window with two large 'people' icons.
- Drag the `Qwickly.bundle` icon from the first window to the second where it says `Keyboard layout to install: Drag keyboard layout here to install`
- Open (double-click) the large 'person' icon named `Install for current user (recommended)`, the window will close.
- Open the `Keyboard` item in `System Preferences`
- Click the `Input Sources` tab/section
- Press the `+` button on the bottom-left to 'add' a layout
- With the `English` language selected in the left list, select the layout(s) you wish to install. Multi-select holding down shift key while clicking.
- Click the `Add` button, the window will close.
- Select a newly added layout on the left list to use it now.
- Enabling the `[x] Show Input menu in the menu bar` can be useful to show which layout is in effect and easily switch between them.

That's all. Seems like a lot of steps but it's really quite easy to do--though perhaps not very intuitive.

## Qwickly (pinky comma)
![Qwickly (pinky comma) layout](https://github.com/qwickly-org/Qwickly/blob/master/Qwickly-comma.png)

## Qwickly (matrix)
```
Q  W  U  D  P  K  H  Y  L  ;  [  ]  \
A  S  E  T  G  F  N  I  R  O  ' enter
Z  X  J  C  V  B  M  ,  .  /  shift
```

## Qwickly-KZ
![Qwickly-KZ layout](https://github.com/qwickly-org/Qwickly/blob/master/Qwickly-KZ.png)

## Qwickly-KZ (pinky comma)
![Qwickly-KZ layout](https://github.com/qwickly-org/Qwickly/blob/master/Qwickly-KZ-comma.png)

## Qwickly-KZ (matrix)
```
Q  W  U  D  P  Z  H  Y  L  ;  [  ]  \
A  S  E  T  G  F  N  I  R  O  ' enter
K  X  J  C  V  B  M  ,  .  /  shift
```

## Qwickly-NRIO-KZ (aka NRIO-KZ)

This layout is based on Qwickly-KZ with the letters on right middle (YI) and ring fingers (LR) swapped.<br/>
It produces better benchmarks but personal experience over many weeks did not achieve the smoothness of typing on the Qwickly-KZ layout. Your mileage may vary and this layout is included to see if it works better for you. Do not let the benchmarks convince you one way or another, try out each one for long enough to form an opinion for your specific situation. Benchmarks should only guide your choices--ultimately your real-world comfort and speed matters most. For English prose the Qwickly-NRIO and Qwickly-KZ have the top stats so don't get caught up in small/hypothetical differences.

![Qwickly-NRIO layout](https://github.com/qwickly-org/Qwickly/blob/master/Qwickly-NRIO.png)

## Qwickly-NRIO (aka NRIO)

There's also the NRIO layout with Z in QWERTY position.
```
Q  W  U  D  P  K  H  Y  L  ;  [  ]  \
 A  S  E  T  G  F  N  I  R  O  ' enter
  Z  X  C  V  J  B  M  ,  .  /  shift
```

## Benchmarks

*Stats show below as Qwickly-NR are for Qwickly-NRIO-KZ*
*The matrix version scores are not listed as they generally score uncomparably higher.*

<pre><code>
               Colemak-DH Qwickly-NR Qwickly-KZ Colemak   Qwickly    Niro    S.Dvorak

   <b>Alice</b>          69.06      <b>70.31</b>*    69.73     67.31     69.40     67.55     63.59
   Common         <b>76.05</b>*     73.87     71.78     74.50     71.75     72.18     64.48
   S.A.T.         <b>73.04</b>*     70.84     70.23     71.38     70.01     70.07     60.79
   <b>Magna</b>          71.18      <b>72.47</b>*    70.71     69.29     70.61     68.85     63.99
   <b>1984</b>           71.17      <b>71.80</b>*    71.52     69.30     71.60     69.08     65.19
   <b>Tarzan</b>         71.03      <b>72.20</b>*    71.46     69.73     71.36     69.45     64.73
   <b>Jungle</b>         65.76      <b>68.33</b>*    67.40     65.57     67.35     66.44     61.71
   Difficult      <b>68.69</b>*     67.85     66.82     67.30     66.68     65.28     61.31
   Medical        <b>73.43</b>*     70.12     69.80     72.08     70.07     67.34     58.77
   <b>Quotes</b>         51.82      <b>58.45</b>*    58.25     56.54     58.30     57.40     48.43
   <b>Tao</b>            61.88      <b>62.58</b>*    62.26     61.44     62.31     60.34     57.78
   Bigrams        <b>78.30</b>*     77.47     76.67     77.43     76.63     75.39     70.88
   <b>Cost</b>           <b>61.42</b>*     61.07     60.29     60.69     60.22     59.84     52.09
   <b>Contract</b>       <b>60.85</b>*     55.80     54.57     60.17     54.63     54.61     49.24
   <b>Binary</b>         <b>61.63</b>*     60.41     60.00     61.05     60.12     59.05     55.12
   Lorem          58.93      58.73     58.68     57.89     <b>59.77</b>*    59.18     50.96
   Game           44.21      <b>46.03</b>*    45.24     43.99     45.13     44.82     41.64
</code></pre>

**bold name** = prose (English sentences)<br/>
**bold score*** = best score
