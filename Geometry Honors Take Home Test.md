Baobao Kumble
Geometry Honors Take Home Test
April 26th, 2023

#### Problem 1 Proof:
In the diagram, we are given the triangle $\triangle{RHM}$, that the points of tangency of its incircle are points $B$, $E$, and $G$, and that all other points are the tangent points of its 3 excircles. We will prove that $\overleftrightarrow{BR}$, $\overleftrightarrow{DH}$, and $\overleftrightarrow{FM}$ are concurrent.

We will start by noting that, to finish, we can also prove that $\frac{MD}{DR}\cdot\frac{RF}{FH}\cdot\frac{HB}{BM}=1$, as by the converse of Ceva's theorem, we would be done. 

First off, by the ice cream cone theorem, $DR=RS$, $RF=RA$, and $HE=HB$, we can substitute: $$\frac{MD}{DR}\cdot\frac{RF}{FH}\cdot\frac{HB}{BM}=\frac{MD}{RS}\cdot\frac{RA}{FH}\cdot\frac{HE}{BM}$$
Next, by theorems 130 and 131, and by letting $RM=h$ and $RH=m$, $RS=s-h$, $RA=s-m$, we can substitute like so: $$\frac{MD}{RS}\cdot\frac{RA}{FH}\cdot\frac{HE}{BM}=\frac{MD}{s-h}\cdot\frac{s-m}{FH}\cdot\frac{s-h}{s-m}$$
After cancelling, we are left with $\frac{MD}{FH}$, and after applying the theorem 132, which states the sides of a triangle tangent to one of the excircles are equal to the semiperimeter of that triangle, we can substitute again and conclude: $$\frac{MD}{FH}=\frac{s}{s}=1$$
Circling back, we have just proved that $\frac{MD}{DR}\cdot\frac{RF}{FH}\cdot\frac{HB}{BM}=1$, and by the converse of Ceva's theorem, we are done. Q.E.D. 

#### Problem 2:
We are given that $\frac{HK}{HD}=\frac{5}{6}$ and $\frac{EF}{ED}=\frac{1}{5}$.

**Part A:**
In triangle $\triangle{KDF}$, points $H$, $E$, and $B$ are collinear and are on each side of the triangle, so we can use Menelaus' theorem and arrive at this: $$\frac{5}{6}\cdot\frac{5}{1}\cdot\frac{BF}{BK}=1\longrightarrow\frac{25}{6}\cdot\frac{BF}{BK}=1\longrightarrow\frac{BF}{BK}=\frac{6}{25}$$
In $\triangle{BKD}$, cevians $\overline{BH}$, $\overline{DF}$, and $\overline{KC}$ are concurrent at point $E$, so we can use Ceva's theorem and conclude this: $$\frac{6}{5}\cdot\frac{19}{6}\cdot\frac{BC}{CD}=1\longrightarrow\frac{19}{5}\cdot\frac{BC}{CD}=1\longrightarrow\frac{BC}{CD}=\frac{5}{19}$$
**Part B:** 
In $\triangle{DCK}$, points $H$, $M$, and $F$ are collinear and are on each side of the triangle, so we can use Menelaus' theorem and conclude this: $$\frac{5}{6}\cdot\frac{6}{1}\cdot\frac{EM}{MK}=1\longrightarrow\frac{5}{1}\cdot\frac{EM}{MK}=1\longrightarrow\frac{EM}{MK}=\frac{1}{5}$$

In $\triangle{DCK}$, points $H$, $E$, and $B$ are collinear and are on each side of the triangle, so we can use Menelaus' theorem and arrive at this: $$\frac{5}{6}\cdot\frac{24}{5}\cdot\frac{CE}{EK}=1\longrightarrow\frac{4}{1}\cdot\frac{CE}{EK}=1\longrightarrow\frac{CE}{EK}=\frac{1}{4}$$
Now, we know that $CE=1$, and we know that $MK=5$, so $\frac{EK}{MK}=\frac{1}{5}$. 
(Note to Mr. Worrall: I know for a fact that my solution for $\frac{CE}{MK}$ is wrong, but I couldn't find a way to get $CE$ to be in the same variable as $MK$ like you suggested, so I'm writing my solution)

