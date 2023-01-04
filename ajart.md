<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$']]summ
    }
  };
</script>
# Peals of Stedman Triples with bobs only

Date: February 24, 1995

Click [here](#table-of-Contents) for table of contents.

# Introduction

The first peal of Stedman Triples was rung in 1731. Until now, all peals of
Stedman Triples have had a least two singles. It has been a long standing
question as to whether a peal could be obtained with just common bobs alone.
This article examines the nature of the problem, the difficulties to be overcome
and the steps taken to arrive at a solution.

The are $5040/6 = 840$ possible calling positions in a peal of Stedman Triples.
Each of these calling positions can possibly have a bob, so a simple search
would require examining $2^{840}=7.3×10^{252}$ possible
touches. This is a huge number, far in excess of the number of atoms in the
universe, so a direct search is out of the question.

## Courses

An extent of Stedman Triples is 5040 changes, which is 60 whole courses, or 84
bobbed courses. A sequence of 3 bobs (for plain courses) or 3 omits (for bobbed
courses) on the same three bells links 3 courses or blocks of courses into 1
block.

## Q-sets

A Q-set is a set of calls affecting the same group of bells so forming a round
block, such as 3 bobs at home for Plain Bob Major.

Consider the following six ends, which are followed with either a bob or an
omit.
```
2314567      2314675      2314756
------- P    ------- P    ------- P
3241657      3241765      3241576

2314567      2314675      2314756
------- Bob  ------- Bob  ------- Bob
3241576      3241657      3241765
```
If an omit is rung after `2314567`, then the next row is `3241657`. This means that
a bob can not be rung after row `2314675`, because otherwise the same row would be
rung again. Therefore, if row `2314675` is rung at a six end it must be followed
by an omit, so row `3241765` must also be rung. This means that six end `2314765`
can not be rung with a bob, so must be rung with an omit.

If a bob is rung after `2314567`, then the next row is `3241576`. This means that an
omit can not be rung after row `2314756`, because otherwise the same row would be
rung again. Therefore, if row `2314756` is rung at a six end it must be followed
by a bob, so row `3241765` must also be rung. This means that six end `2314675` can
not be rung with an omit, so must be rung with a bob.

The set of six ends `2314567`, `2314675`, `2314756`, must therefore be rung either all
with a plain following, or all with a bob following, or at most two members of
the set can be present. This set is an example of a Q-set, and is why bobs come
in threes, affecting the same three bells, in compositions containing Q-sets of
six ends. Similarly for compositions based on bobbed courses, the omits come in
threes, affecting the same three bells.

These Q-sets contain an odd number of elements. If there was only one way of
ringing a row then the Q-set rule would imply that courses have to be linked
using Q-sets, joining an odd number of courses into a smaller odd number. As
there are an even number of courses to start with, and an extent is all rows in
one block (an odd number), this gives the basis of the proof that an extent of
Grandsire Triples requires singles.

Fortunately for Stedman Triples, a row can be obtained in six ways, three in a
quick six and three in a slow six. The Q-set rule does not disprove the
existence of a bobs only peal, because the third element of a Q-set could be
obtained elsewhere in a six.

## Whole course compositions

The greatest number of mutually true plain courses of Stedman Triples is 40. The
fact that you can not find 60 plain courses containing all the rows in an extent
was shown by W.H.Thompson. This means that you can not take plain courses, link
them by 3 bobs and hope to get a peal.

## Twin bob compositions

These use pairs of consecutive bobs, at positions 3,4 (=S, in slow); 5,6 (=H,
first half turn); 7,8 (=L, last whole turn) and 12,13 (=Q, in and out quick).
Peals based on Thurstans' block are the most common example of this type of
peal.

I investigated this type of peal, and found using computer searches several nice
half peals which could be linked with singles to give a true peal. Linking the
halves with twin bobs failed, with 12 changes repeated.      

## Use of singles in Stedman Doubles

A row can be categorised as either odd or even depending on whether it takes an
odd or even number of swaps of adjacent bells to return the row to rounds.

With Stedman Doubles, exactly two pairs of bells are swapped in each change in a
plain course. This means that as a plain course starts with rounds, an even row,
every row must also be even. A plain course of Stedman Doubles has 60 even rows.
An extent of doubles contains 120 rows, of which 60 are odd and 60 even. The
other 60 rows are odd, and the only way of getting to them is to swap an odd
number of bells over for one change. This change with an odd number of bells
being swapped is a 'single', because only a single pair of bells are swapped.
The odd rows can then be rung. A further single is required to switch back to
even rows, so that rounds can then be arrived at.

This is why Stedman Doubles requires pair(s) of singles to ring the extent.

## Use of singles in Stedman Triples

With Stedman Triples, exactly three pairs of bells are swapped each change. This
means that the rows generated are alternately odd and even, and there is no
requirement for singles to generate odd rows.

Singles are useful however to join a pair of blocks together, rather than three
blocks. This is why conventional compositions uses singles; to link an even
number of blocks into an odd number of blocks, so then three bobs or three omits
can be used link three blocks into one, reducing the number of blocks by two
each time until finally there is one block, the actual peal.

## Bob Courses

Peals based on bobbed courses (B-blocks) are another major class of Stedman
compositions, for example Slack's two-part. The front work of a bobbed course is
that of Stedman Doubles, while the back bells dodge for 60 changes as 10 bobs
are called, with 30 changes one way round, and 30 changes the other.

Henceforth, course will mean bobbed course. Bobbed courses are easier (for the
composer, not the conductor) to work with, because they are true against all
courses with other bells behind. As odd and even rows alternate if no singles
are used, they are true against all courses with the back bells swapped. My
investigations of B-blocks revealed several ideas for bobs only peals, most of
which proved unsuccessful, but did give some ideas for conventional peals with
singles.

## Number of different courses

For a given pair of bells at the back with a bobbed course, there are 5 front
bells. This does not mean that there are $5!=120$ possible different courses. If
there are no singles, then the end of a course must be an even row, so that
restricts number of different courses to 60. Each course can be started in 5
different places, by moving on two sixes. This gives 12 different courses.

## Partners of courses

By ringing the front work backwards, the same bells on the front will come up
back and hand instead of hand and back, and so will come up with the back bells
the other way around. These two possible courses are mutually true, and can be
termed partners of one another.

For a composition, once a course is decided, there is no choice for the partner
course, so there are only six possibilities for a pair of courses that can be
chosen for each permutation of bells at the back.

## Combining an even number of blocks into an odd number of blocks
### Known by P A B Saddleton and A Johnson

If there was some way of combining all the rows in an even number of courses
into an odd number of blocks, then this would be a significant step in obtaining
a bobs only peal of Stedman Triples. This is because then together with the
unused courses there would be an odd number of blocks containing all the rows in
an extent. These blocks could then in theory be linked using Q-sets so as to
form just one block, containing all the rows, which would be a peal. Similarly,
it would be useful if there was a way of combining an odd number of courses into
an even number of blocks.

## Observations about Stedman Doubles
### Discovered by A Johnson

If the front work is considered as Stedman doubles, and the changes on `23145` as
a six end are written out, and the changes on `34125` are written out, then it can
be seen that the rows in sixes 5,6,7 of the first course are also in the other
course in sixes 7,5,6.

This was discovered just using pencil and paper, whilst investigating how
falseness between courses is distributed, by choosing a course which is clearly
false against the other in the first six. Falseness incidence between courses is
important because the Q-set rule suggests that a peal can not be obtained with
whole courses alone.

Full details of sixes 5,6,7
```
41253 B          21354 B
-----  5         -----  5
14523 H          12534 H  Same rows as
41532 B          21543 B  in 7th six of
45123 H          25134 H  course 23145
54132 B          52143 B
51423 H          51234 H
15432 B          15243 B
-----  6         -----  6
51342 H          51423 H  Same rows as
53124 B          54132 B  in 5th six of
35142 H          45123 H  course 23145
31524 B          41532 B
13542 H          14523 H
15324 B          15432 B
-----  7         -----  7
51234 H          51342 H  Same rows as
15243 B          15324 B  in 6th six of
12534 H          13542 H  course 23145
21543 B          31524 B
25134 H          35142 H
52143 B          53124 B
-----  8         -----  8
25413 H          35214 H
```
The rows occur at handstroke in both courses or at backstroke in both courses.
This means that all the rows in the course `21345` can be rung by ringing sixes
1,2,3,4,8,9,10 of course `23145` and sixes 5,6,7 of course `34125`. By symmetry,
sixes 5,6,7 of course `42135` could be used instead of sixes 5,6,7 of course
34125.

## Implications for bobbed courses of Stedman Triples
### Discovered by A Johnson

The common rows occur at handstroke in both courses or at backstroke in both
courses. This means that if instead of a course of Stedman Doubles, a bobbed
course of Stedman Triples is rung, then the same arrangement of front bells in
the two courses will occur with the back bells the same way around, so the whole
row will be the same.

A way of switching in and out of bobbed courses at the 5th or 8th six is to put
an omit at those positions. The same bell makes 5ths at calling position 5 or 8,
so if there are omits at 5 and 8, a third omit at 8 gives a round block.
```
             Calling positions
Course end   1 2 3 4 5 6 7 8 9 0
   2314567   AAAAAAAAAAAAAA-EEEEE
   2614573   CCCCCCCC-      BBBBB
   2714536            DDDDD-
```
The course end is the six end that would result if the course was allowed to run
until just before calling position 1. The order the sixes are rung is indicated
by the letters.

This gives a block in which one course (`2314567`) is rung in its entirety, a
course (`2614573`) in which 7 sixes are rung and a course (`2714536`) in which 3
sixes are rung.

Having taken these three course, the gap in course `2614573` could be filled in
trivially by ringing sixes 5,6,7 from the same course. This is not very useful,
because the course would have to be entered from `2314567` at calling position 5,
which has already been rung.

However, there are other ways of ringing these rows. The missing 5,6,7 sixes in
course `2614573` could be rung by ringing sixes 5,6,7 from course `6412573` or
course `4216573`. These two courses are the course `2614573` with the bells in the
same starting positions that bells `234` in course `2314567` transposed as `234` to
`342` or `234` to `423`.

If course `6412573` is chosen for example, these courses can be written out:
```
             Calling positions
Course end   1 2 3 4 5 6 7 8 9 0
   2314567   XXXXXXXXXXXXXX-XXXXX
   2614573   XXXXXXXX-      XXXXX
   2714536            XXXXX-

   6412573            XXXXX-       fills in
                             course 2614573
```
Now the part of course `6412573` can be generated as part of another round block.
There is a gap in one of these generated courses, so this process can be
repeated.

Consider the following 5 sets of two-course blocks, with omits at 8,5,8.
```
X = part of course rung
# = part of course rung by rows
    from another course elsewhere
% = part of course which fills in
    a gap in a course rung
    elsewhere
The corresponding course is on the right.

             Calling positions     Other
Course end   1 2 3 4 5 6 7 8 9 0   course
   2314567   XXXXXXXXXXXXXX-XXXXX
   2614573   XXXXXXXX-##### XXXXX (6412573)
   2714536            %%%%%-      (4217536)

   6712534   XXXXXXXXXXXXXX-XXXXX
   6312547   XXXXXXXX-##### XXXXX (3216547)
   6412573            %%%%%-      (2614573)

   3416572   XXXXXXXXXXXXXX-XXXXX
   3716524   XXXXXXXX-##### XXXXX (7613524)
   3216547            %%%%%-      (6312547)

   7213546   XXXXXXXXXXXXXX-XXXXX
   7413562   XXXXXXXX-##### XXXXX (4317562)
   7613524            %%%%%-      (3716524)

   4617523   XXXXXXXXXXXXXX-XXXXX
   4217536   XXXXXXXX-##### XXXXX (2714536)
   4317562            %%%%%-      (7413562)
```
This gives a set of 5 two-course round blocks, with a cyclic relationship
between them, so each block has part of a course filled in by part of the next
block, and the last block has part of a course filled in by the first block.

When this process has been completed, it is seen that there are five round
blocks, which contain all the rows in the following ten courses, and no other
rows.
```
2314567 6712534 3416572 7213546 4617523
2614573 6312547 3716524 7413562 4217536
```
We have therefore managed to reduce an even number of courses to an odd number
of blocks. This is the essential step which makes possible a peal of Stedman
Triples with bobs only. I termed these five two-course blocks the 'magic blocks'
because of this. After writing the first draft I learnt that Colin Wyld
discovered this step three years before me, and that Brian Price worked out
these blocks some weeks after I discovered them. Colin then used this technique
last autumn to produce the first bobs only extent of Stedman Triples.

If we also consider the 10 one-course blocks which are the partners of the
special ten courses, then that gives 15 blocks containing all the rows in 20
B-blocks. To get a peal these 15 blocks need to be linked with the remaining 64
B-blocks using Q-sets of omits. This is a reasonably well known, though not
always easy technique. The set of 15 B-blocks to be linked is as follows.
```
2314567 or 2614573; 3215467 and 6215473
6712534 or 6312547; 7615234 and 3615247
3416572 or 3716524; 4315672 and 7315624
7213546 or 7413562; 2715346 and 4715362
4617523 or 4217536; 6415723 and 2415736
```
Where there is a choice of courses, either course can be linked into the touch
with a set of three omits. The other course need not be included, because it
will then be linked in as above, using omits at 8,5,8.

There is then a free choice for the order of the front bells for the other $84-20=64$
B-blocks, to give a set which can be linked together. In fact once one
course has been chosen, its partner is fixed, so this gives a choice of $64/2=32$
pairs of courses. There are 6 possible pairs of courses with each combination
of back bells, which gives $6^{32}=7.9×10^{24}$ possibilities.
Although this is big, this is nothing like the $2^{840}$ possibilities
considered earlier.

## Linking the blocks together
### Work done by A Johnson

There are 15+64 = 79 blocks to be linked together. Three blocks may be linked
into one by three omits on members of a Q-set. This means that at least $(78/2)×3=117$
omits are required to link 79 blocks into one. There are also $3×5=15$
omits in the 5 magic blocks. This gives at least $117+15=132$ omits, so at most
$840-132=708$ bobs in a peal on this plan.

## Adding extra omits
### Known by P A B Saddleton

There are two places in a bobbed course where the same three bells are affected
by an omit. This can be used to have a round block using six omits and not
three.      

For example:
```
             Calling positions
Course end    1 2 3 4 5 6 7 8 9 0
   2314567   A-EEEEE-IIIIIIIIIIII
   2314675   G-BBBBB-FFFFFFFFFFFF
   2314756   D-HHHHH-CCCCCCCCCCCC
```
The letters show the order in which the parts of the course are rung.

This can be done for any block of three, providing an omit does not occur in a
missing part of a partial course in a magic block, so allowing the bob count to
be reduced in multiples of three.

## Consequences of extra omits

This would allow up to another 117 omits, giving a total of 591 bobs. As the
omits can be added independently for any set of 3 omits, the number of bobs can
be varied in multiples of three from 591 to 708. There are therefore perhaps $2^{39}$
trivial variations on any possible peal. As a peal could be started in any quick
six, this multiplies the variations by 480, and by another 2 if the peal is rung
backwards.

This gives an estimate of $2×480×2^{39}=5.3×10^{14}$
variations of any peal generated. Ringing them all would take about 10 times the
current age of the universe, surely enough for any peal tour.

## Course ends

When linking courses together, it is easier to write out the ends of courses.
Transposing bells as the result of omits at certain positions is easily done.
```
Omit at 1 (or 4)   2314567 -&gt; 2314675
Omit at 7 (or 10)  2314567 -&gt; 2316574
Omit at 5 (or 8)   2314567 -&gt; 2614573
Omit at 3 (or 6)   2314567 -&gt; 6314572
Omit at 9 (or 2)   2314567 -&gt; 2364571
```
The same course is given by the end of any quick six, so the following courses
are all equivalent:
```
2314567 3451267 4125367 1532467 5243167
```
The partner of course `2314567` is course `3215467`. These courses are all
equivalent:
```
3215467 2541367 5134267 1423567 4352167
```
## Linking partners of B-blocks
### Known by P A B Saddleton

In general, if a partner of an existing course in a block is linked into the
block, then several other partner courses can easily be linked in as well.      
This is done by applying three omits on the same three bells on the partner
course as on the original course. The additional blocks linked will also be
partners of existing courses. This process can be repeated until all the
partners are obtained.

## Methods of linking the blocks together
### Work done by A Johnson

I succeeded in linking 11 of the 15 blocks in 2280 or 2400 changes, and 13 of
the 15 blocks in 3000 changes by linking in two new courses using sets of 3
omits, but could not link all 15 blocks.

The linking of 11 of the blocks was done by hand, after writing out all the five
equivalent six ends for each course, to make any similarity between courses more
obvious. The five whole courses in the magic blocks were linked, then one of the
partners of split course of the magic blocks was linked in. This meant that by
the rule for linking partners of blocks, starting from the split course in a
magic block I could apply the same omits to it as was applied to the partner of
the split course which was already linked in. This linked all the partners of
all the courses so far, apart from partners of the four split courses in the
magic blocks. The four blocks to be linked were partners of courses in the magic
blocks. The magic blocks were already connected into the main part of the
composition.

The unused courses were not sufficient to link the partners into the main block,
as one course was required to be used in different ways for several of the
partners.

A variation of the original main block allowed one of the magic blocks to be
linked in via one of the split courses. This meant that the whole course in the
magic block was the course without a partner, and that as different unused
courses were available linking the unlinked partners was not obviously
impossible.

Linking in single courses without a partner is difficult without leaving another
course linked in without a partner. This occurs because courses must be linked
in twos.

One way of solving this problem of linking the partner courses called say
A,B,C,D was to link A to the partner of B, which was already in the main part of
the touch. By symmetry B could then be linked to the partner of A, also in the
main touch. This links in two of the courses. Having done this I could not then
link the other two courses, because there were not enough useful B-blocks left.

## Other methods of linking blocks together
### Work done by P A B Saddleton

Philip Saddleton took a more systematic approach to linking courses. He chose by
hand which courses to link, but had computer assistance in listing which other
courses would not be accessible if certain choices were made.

The aim was to find a set of 42 pairs of courses, including the       courses
making up the magic blocks, with as many Q-sets of omits as possible available
to link the courses together. Philip maximised the connectivity between courses
by where possible completing Q-sets where two members were already present, thus
only adding one course. The partners were linked with complementary Q-sets. He
also made sure there was always a potential exit point from each block. When
this was finished all the courses has been chosen, and there were 22 pairs of
Q-sets of omits. The courses were then connected by choosing all available
Q-sets of omits and the 15 omits used in the magic blocks. Two Q-sets could not
be used, since they contained an element in the substituted sixes of the magic
block. Adding all possible omits gave seven blocks. These blocks were then
joined by replacing four Q-sets of omits with bobs. After considerable work,
Philip had managed to link the 15 blocks together with another 64 B-blocks to
give a peal. The peal thus contains $3×5+22×(4×3)-2×3-4×3=261$ omits,
hence 579 bobs.

The actual composition differs in the precise 20 courses chosen to make up the
initial 15 blocks illustrated earlier, but the principle is the same. Philip's
composition is based on 5 blocks with calls at 1,4;4, rather than 8;5,8.

A Cambridge University Guild band, with Philip Agg conducting, rang this
composition at St John the Evangelist, Waterloo Road on 22nd January 1995. This
was the first peal rung of Stedman Triples with bobs only.

Andrew Johnson

## The composition
```
 5040 Stedman Triples
 by A Johnson and P A B Saddleton

 2314567  1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0
 ________________________________________________
 2416753    - -   - -   - - - - - - - - -     - -
 3415762  - -   - -   - - - - -   - - - -   -   -
 3425716    - -   - - - - - -     - - - - - -   -
 7214635  -   -     -   - -   - -   - -   - - - -
 5247136  - -   - -     -   - -   -   - - - - - -
 5274631    - -   - -   - -   -   - - - -   - -
 3715642  -   - - - - - - - - -     - -       - -
 7451623  - - - -   -   -   - -     - -     - -
 4752613  - - - - - -     - - - -   - -   -   - -
 3156247    - -   - - - - -     - -   -   -   - -
 4756231    - -   - - - - - -   -   - - - -   - -
 3456271    - -   - - - - - -   -   -   - -   - -
 7356241  - -   -   - -     - -   - - - - - -   -
 1456237  -   - - - - - -   - -   - -     - - - -
 4752361  - -   -     - - - - - -     - -   - -
 3752641    -   - -   - -   - -   - - - - - -   -
 4752136  -   - - - - - -   - -       - - - - - -
 7453612    - -     - -   - - - -   -   - -   -
 1732645  - - - - - -   - -   - -   - -   -     -
 1532746    - - - - - -   - -   - -   - - - - - -
 1432657    - -     - -     - -   - - - - - -   -
 1472635  -     -       - -   - - - - - -       -
 6534721  -   - -   -   - -     - -   -   - - - -
 1534762  - -   -   - -   - - - - - -     - - - -
 2134765    - -   - - - - - -   -   - -   -   - -
 1734652  - - - -   - -   - - - -       - -   - -
 1745263  - - - -   -           - -   - - - - - -
 1742653    - -   - - - - - -   - -   - -   - -
 7152643  -     - -   -   - - - - - -     -   - -
 3417652  - - - -     - - - - -   - - - -   - - -
 3217564  - - - - - -     -     - -   - - - - - -
 5413672    -   -   - -   - - - - - -         - -
 5247361  - - - -   - -         - -   - - - - - -
 4517632          - - - - - -   - -   -   -   - -
 4516372    - -   - - - - - -   - -   - -   - -
 4517326  - -   - -   - -   -     -   -   - - -
 3215674    - -     - -   - - - -   - -     - -
 3215746    - -   - - - - - -   - -   - - - - - -
 3465721    - -     - -   - -   - -   - - - -   -
 3456712  -   - - - -   - - - - - - - - -   -   -
 7316542  -     -   - -   - -   - -   -   - - - -
 2314567  - -     - - - - - -   - -   -     - -
 ________________________________________________
Contains 579 bobs.
Rung at St John's, Waterloo Road, on 22nd January 1995,
conducted by Philip J Agg.
```

## Table of Contents

* TOC
{:toc}
