.. -*- coding: utf-8 -*-

Najważniejsze struktury algebraiczne
------------------------------------

Definicje i przykłady
~~~~~~~~~~~~~~~~~~~~~

**Struktura algebraiczna** składa się z jednego albo kilku zbiorów oraz działań określonych na tych zbiorach. 
Definicja konkretnej struktury wymienia te zbiory i podaje postulaty, które powinny spełniać działania.

Najważniejsze struktury to: :math:`\ ` grupa, :math:`\ ` pierścień, :math:`\ ` ciało, :math:`\ ` przestrzeń wektorowa,  :math:`\ ` algebra.

| **Grupa** :math:`\,` składa się z jednego zbioru :math:`\,G\ ` i :math:`\ ` jednego
  działania :math:`\:\perp\;:\ \ \mathbb{G}\;=\;(G,\,\perp).`
|
| Działanie grupowe :math:`\,\perp\,` spełnia następujące warunki:

1. jest łączne:
   
   .. math::
   
      (g_1\perp g_2)\perp g_3\ =\ g_1\perp (g_2\perp g_3)\qquad 
      \text{dla dowolnych}\quad g_1,g_2,g_3\in G\,;

2. istnieje element neutralny :math:`\ e\in G\ \,` taki, że
   
   .. math::
      
      e\perp g\ =\ g \perp e\ =\ g \qquad\text{dla każdego}\quad\ g\in G\,;

3. każdy element :math:`\ g\in G\ ` ma swoją odwrotność :math:`\ g^{-1}\in\,G\ ` taką, że

   .. math::
      
      g\perp g^{-1}\ =\ g^{-1}\perp g\ =\ e\,.

Jeżeli ponadto działanie :math:`\ \perp\ ` jest przemienne:

.. math::
   
   g_1\perp g_2 \ =\ g_2\perp g_1\quad\text{dla dowolnych}\quad g_1, g_2\,\in\,G\,, 

to grupę nazywamy przemienną.

Przykłady grup przemiennych:

* grupa addytywna liczb całkowitych :math:`\ (Z,\,+)\,;\ \ ` 
* grupa multiplikatywna liczb rzeczywistych różnych od zera :math:`\ (R\smallsetminus\{0\}\,,\;\cdot\ )\,;`
* grupa wektorów geometrycznych na płaszczyźnie albo w przestrzeni :math:`\ (V,\,+)\,;`

Przykłady grup nieprzemiennych:

* grupa permutacji zbioru :math:`\,n`-elementowego :math:`\,(\Pi(n),\,\circ\,)\,;`

* | grupa nieosobliwych rzeczywistych macierzy kwadratowych stopnia :math:`\,n\,` 
  | (z mnożeniem macierzowym jako działaniem grupowym);  

* | grupa przekształceń symetrii figury na płaszczyźnie albo bryły w przestrzeni
  | (działaniem grupowym jest składanie przekształceń symetrii). 

| **Pierścień** (ang.: ring) składa się z jednego zbioru :math:`\,P\ \,` i :math:`\ ` dwóch działań:
| "dodawania" :math:`\,+\ \,` oraz :math:`\ ` "mnożenia" :math:`\ \cdot\ :\ \ \mathbb{P}\;=\;(P,\,+\,,\,\cdot\,)\,.`
|
| Działania w pierścieniu spełniają następujące warunki:

1. struktura :math:`\ (P,\,+)\ \ ` jest grupą przemienną;

2. mnożenie jest działaniem łącznym:
 
   .. math::
      
      (a_1\cdot a_2)\cdot a_3 \ =\ a_1\cdot (a_2\cdot a_3)\qquad 
      \text{dla dowolnych}\quad a_1,\,a_2,\,a_3\,\in\,P\,;

