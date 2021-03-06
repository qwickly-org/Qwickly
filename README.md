# Qwickly - "quick to learn, quick to type" Keyboard Layout

Easier to learn than Minimak, faster than Dvorak, and your shortcuts (mostly) stay put.

Read the blog [How Qwickly came to be](https://blog.keithkim.org/opensource/making-the-qwickest-keyboard-layout).

### Installer for all macOS/OS X versions
- Qwickly (includes I and II) [Qwickly.dmg](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly.dmg)

Created using [Ukelele software](https://software.sil.org/ukelele).

### Installers for Windows (64-bit)
- Qwickly [Qwickly_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly_amd64.msi)
- Qwickly (Mod BF) [QwicklyM_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/QwicklyM_amd64.msi)
- Qwickly I [Qwickly1_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly1_amd64.msi)
- Qwickly II [Qwickly2_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly2_amd64.msi)

Created using Microsoft Keyboard Layout Creator v1.4.

### Installers for Linux
- in development (stay tuned)


## Qwickly I

Let's get the 8 most [frequently occurring letters](https://en.wikipedia.org/wiki/Letter_frequency) in home finger positions. `A` and `S` are already there.

Swap frequently occurring letters: `E`, `T`, `N`, `I`, `O`, `P`<br/>
with letters above or below them: `D`, `F`, `J`, `K`, `L`, `;`

*(`R` occurs more than `P` but we'll get it in the next step.)*
```
 Q   W  (D)  R  (F)  Y   U  (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) (P)  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
```
The keys `ASET GH NIOP` uses the same muscle-memory from QWERTY, just not moving fingers off the home row.<br/>
With this layout, you will often miss `DF JKL` but that's okay since the letter you want is just above/below the miss.<br/>
We are mostly learning the home row. Switch to **Qwickly II** as soon as you can handle it.

## Qwickly II

The next frequently occurring letters `D`, `H`, and `L` are already in close positions.

Reduce finger travel for other frequently occurring letters: `R`, `U`<br/>
rotate-swap with letters: `D`, `P` *(We move `D` for `U` because it works out better in the end.)*
```
 Q   W  <U> [D] (F)  Y  [P] (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) <R>  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

Here we're trying to learn the new `U`, `D` and `R` positions.<br/>
`K`/`I` and `L`/`O` bigrams will be awkward as it's same fingers like QWERTY but 'upside-down'.<br/>
Switch to **Qwickly** as soon as you can handle it. You can even try going directly from **Qwickly I** to **Qwickly**.

## Qwickly

`J` is an infrequently occurring letter so it can be farther away.<br/>
`L` is frequently occurring so use a strong finger with the ordering `L`/`P`/`Y` to minimize same-finger [bigrams](https://blogs.sas.com/content/iml/2014/09/26/bigrams.html).<br/>
`K` occurs more than `J` so keep it closer.

As it turns out, it's easier to learn new key positions that are two fingers away than one away.
```
 Q   W  <U> [D] (F) (J) [L] [P] [Y] (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) <R>  '   enter

   Z   X   C   V   B   [K]  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

### WPM per letter on day 6

There's some evidence that reusing muscle-memory for home row keys works.<br/>
Notice which letters are more/less quickly typed than others.

![wpm per letter](https://github.com/qwickly-org/Qwickly/blob/master/wpm-letters-day-6.png)

### WPM progress day 2 to 6

Day 1 started at ~15 wpm after about an hour of practice.

![wpm progress days 2 through 6](https://github.com/qwickly-org/Qwickly/blob/master/wpm-days-2-6.png)

## Qwickly (Mod PF)

For some people (including myself) up and over for the `F` is noticeably farther/slower when moved beside `M` especially on a laptop keyboard. We swap sides with `P`. Also give `Y` and `K` a little shuffle to make smaller hand/finger motions. Although we move quite a few keys here, they're less frequently occurring and in the long run will appreciate the extra comfort and speed.
```
 Q   W  <U> [D] <P> <B> [L] [Y] [K] (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) <R>  '   enter

   Z   X   C   V  <J>  <F>  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

### Benchmarks

Using https://stevep99.github.io/keyboard-layout-analyzer

<pre><code>
              Colemak  Qwickly-PF Qwickly    Niro     S.Dvorak   Asset   Minimak-12

   Alice       66.61     <b>67.40</b>*    67.20     67.28     63.71     64.29     62.45
   Common      <b>73.94</b>*    72.93     73.11     72.84     66.82     66.53     65.58
   S.A.T.      <b>73.11</b>*    71.93     72.66     72.00     64.26     65.52     63.21
   Magna       68.09     <b>68.55</b>*    68.38     68.07     65.08     64.27     62.41
   1984        67.47     <b>68.12</b>*    67.45     67.73     65.25     64.44     62.04
   Tarzan      68.38     <b>68.66</b>*    68.39     68.55     65.43     64.22     62.07
   Jungle      63.98     64.63     <b>64.74</b>*    64.68     61.22     61.24     57.55
   Difficult   67.97     68.44     <b>68.84</b>*    68.61     63.82     61.63     60.34
   Medical     <b>72.76</b>*    71.55     70.34     70.33     61.49     58.50     60.74
   Quotes      54.50     <b>55.13</b>*    53.75     54.35     46.74     51.61     49.92
   Tao         61.61     <b>61.96</b>*    60.22     61.11     58.68     58.37     56.35
   Bigrams     <b>72.68</b>*    72.49     72.20     72.32     68.24     70.18     69.10
   Cost        58.11     57.80     <b>58.93</b>*    57.85     50.78     54.84     52.93
   Contract    <b>57.38</b>*    53.37     54.83     53.38     47.38     52.70     49.73
   Binary      <b>59.05</b>*    57.93     57.80     57.55     54.23     52.70     51.51
   Lorem       57.06     57.39     56.99     <b>57.83</b>*    51.61     54.55     48.29
   Game        38.86     39.76     <b>40.50</b>*    39.67     35.35     36.04     34.56
</code></pre>
**bold*** = best score

Colemak takes 6 wins, Qwickly-PF 6, Qwickly 4 wins and Niro 1 win.<br/>
Qwickly is head-to-head (10 to 7) with Niro.<br/>
Simplified Dvorak is head-to-head with Asset. Minimak-12 is last.

The goal was to make an ergonomic/efficient layout that's easier to learn than any of the existing ones.<br/>
Local key changes also eases relearning shortcuts.

#### Qwickly
![Qwickly keyboard layout](https://github.com/qwickly-org/Qwickly/blob/master/Qwickly.png)

#### Qwickly (Mod PF)
![Qwickly Mod-PF keyboard layout](https://github.com/qwickly-org/Qwickly/blob/master/Qwickly-PF.png)