#### Problem 3 Proof:
In the diagram, we are given that points $O$, $G$, and $H$ are the circumcenter, centroid, and orthocenter, respectively, of $\triangle{ABC}$. We are also given that $\overline{PQ}$ is a diameter of the circumcircle of $\triangle{ABC}$ and that $\overleftrightarrow{PG}$ intersects $\overline{HQ}$ at point $M$. We will prove that $M$ is the midpoint of $\overline{HQ}$.

We will begin by quoting the given that $O$, $G$, and $H$ are the circumcenter, centroid, and orthocenter. This given means that the segment $\overline{HO}$ is the Euler Line in $\triangle{ABC}$. This gives me two facts: that points $O$, $G$, and $H$ are collinear, and that $GH=2OG$, or that $\frac{OG}{GH}=\frac{1}{2}$.

Looking at the diagram, we can see that the segment $\overline{HO}$ makes up one side of the triangle $\triangle{HQO}$. We can observe that in this triangle, points $M$, $G$, and $P$ are collinear and are each on a side of the triangle. This is due to $M$ being given to be on $\overline{HQ}$, $G$ being on the Euler Line $\overline{HO}$, and $P$ being an endpoint of the diameter $\overline{PQ}$. Therefore, Menelaus' theorem is applicable in the triangle $\triangle{HQO}$. By applying Menelaus' theorem, we arrive at this equation: $$\frac{HM}{MQ}\cdot\frac{QP}{PO}\cdot\frac{OG}{GH}=1$$
Because we are given that $\overline{PQ}$ is the diameter of the circumcircle $O$, we can say that $\frac{QP}{PO}=\frac{2}{1}$ because the radius $\overline{PO}$ is half of the diameter. We also concluded earlier that $\frac{OG}{GH}=\frac{1}{2}$, since $\overline{HO}$ is a Euler Line. With these two pieces of information, we can substitute like so: $$\frac{HM}{MQ}\cdot\frac{2}{1}\cdot\frac{1}{2}=1$$
After cancelling the $\frac{2}{1}$ and $\frac{1}{2}$, we are left with this equation: $$\frac{HM}{MQ}=\frac{1}{1}$$
With this equation, we can conclude that $HM=MQ$, which proves that point $M$ is the midpoint of $\overline{HQ}$, and we are done. Q.E.D.

#### Problem 4 Proof:
In the diagram, we are given triangle $\triangle{ABC}$, where points $D_1$, $E_1$, and $F_1$ are the intersections of the internal angle bisectors with the sides opposite vertices $A$, $B$, and $C$, respectively; and points $D_2$, $E_2$, and $F_2$ are the intersections of the external angle bisectors with the sides opposite vertices $A$, $B$, and $C$, respectively. Also, let $a=BC$, $b=AC$, and $c=AB$.

We will start by noting that the main triangle to look at to solve this 

#### Problem 5 Proof:
In the diagram, we are given that points $P$, $N$, and $M$ are the midpoints of $\overline{AB}$, $\overline{AC}$, and $\overline{BC}$, respectively, in $\triangle{ABC}$. We are also given that points $I$ and $G$ are the incenter and the centroid, respectively, of $\triangle{ABC}$; and that point $S$ is on $\overline{IG}$ so that $G$ is between $I$ and $S$ and $IG=2SG$. We will prove that $\angle{SMP}\cong\angle{SMN}$ and that point $S$ is the incenter of $\triangle{PMN}$. 

We will start by noting that, since $\overline{PM}\parallel\overline{AN}$ and $\overline{NM}\parallel\overline{AP}$ by the midsegment theorem, we have a parallelogram $APMN$. In which, $\angle{SMP}\cong\angle{PAN}$, because opposite angles are congruent in a parallelogram. We also know that $\angle{PAI}\cong\angle{IAN}$ because we are given that $I$ is the incenter, so $\overline{AI}$ is an angle bisector.