3. mnożenie jest rozdzielne względem dodawania:
 
   .. math::
      
      a\cdot(b_1+b_2)\ =\ (a\cdot b_1)\ +\ (a\cdot b_2)\qquad
      \text{dla dowolnych}\quad a,\,b_1,\,b_2\,\in\, P\,,

      (a_1+a_2)\cdot b\ =\ (a_1\cdot b)\ +\ (a_2\cdot b)\qquad
      \text{dla dowolnych}\quad a_1,\,a_2,\,b\,\in\, P\,.

Jeżeli dodatkowo mnożenie jest przemienne:

.. math::
   
   a_1\cdot a_2 \ =\ a_2\cdot a_1\qquad\text{dla dowolnych}\quad a_1,\,a_2\,\in\,P,

to pierścień nazywamy przemiennym.

Jeśli natomiast istnieje element neutralny ze względu na mnożenie
(nazywamy go jednością pierścienia i oznaczamy 1), a więc taki, że

.. math::
   
   1\cdot a\ =\ a\cdot 1\ =\ a\qquad\text{dla każdego}\quad a\in P\,,

to mówimy o pierścieniu z jednością.

| Przykłady przemiennych pierścieni z jednością:

* | pierścień liczb całkowitych: :math:`\ \ \mathbb{Z} \,=\, (Z,\ +\,,\ \cdot\,)`
  | ze zwykłym dodawaniem i mnożeniem liczb;

* | pierścień reszt modulo :math:`\,n:\ \ \mathbb{Z}_n = (Z_n,\ +_n\,,\ \cdot_n\,)\,,\ ` 
    gdzie :math:`\ Z_n\,=\,\{0,1,\ldots,n-1\}\,,\ `
  | a działania :math:`\ \,+_n\ \ \,\text{i}\ \ \,\cdot_n\ ` są dodawaniem  i  mnożeniem modulo :math:`\,n,\ \ n=2,3,\ldots`

* | struktura :math:`\,(X,\ \oplus,\ \odot\,)\,,\ ` gdzie :math:`\,X\,=\,Z,\,Q\ \ \text{albo}\ \,R,\ `
    a działania są określone
  | następująco: :math:`\quad a\oplus b\,:\,=\,a+b+1,\quad a\odot b\,:\,=\,a+b+ab,\quad a,b\in X\,;`
  | zerem tego pierścienia jest liczba -1, a jednością :math:`\ -\ ` liczba 0;

* | zbiór wszystkich funkcji odwzorowujących przedział :math:`\ [\,0,\,1\,]\ \ \text{w}\ \ R`
  | tworzy pierścień razem z działaniami dodawania i mnożenia funkcji;
  | zerem jest funkcja :math:`\ \,\theta(x)=0,\ \,` 
    a jednością funkcja :math:`\ e(x)=1,\ \ x\in [\,0,\,1\,]\,.`

| Nieprzemienny pierścień z jednością tworzą macierze kwadratowe stopnia :math:`\,n\,`
| ze względu na dodawanie i mnożenie macierzowe.


| **Ciało** (ang.: field) składa się z jednego zbioru :math:`\,K\ ` i :math:`\ ` dwóch działań:
| :math:`\ ` "dodawania" :math:`\,+\ \,` oraz :math:`\ ` "mnożenia" :math:`\ \cdot\ :\ \ \mathbb{K}\;=\;(K,\,+\,,\,\cdot\,)\,.`

Działania w ciele spełniają następujące warunki:

1. :math:`(K,\,+)\ \ ` jest grupą przemienną z elementem neutralnym :math:`\,` 0 :math:`\,` (zero ciała);

2. :math:`(K\smallsetminus\{0\},\ \cdot\;)\ \ ` jest grupą przemienną z elementem neutralnym :math:`\,` 1 :math:`\,` (jedność ciała);

3. mnożenie jest rozdzielne względem dodawania:
   
   .. math::
      
      \alpha\cdot(\beta_1+\beta_2)\ =\ (\alpha\cdot \beta_1)\ +\ (\alpha\cdot \beta_2)\quad
      \text{dla dowolnych}\quad\alpha,\,\beta_1,\,\beta_2\,\in\, K\,.

