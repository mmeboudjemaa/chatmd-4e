# Source : 402_théorème de pythagore_longueurs/402_cours.tex

::: center
**Séquence 2 -- Théorème de Pythagore**\
**Cours**
:::

# Rappel : le carré d'un nombre

Si un carré a pour côté $c$, alors son aire est $c^2$.

# L'hypoténuse

::: tcolorbox
**Propriété :** l'hypoténuse est le **plus long côté** d'un triangle rectangle.
:::

Dans le triangle $ABC$ rectangle en $A$, l'hypoténuse est $[BC]$.

# Du puzzle au théorème

::: minipage
![image](images/puzzle_original_triangle_carrés.png){width="92%" height="4.4cm"}
:::

::: minipage
Le puzzle montre que :

$$\boxed{
\begin{array}{c}
\text{aire du carré sur l'hypoténuse}\\
=\\[-0.2em]
\text{somme des aires des deux autres carrés}
\end{array}
}$$

Dans le triangle $ABC$ rectangle en $A$ :

$$BC^2=AB^2+AC^2.$$
:::

::: center
Si $ABC$ est rectangle en $A$, alors : $$\boxed{BC^2=AB^2+AC^2}$$
:::

**La racine carrée**

Lors de l'activité, nous avons cherché le côté d'un carré d'aire $50\ \text{cm}^2$ :

$$7{,}07\times7{,}07=49{,}9849
\qquad
7{,}08\times7{,}08=50{,}1264.$$

:::::: tcolorbox
::: center
**Carré d'un nombre et racine carrée**
:::

::: minipage
**Du côté vers l'aire**

$$6\times6=36
\qquad
\boxed{6^2=36}$$

$$\boxed{
\text{côté}
\ \xrightarrow{\quad\text{carré}\quad}\
\text{aire}
}$$
:::

::: minipage
**De l'aire vers le côté**

$$\sqrt{36}=6
\qquad
\boxed{\text{côté}=6\text{ cm}}$$

$$\boxed{
\text{aire}
\ \xrightarrow{\quad\text{racine carrée}\quad}\
\text{côté}
}$$
:::
::::::

**Avec la calculatrice**

:::: minipage
::: tcolorbox
**CASIO fx-92+ Spéciale Collège**

$$\sqrt{50} :
\quad
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize SECONDE%
}%
\;
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize \(x^2\)%
}%
\;
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize 50%
}%
\;
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize EXE%
}%$$

$$%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize \(S\leftrightarrow D\)%
}%

\quad\Rightarrow\quad
\boxed{\sqrt{50}\approx7{,}07}$$
:::
::::

:::: minipage
::: tcolorbox
**Nouvelle CASIO fx-92 Collège**

Modèle à touches rondes

$$\sqrt{50} :
\quad
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize \(\sqrt{\phantom{0}}\)%
}%
\;
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize 50%
}%
\;
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize EXE%
}%$$

$$%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize FORMAT%
}%

\rightarrow
%
\fbox{%
  \rule{0pt}{1.15em}%
  \sffamily\bfseries\scriptsize Décimal%
}%

\quad\Rightarrow\quad
\boxed{\sqrt{50}\approx7{,}07}$$
:::
::::

**Arrondir au dixième**

:::: tcolorbox
Pour arrondir au dixième, je garde **un chiffre après la virgule** et je regarde le **chiffre suivant** :

$$\boxed{
\begin{array}{ccl}
0,\ 1,\ 2,\ 3,\ 4 &\longrightarrow& \text{je garde le dixième}\\[0.2em]
5,\ 6,\ 7,\ 8,\ 9 &\longrightarrow& \text{j'ajoute 1 au dixième}
\end{array}
}$$

$$\sqrt{50}\approx7{,}\boxed{0}\underline{7}\ldots
\quad\Longrightarrow\quad
\boxed{\sqrt{50}\approx7{,}1}$$

$$\sqrt{55}\approx7{,}\boxed{4}\underline{1}\ldots
\quad\Longrightarrow\quad
\boxed{\sqrt{55}\approx7{,}4}$$

::: center
Un arrondi n'est pas exact : $$\boxed{\sqrt{50}\approx7{,}1}
\qquad\text{et non}\qquad
\sqrt{50}=7{,}1.$$
:::
::::

**Rédiger avec le théorème de Pythagore**

:::: minipage
::: tcolorbox
**Chercher l'hypoténuse**

$MNP$ est rectangle en $M$, avec $MN=5$ cm et $MP=7$ cm.

Calculer $NP$.

**Rédaction**

Le triangle $MNP$ est rectangle en $M$.

D'après le théorème de Pythagore :

$$NP^2=MN^2+MP^2$$

$$\begin{aligned}
NP^2 &= 5^2+7^2\\
NP^2 &= 25+49\\
NP^2 &= 74
\end{aligned}$$

$$NP=\sqrt{74}$$

$$\boxed{NP\approx8{,}6\text{ cm}}$$
:::
::::

:::: minipage
::: tcolorbox
**Chercher un côté de l'angle droit**

$RST$ est rectangle en $R$, avec $ST=9$ cm et $RS=4$ cm.

Calculer $RT$.

**Rédaction**

Le triangle $RST$ est rectangle en $R$.

D'après le théorème de Pythagore :

$$ST^2=RS^2+RT^2$$

$$\begin{aligned}
9^2 &= 4^2+RT^2\\
81 &= 16+RT^2\\
RT^2 &= 81-16\\
RT^2 &= 65
\end{aligned}$$

$$RT=\sqrt{65}$$

$$\boxed{RT\approx8{,}1\text{ cm}}$$
:::
::::

**Ma checklist Pythagore**

::::: tcolorbox
::: minipage
$\square$ Le triangle est **rectangle**.

$\square$ J'ai repéré l'**hypoténuse**.

$\square$ L'hypoténuse est seule d'un côté de l'égalité.

$\square$ J'écris d'abord l'égalité avec les **lettres**.
:::

::: minipage
$\square$ Je prends la **racine carrée**.

$\square$ Si j'arrondis, j'écris $\approx$.

$\square$ J'écris l'**unité**.

$\square$ Je vérifie : l'hypoténuse est le **plus long côté**.
:::
:::::
