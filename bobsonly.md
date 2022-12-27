# Bobs-only extents of Stedman Triples

## Introduction

Back in 1995 the question of whether it was possible to get an extent of Stedman Triples using only common bobs was settled with Colin Wyld's peals (http://complib.org/composition/composition/21261 https://complib.org/composition/37681) and the Johnson/Saddleton peal (https://complib.org/composition/10423). These peals were one-part compositions with many bobs, and are hard to conduct.

Since then there have been further compositions starting with my 4 irregular 10-part peals from June 1995 with 438 bobs (https://complib.org/composition/28944 https://complib.org/composition/28946) and 441 bobs (https://complib.org/composition/28945 https://complib.org/composition/28947) which have been rung over 200 times. A further development in 2012 were another 148 10-part peals with between 438 bobs (https://complib.org/composition/31021) and 456 bobs (https://complib.org/composition/37714), including several exact two-part peals, some with at most 5 bobs in a row. More recently were my exact three-part peals of 2017 (https://complib.org/composition/36006).

Since then I have come up with many more peals, though they are likely to be too hard to call for most conductors.

There are 840 places (at any six-end) where a bob could be called in an extent of Stedman Triples, which would give 7.3×10^253 possibilities. This is so huge that a direct search is impossible. Another approach is to cover all the rows with multiple shorter touches, each with a different starting row and returning to its start point (round blocks). You cannot cover all the rows with plain courses (the maximum is 40 of the required 60, but the remaining rows are unlinkable). You can cover all the rows with 84 B-blocks, 60 change round blocks of 10 bobs in a row. The problem then is to link the round blocks together into one big block. Omitting a bob from three B-blocks affecting the same 3 bells behind while the front 4 bells are in the same position can link them into one. That process would at best reduce the number of round blocks down from 84 in twos to give two unlinkable round blocks. 

This is an example of the Q-set parity law. With Grandsire Triples using only common bobs there is only one lead head which brings up a row which leads to the proof of the impossibility of a extent of Grandsire Triples using just common bobs. Stedman Triples is made up of sixes, and any row could appear in a six defined by one of six possible six-ends, three quick or three slow, which breaks the Q-set parity law restriction, similar to how in Cambridge Surprise Minor a row can appear either of two leads, the forward or backwards version, thus allowing a bobs-only 720.

B-blocks have a pair of bells dodging behind and two B-blocks can cover all the rows with a pair of bells dodging a particular way round. For each pair there are six possible complementary pairs of B-blocks, as illustrated by the six-ends below. The 'QS' is my convention for a quick six-end (to be followed by a slow six) and SQ for a slow six-end.

```
2314567QS
3215467QS

3124567QS
1325467QS

1234567QS
2135467QS

2314567SQ
2134567SQ

3124567SQ
3215467SQ

1234567SQ
1325467SQ
```

## Magic Block Peals

The magic blocks used in the Wyld and Johnson/Saddleton peals have the same rows as 10 B-blocks but in five round blocks, breaking the parity barrier. This is my compact form of showing them, where '-' means a bob and 'P' means a plain after the six-end, and the '*1(1)' means the block is rung once, and there is one version of it in the peal (useful for multi-part peals).
```
2314567QS---------P------P--P*1(1)
2743516QS---------P------P--P*1(1)
2176534QS---------P------P--P*1(1)
2461573QS---------P------P--P*1(1)
2637541QS---------P------P--P*1(1)
```
Notice how they are a five-part set, with bells 2 and 5 fixed and 3,7,6,1,4 rotating.

There are then 10 B-blocks which are the complementary pairs of those first 10 blocks, and 64 remaining B-blocks, arranged in 32 complementary pairs. There are therefore 6^32 = 7.96×10^18 choices for those pairs, and some choices give enough Q-sets to link everything together. This gives 79 round blocks with 825 bobs, which perhaps could be reduced to one block using 39 Q-sets of 3 omits

There have been further minor developments in magic block peals. Colin Wyld found that he needed an extra Q-set of omits to link the blocks together, so the peal took 840 - 5*3 - 3*(79-1)/2 - 3 = 705 bobs. With a suitable choice of B-blocks the extra Q-set of omits is not needed and a peal of 708 bobs is possible, for example by bobbing some Q-sets of the first Johnson/Saddleton peal to give https://complib.org/composition/37705. By bobbing one Q-set of Wyld's No. 1 then that can also be increased to 708 bobs (https://complib.org/composition/92949).

With more care then the omits can be all isolated, as shown by https://complib.org/composition/46033 (rung on 14 March 2019) and https://complib.org/composition/46069 where there are just 8 omits after quick sixes (5 essential for the magic blocks plus 1 Q-set) and 124 after slow sixes. From my searches I do not think it is possible to reduce this to the 5 essential omits after quick sixes, thus answering Alan Burbidge's question in 'Stedman Triples and Similar Fascinations'. These peals can be reversed if required, putting most of the omits after the quick sixes and a few after the slow sixes.

The first bobs-only peal to be rung had 579 bobs. Shortly afterwards, Philip Saddleton reported that he had reduced that to 576 bobs, but did not publish it. I I have now composed a magic block peal with 576 bobs, https://complib.org/composition/59746, which I believe to be the minimum on the plan.

It is not possible to get a peal using the magic blocks without at least one run of 9 bobs, for example https://complib.org/composition/91621.

In classifying bobs-only peals it is useful to have some statistics which do not change with the choice of Q-sets plained or bobbed or the choice of pairs of complementary B-blocks.

* Number of round blocks when all Q-sets bobbed.
* Number of bobs when all Q-sets bobbed.
* Number of whole B-blocks when all Q-sets bobbed.
* Number of whole paired B-blocks when all Q-sets bobbed.
* Number of complete B-blocks (take all the sixes, and without changing their type can they be chopped up and reassembled into whole B-blocks).
* Number of paired sixes

When comparing peals other statistics can determine their merit:

* Number of bobs (normally minimised, sometimes maximised)
* Minimise the longest run of bobs
* Minimise the number of runs of an odd number of bobs, so that bells normally alternate going in quick and slow
* Longest run of plain leads, prefer runs ending at a slow six so that the peal can finish in the plain course
* Multiple parts
* Repeated sections
* Number of different courses

## Other 79 complete B-block peals 

Recently I discovered some more peals, which although looking similar to magic block peals are in fact different. Some are based on these blocks
```
2314567QS---------P------P--P*1(1)
2471536QS---------P------P--P*1(1)
2736514QS---------P------P--P*1(1)
2167543QS---------P------P--P*1(1)
2643571QS---------P------P--P*1(1)
```
This looks similar to the magic blocks, but is different, and generates different peals. There is a peal with only 5 plains (omits) after a quick six, https://complib.org/composition/92794, though with 2 double omits. To avoid double omits however requires at least 18 plains after a quick six. There are peals from 576 bobs (https://complib.org/composition/92793) to 708 bobs.

These blocks are clearly different as two of the blocks have 9,3,6 bobs in a run rather than 9,6,3.
```
2314567QS---------P------P--P*1(1)
2471536QS---------P------P--P*1(1)
2736514QS---------P------P--P*1(1)
5246317QS--------P--P------P-*1(1)
5217634QS--------P--P------P-*1(1)
```
There is a peal, https://complib.org/composition/91638 which has only 7 omits after a quick six, the minimum using these blocks, and isolated omits. A similar peal with 7 omits after a slow six is https://complib.org/composition/84678 There is also another peal, https://complib.org/composition/90948 with a maximum of 6 bobs in a run, no 5-bob sets, and only 3 3-bob sets and 36 single bobs, so most of the time the alternation between quick and slow work is maintained.
```
2314567QS---------P------P--P*1(1)
2743516QS---------P------P--P*1(1)
2176534QS---------P------P--P*1(1)
5241637QS--------P--P------P-*1(1)
5236714QS--------P--P------P-*1(1)
```
This gives another peal, https://complib.org/composition/92964 with a maximum of 6 bobs in a run, two 5-bob sets, and two 3-bob sets and 37 single bobs. A 579 bob peal is https://complib.org/composition/84857. https://complib.org/composition/90545 and https://complib.org/composition/90546 have only 7 omits after a quick six.

See https://complib.org/collection/11309 for the peals.