Grupę :math:`\,(K,\,+)\,` nazywamy *grupą addytywną ciała*.

| Łatwo zauważyć, że każde ciało jest pierścieniem.
| Dokładnie: :math:`\,` ciało jest pierścieniem przemiennym z jednością, 
  w którym dla każdego elementu niezerowego istnieje odwrotność.

| Przykłady:

* ciało liczb wymiernych: :math:`\ \mathbb{Q}\,=\,(Q,\,+\,,\;\cdot\;)\;;\ ` 

* ciało liczb rzeczywistych: :math:`\ \mathbb{R}\,=\,(R,\,+\,,\;\cdot\;)\;;\ `

* ciało liczb zespolonych: :math:`\ \mathbb{C}\,=\,(C,\,+\,,\;\cdot\;)\,;`

* | zbiór liczb :math:`\,Q(\sqrt{2})\,:\,=\,\{\,a+b\sqrt{2}\,:\ a,b\in Q\,\}`
  | tworzy ciało ze zwykłym dodawaniem i mnożeniem liczb rzeczywistych;

* | struktura :math:`\,(X,\ \oplus,\ \odot\,)\,,\ ` gdzie :math:`\,X\,=\,Q\ \ \text{albo}\ \,R,\ `
    a działania są określone następująco:
  | :math:`\ a\oplus b\,:\,=\,a+b+1,\quad a\odot b\,:\,=\,a+b+ab,\quad a,b\in X\,,\ \,` jest ciałem
  | (zerem ciała jest tutaj liczba -1, a jednością :math:`\ -\ ` liczba 0);

* | pierścień :math:`\ \mathbb{Z}_n\ ` reszt modulo :math:`\,n\ ` jest ciałem (skończonym)
  | wtedy i tylko wtedy, gdy :math:`\ n\ ` jest liczbą pierwszą.

| **Uwaga:**
| Często grupą (pierścieniem, ciałem) nazywa się sam zbiór :math:`\ G\ (P,\ K),\ ` 
| o ile są w nim określone działania spełniające odpowiednie postulaty.
|
|
|
|

**Przestrzeń wektorowa nad ciałem** :math:`\,K\ ` jest strukturą 
:math:`\ \ \mathbb{V}\,=\,(\,V,\,\oplus\,;\ \,K,\,+\,,\,\cdot\ \,;\ \;\boxdot\,)\,,\ `
w której są spełnione następujące warunki:

1. :math:`\ (V,\,\oplus\,)\ \ ` jest grupą przemienną (jest to *grupa addytywna przestrzeni*);

2. :math:`\ (K,\,+\,,\,\cdot\,)\ \ ` jest ciałem;

3. | :math:`\ (\alpha + \beta)\,\boxdot\,v \ \,=\ \,(\alpha\,\boxdot\,v)\,\oplus\,(\beta\,\boxdot\,v),`
   | :math:`\ \ \alpha\,\boxdot\,(v\,\oplus\,w) \ \,=\ \,(\alpha\,\boxdot\,v)\ \oplus\ (\alpha\,\boxdot\,w);`

4. :math:`\ \ \alpha\,\boxdot\,(\beta\,\boxdot\,v) \ \,=\ \,(\alpha\cdot\beta)\,\boxdot\,v;`

5. :math:`\ \ 1\ \boxdot\ v \ \,=\ \,v.`

W powyższych wyrażeniach :math:`\ \alpha\ \,\text{i}\ \,\beta\ ` są dowolnymi elementami ciała :math:`\,K\ `
(1 jest jednością tego ciała), :math:`\ ` natomiast :math:`\ v\ \ \text{i}\ \ w\ ` są dowolnymi elementami zbioru :math:`\,V.`