First, we will prove that $\overline{SM}\parallel\overline{AI}$. We know that $\angle{SGM}\cong\angle{IGA}$ by the vertical angle theorem, we know that $AG=2GM$ by the median 2:1 theorem, and we are given that $IG=2GS$. By SAS similarity, we have proved that $\triangle{SMG}\sim\triangle{IAG}$. By "CPCTC", $\angle{SMG}\cong\angle{IAG}$, and by alternate interior angle theorem, $\overline{SM}\parallel\overline{AI}$.

Next, I extended $\overline{AI}$ and $\overline{SM}$ so that they intersect $\overline{PM}$ and $\overline{AN}$ at $Q$ and $R$, respectively. We just proved that $\overline{AQ}\parallel\overline{RM}$ and we know that $\overline{QM}\parallel\overline{AR}$ by the midsegment theorem, which gives us the parallelogram $QARM$. From this, we can reason that $\angle{SMP}\cong\angle{IAN}$ because opposite angles are congruent in a parallelogram. We already know that $\angle{NMP}\cong\angle{PAN}$, so by parts-whole, $\angle{SMN}\cong\angle{PAI}$. We know that $\angle{PAI}\cong\angle{IAN}$, so by transitivity, $\angle{SMP}\cong\angle{PAI}$. By even more transitivity, we conclude that $\angle{SMP}\cong\angle{SMN}$. Q.E.D.

By the angle bisector theorem, we have proved that $\overline{MS}$ is the bisector of $\angle{PMN}$. To prove that $S$ is the incenter of $\triangle{PMN}$, we would simply apply what we did to prove that to a different segment, such as $\overline{NS}$. We will prove that $\angle{SNP}\cong\angle{SNM}$ the same way that we proved that $\angle{SMP}\cong\angle{SMN}$. 

TL;DR: It's almost the same exact proof as in the first part, but replace some of the points and lines with what correspond with vertex $B$ and what you see in the diagram.

We will start by noting that, since $\overline{PN}\parallel\overline{BM}$ and $\overline{NM}\parallel\overline{BP}$ by the midsegment theorem, we have a parallelogram $BPNM$. In which, $\angle{PBM}\cong\angle{MNP}$, because opposite angles are congruent in a parallelogram. We also know that $\angle{MBI}\cong\angle{IBP}$ because we are given that $I$ is the incenter, so $\overline{BI}$ is an angle bisector.

First, we will prove that $\overline{SN}\parallel\overline{BI}$. We know that $\angle{SGN}\cong\angle{IGB}$ by the vertical angle theorem, we know that $BG=2GN$ by the median 2:1 theorem, and we are given that $IG=2GS$. By SAS similarity, we have proved that $\triangle{SNG}\sim\triangle{IBG}$. By "CPCTC", $\angle{SNG}\cong\angle{IBG}$, and by alternate interior angle theorem, $\overline{SN}\parallel\overline{BI}$.

Next, I extended $\overline{BI}$ and $\overline{SN}$ so that they intersect $\overline{PN}$ and $\overline{BM}$ at $X$ and $Y$, respectively. We just proved that $\overline{BX}\parallel\overline{YN}$ and we know that $\overline{XN}\parallel\overline{BY}$ by the midsegment theorem, which gives us the parallelogram $XBYN$. From this, we can reason that $\angle{SNP}\cong\angle{IBM}$ because opposite angles are congruent in a parallelogram. We already know that $\angle{PNM}\cong\angle{MBP}$, so by parts-whole, $\angle{SNM}\cong\angle{PBI}$. We know that $\angle{PBI}\cong\angle{IBM}$, so by transitivity, $\angle{SNP}\cong\angle{IBP}$. By even more transitivity, we conclude that $\angle{SNP}\cong\angle{SNP}$.

By the angle bisector theorem, we have just proved that $\overline{NS}$ is the bisector of $\angle{PNM}$. We have already proved that the bisector of $\angle{NPM}$, $\overline{PS}$, will be concurrent with the other two angle bisectors $\overline{NS}$ and $\overline{SM}$ at point $S$, and with that, we conclude that $S$ is the incenter of $\triangle{PMN}$. Q.E.D