Elementy zbioru :math:`\,K\ ` nazywamy skalarami, :math:`\ ` a :math:`\ ` 
elementy zbioru :math:`\,V\ ` - :math:`\ ` wektorami.

W praktyce sam zbiór wektorów :math:`\,V\,` nazywany jest przestrzenią wektorową.
W tym ujęciu przestrzeń wektorowa to zbiór wektorów, które można dodawać
(i które tworzą grupę przemienną ze względu na dodawanie) oraz mnożyć przez skalary z ciała :math:`\,K\,`
(przy czym działanie to jest rozdzielne zarówno ze względu na dodawanie skalarów, jak i dodawania wektorów,
jest łączne w sensie warunku 4. oraz  spełnia warunek :math:`\,` 5.).

Najczęściej ciałem :math:`\,K\,` jest zbiór liczb rzeczywistych :math:`\,R\,` bądź liczb zespolonych :math:`\,C.\ `
Mówimy wtedy odpowiednio o przestrzeni wektorowej rzeczywistej :math:`\ V(R)\ ` bądź zespolonej :math:`\ V(C).`

| Przykłady:

* | Zbiór liczb rzeczywistych :math:`\,R\,` jest przestrzenią wektorową :math:`\,R(Q)\,` nad ciałem
    liczb wymiernych :math:`\,Q\,,\ `
    jak również przestrzenią wektorową :math:`\,R(R)\,` nad ciałem liczb rzeczywistych :math:`\,R\,.`
  | Na tej samej zasadzie zbiór liczb zespolonych :math:`\,C\,` tworzy przestrzeń
    rzeczywistą :math:`\,C(R)`
    oraz przestrzeń zespoloną :math:`\,C(C)\,.`

* Zbiór wektorów geometrycznych jest przestrzenią wektorową rzeczywistą 
  ze względu na dodawanie wektorów i mnożenie ich przez liczby rzeczywiste.

* Zbiór :math:`\,K^n,\,` złożony z :math:`\ n`-elementowych wektorów kolumnowych
  nad ciałem :math:`\,K,\,` jest przestrzenią wektorową
  nad tym ciałem ze względu na dodawanie wektorów i mnożenie ich przez skalary z :math:`\,K.`

* Również zbiór :math:`\,M_{m\times n}(K)\,` macierzy prostokątnych nad ciałem :math:`\,K\ ` 
  o :math:`\,m\,` wierszach i :math:`\,n\,` kolumnach jest przestrzenią wektorową nad :math:`\,K.`

Przyjmując, że mnożenie ma wyższy priorytet niż dodawanie, można wprowadzić zapis uproszczony,
który będzie w dalszym ciągu stosowany:

.. math::

   (\alpha\,\boxdot\,v)\ \oplus\ (\alpha\,\boxdot\,w)\quad\rightarrow\quad
   \alpha\cdot v\,+\,\alpha\cdot w\quad\rightarrow\quad
   \alpha\,v\,+\,\alpha\,w\,.

Podstruktury
~~~~~~~~~~~~
 
Załóżmy, że struktura :math:`\,\mathbb{G} = (G,\,\perp)\,` jest grupą.
Może się zdarzyć, że podzbiór :math:`H` zbioru :math:`G`
również tworzy grupę z (odpowiednio zwężonym) działaniem :math:`\,\perp\,.\ `
Mówimy wtedy, że :math:`\,H\,` jest *podgrupą* grupy :math:`\,G\,,\,`
co zapisujemy: :math:`\ H\,<\,G\,.`

Przykłady podgrup:

* Zbiór :math:`\,2Z\,` parzystych liczb całkowitych jest podgrupą
  grupy addytywnej wszystkich liczb całkowitych.
* Dwuelementowy zbiór :math:`\,\{-1,\,1\}\,` jest podgrupą grupy multiplikatywnej 
  liczb rzeczywistych różnych od zera.

Analogicznie określamy *podpierścienie*, *podciała* i *podprzestrzenie wektorowe*.

Podzbiór może być podstrukturą tylko wtedy, gdy działania w danej strukturze
nie wyprowadzają elementów poza ten podzbiór, czyli gdy podzbiór jest domknięty
ze względu na te działania (np. podzbiór :math:`\,2Z+1\,` liczb nieparzystych nie jest podgrupą 
grupy addytywnej :math:`\,Z,\,` bo suma dwóch liczb nieparzystych jest liczbą parzystą,
nie należącą do podzbioru). Ponadto w podzbiorze powinny być spełnione wszystkie postulaty
z definicji wyjściowej struktury.

W praktyce istnieją prostsze kryteria dla upewnienia się, że mamy do czynienia z podstrukturą.
Na przykład dla grup można udowodnić

**Twierdzenie:**

Niech :math:`\ \mathbb{G}\;=\;(G,\,\perp)\ ` będzie grupą,
:math:`\ \,\emptyset\neq H\,\subset G\,.`
   
Wówczas :math:`\ H < G\ ` wtedy i tylko wtedy, :math:`\,` gdy dla dowolnych 
:math:`\ a,b \in G\ ` spełniony jest warunek:

.. math::
      
   a,b\,\in\, H\quad \Rightarrow\quad
   \left(\ a\perp b\ \in\ H\ \ \wedge\ \ a^{-1}\,\in\,H \ \right)\,.

(niepusty podzbiór :math:`\,H\,` grupy :math:`\,G\,` jest podgrupą wtedy i tylko wtedy, gdy
:math:`\,H\,` jest domknięty ze względu na działanie grupowe oraz zawiera odwrotności
wszystkich swoich elementów).

Kryterium dla podprzestrzeni można sformułować dwojako:

**Twierdzenie:**

Niech :math:`\ W \subset V(K)\,.\ ` Wówczas :math:`\,W < V\ `
wtedy i tylko wtedy, :math:`\,` gdy dla dowolnych wektorów :math:`\,w_1,w_2 \in V\,`
oraz dla dowolnego skalara :math:`\,\alpha \in K\,` spełniony jest warunek:

.. math::
   :label: 01
      
   w_1,w_2\,\in\,W \quad\Rightarrow\quad
   \left(\ w_1+w_2\,\in\,W\ \ \wedge\ \ \alpha\,w_1\,\in\,W \ \right)\,,

czyli, :math:`\,` gdy dla dowolnych wektorów :math:`\,w_1,w_2 \in V\,` i dla dowolnych skalarów
:math:`\,\alpha_1,\alpha_2 \in K\,:`

.. math::
   :label: 02
      
   w_1,w_2\,\in\,W \quad\Rightarrow\quad
   \alpha_1\,w_1 + \alpha_2\,w_2\,\in\,W\,.

(podzbiór :math:`\,W\,` przestrzeni wektorowej :math:`\,V\,` nad ciałem :math:`\,K\,`
jest podprzestrzenią wtedy i tylko wtedy, :math:`\,` gdy jest domknięty
ze względu na dodawanie wektorów i mnożenie ich przez skalary z :math:`\,K\,,\ ` 
czyli :math:`\,` gdy dla dowolnych dwóch wektorów z :math:`\,W\,` każda kombinacja liniowa
tych wektorów też należy do :math:`\,W)\,`.

|
| Każda przestrzeń wektorowa :math:`\,V\,` ma dwie *podprzestrzenie niewłaściwe*.
  Są to: :math:`\,` cała przestrzeń :math:`\,V\ ` oraz jednoelementowy podzbiór zawierający
  tylko wektor zerowy :math:`\,\theta:\ \{\theta\}\,.` 
  Pozostałe podprzestrzenie są *właściwe*.

| Przykłady podprzestrzeni:

| 1.) Niech :math:`\,V\,` oznacza zbiór wektorów geometrycznych w przestrzeni,
| :math:`\,V_x,\,V_y,\,V_z\ \,-\ \,` podzbiory wektorów leżących odpowiednio
  na osiach :math:`\,Ox,\,Oy,\,Oz\,,`
| :math:`\,V_{xy},\,V_{yz},\,V_{xz}\ \,-\ \,` podzbiory wektorów leżących
  w płaszczyznach :math:`\,Oxy,\,Oyz,\,Oxz\,.`
| Podzbiory te są podprzestrzeniami przestrzeni :math:`\,V:\ \ `
  :math:`\,V_x,\,V_y,\,V_z,\,V_{xy},\,V_{yz},\,V_{xz}\,< \,V,`
| a ponadto zachodzą relacje: 
  :math:`\quad V_x,\,V_y\,<\,V_{xy}\,,\quad V_y,\,V_z\,<\,V_{yz}\,,\quad V_x,\,V_z\,<\,V_{xz}\,.`

2.) Rozważmy przestrzeń :math:`\,K^n\ \,n`-wyrazowych
wektorów kolumnowych nad ciałem :math:`\,K\,:`

.. math::
     
   K^n\ \ =\ \ \,\left\{\quad\left[\begin{array}{c}
                        x_1 \\ \ldots \\ x_p \\ x_{p+1} \\ \ldots \\ x_n
                        \end{array}\right]\ :\quad x_i\in K\,,\ \ i = 1,2,\ldots,n.\;\right\}\,,
                                                                                                    
oraz podzbiór :math:`\ W_p\ =\ \{\ \boldsymbol{x}\in K^n\,:\ \ x_{p+1}=\ldots = x_n = 0\,\}\,,\ `
gdzie :math:`\ 1 \leq p < n\,:`

.. math::
     
   W_p\ \ \,=\ \ \,\left\{\quad\left[\begin{array}{c}
                          x_1 \\ \ldots \\ x_p \\ 0 \\ \ldots \\ 0
                          \end{array}\right]\ :\quad x_i\in K\,,\ \ i = 1,2,\ldots,p.\;\right\}\,.

Stosując warunki :eq:`01` albo :eq:`02` łatwo sprawdzić,
że :math:`\,W_p\,` jest podprzestrzenią: :math:`\ \ W_p\,<\,K^n\,.` 

3.) Zbiór :math:`\,M_n(K)\,` macierzy kwadratowych stopnia :math:`\,n\,`
nad ciałem :math:`\,K\,` jest przestrzenią wektorową nad :math:`\,K\,` 
ze względu na dodawanie macierzy i mnożenie ich przez skalary z :math:`\,K\,`:

.. math::

   M_n(K)\ \ =\ \ \left\{\quad\left[\ \begin{array}{cccc}
                                     a_{11} & a_{12} & \ldots & a_{1n} \\
                                     a_{21} & a_{22} & \ldots & a_{2n} \\
                                     \ldots & \ldots & \ldots & \ldots \\
                                     a_{n1} & a_{n2} & \ldots & a_{nn}
                                     \end{array}\ \right]\ :\quad
                             a_{ij}\in K,\ \ i,j\,=\,1,2,\ldots,n.\;\right\}\,.

Podzbiór macierzy diagonalnych (elementy niezerowe występują tylko na głównej przekątnej):

.. math::

   D_n(K)\ \ =\ \ \left\{\quad\left[\ \begin{array}{cccc}
                                     a_{11} &   0    & \ldots &   0    \\
                                       0    & a_{22} & \ldots &   0    \\
                                     \ldots & \ldots & \ldots & \ldots \\
                                       0    &   0    & \ldots & a_{nn}
                                     \end{array}\ \right]\ :\quad
                             a_{ii}\in K,\ \ i\,=\,1,2,\ldots,n.\;\right\}\,.

jest podprzestrzenią: :math:`\ \,D_n(K)<M_n(K)\,,\ ` co znowu wynika z kryterium
:eq:`01` lub równoważnego mu :eq:`02`.

 
                                       

 
    




 












