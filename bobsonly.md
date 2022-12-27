# Bobs-only extents of Stedman Triples

* TOC
{:toc}

## Introduction

Back in 1995 the question of whether it was possible to get an extent of Stedman Triples using only common bobs was settled with Colin Wyld's peals ([CompLib 21261](http://complib.org/composition/composition/21261) [CompLib 37681](https://complib.org/composition/37681)) and the Johnson/Saddleton peal ([CompLib 10423](https://complib.org/composition/10423)). These peals were one-part compositions with many bobs, and are hard to conduct.

Since then there have been further compositions starting with my 4 irregular 10-part peals from June 1995 with 438 bobs ([CompLib 28944](https://complib.org/composition/28944) [CompLib 28946](https://complib.org/composition/28946)) and 441 bobs ([CompLib 28945](https://complib.org/composition/28945) [CompLib 28947](https://complib.org/composition/28947)) which have been rung over 200 times. A further development in 2012 was another 148 10-part peals with between 438 bobs ([CompLib 31021](https://complib.org/composition/31021)) and 456 bobs [CompLib 37714](https://complib.org/composition/37714)), including several exact two-part peals, some with at most 5 bobs in a row. More recently were my exact three-part peals of 2017 ([CompLib 36006](https://complib.org/composition/36006)).

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

The magic blocks used in the Wyld and Johnson/Saddleton peals have the same rows as 10 B-blocks but in five round blocks, breaking the parity barrier. This is my compact form of showing them, where `-` means a bob and `P` means a plain after the six-end, and the `*1(1)` means the block is rung once, and there is one version of it in the peal (useful for multi-part peals).
```
2314567QS---------P------P--P*1(1)
2743516QS---------P------P--P*1(1)
2176534QS---------P------P--P*1(1)
2461573QS---------P------P--P*1(1)
2637541QS---------P------P--P*1(1)
```
Notice how they are a five-part set, with bells 2 and 5 fixed and 3,7,6,1,4 rotating.

There are then 10 B-blocks which are the complementary pairs of those first 10 blocks, and 64 remaining B-blocks, arranged in 32 complementary pairs. There are therefore 6^32 = 7.96×10^18 choices for those pairs, and some choices give enough Q-sets to link everything together. This gives 79 round blocks with 825 bobs, which perhaps could be reduced to one block using 39 Q-sets of 3 omits

There have been further minor developments in magic block peals. Colin Wyld found that he needed an extra Q-set of omits to link the blocks together, so the peal took 840 - 5*3 - 3*(79-1)/2 - 3 = 705 bobs. With a suitable choice of B-blocks the extra Q-set of omits is not needed and a peal of 708 bobs is possible, for example by bobbing some Q-sets of the first Johnson/Saddleton peal to give [CompLib 37705](https://complib.org/composition/37705). By bobbing one Q-set of Wyld's No. 1 then that can also be increased to 708 bobs ([CompLib 92949](https://complib.org/composition/92949)).

With more care then the omits can be all isolated, as shown by [CompLib 46033](https://complib.org/composition/46033) (rung on [14 March 2019](https://bb.ringingworld.co.uk/view.php?id=1276081)) and [CompLib 46069](https://complib.org/composition/46069) where there are just 8 omits after quick sixes (5 essential for the magic blocks plus 1 Q-set) and 124 after slow sixes. From my searches I do not think it is possible to reduce this to the 5 essential omits after quick sixes, thus answering Alan Burbidge's question in 'Stedman Triples and Similar Fascinations'. These peals can be reversed if required, putting most of the omits after the quick sixes and a few after the slow sixes.

The first bobs-only peal to be rung had 579 bobs. Shortly afterwards, Philip Saddleton reported that he had reduced that to 576 bobs, but did not publish it. I I have now composed a magic block peal with 576 bobs, [CompLib 59746](https://complib.org/composition/59746), which I believe to be the minimum on the plan.

It is not possible to get a peal using the magic blocks without at least one run of 9 bobs, for example [CompLib 91621](https://complib.org/composition/91621).

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
This looks similar to the magic blocks, but is different, and generates different peals. There is a peal with only 5 plains (omits) after a quick six, [CompLib 92794](https://complib.org/composition/92794), though with 2 double omits. To avoid double omits however requires at least 18 plains after a quick six. There are peals from 576 bobs ([CompLib 92793](https://complib.org/composition/92793)) to 708 bobs.

These blocks are clearly different as two of the blocks have 9,3,6 bobs in a run rather than 9,6,3.
```
2314567QS---------P------P--P*1(1)
2471536QS---------P------P--P*1(1)
2736514QS---------P------P--P*1(1)
5246317QS--------P--P------P-*1(1)
5217634QS--------P--P------P-*1(1)
```
There is a peal, [CompLib 91638](https://complib.org/composition/91638) which has only 7 omits after a quick six, the minimum using these blocks, and isolated omits. A similar peal with 7 omits after a slow six is [CompLib 84678](https://complib.org/composition/84678) There is also another peal, [CompLib 90948](https://complib.org/composition/90948) with a maximum of 6 bobs in a run, no 5-bob sets, and only 3 3-bob sets and 36 single bobs, so most of the time the alternation between quick and slow work is maintained.
```
2314567QS---------P------P--P*1(1)
2743516QS---------P------P--P*1(1)
2176534QS---------P------P--P*1(1)
5241637QS--------P--P------P-*1(1)
5236714QS--------P--P------P-*1(1)
```
This gives another peal, [CompLib 92964](https://complib.org/composition/92964) with a maximum of 6 bobs in a run, two 5-bob sets, and two 3-bob sets and 37 single bobs. A 579 bob peal is [CompLib 84857](https://complib.org/composition/84857). [CompLib 90545](https://complib.org/composition/90545) and [CompLib 90546](https://complib.org/composition/90546) have only 7 omits after a quick six.

See [CompLib 'Stedman Triples bobs-only peals'](https://complib.org/collection/11309) for the peals.

## 78 complete B-block peals 

There are some more peals based on combining all the rows of several B-blocks into larger round blocks. If all the sixes were separated then for these peals it would be possible to arrange them into 78 whole B-blocks with some sixes left over, so in the peal all the pieces of all 78 B-blocks are present and complete. This is for the convenience of classifying the peals as the choice of which pair of B-blocks with the same bells behind does not affect this statistic, neither does adding or removing 3 bobs in a Q-set [where the same 3 bells are affected by the call and the other bells are in the same position at each call].

### 73 round blocks
Here is the first block.
```
2314567QS---------P--------P-P--------P---------P-P--------PP-------P---------PP-------PP---------PPP--------PP------P---------PP*1(1)
```
Rotated version of that block: [CompLib 90582](https://complib.org/composition/90582)
#### Signature: 12:1+21
Links the contents of 12 whole B-blocks into 1 big block using 21 plains, giving 84-12+1=73 round blocks including the untouched B-blocks.
This leaves 12 more B-blocks as the pairs of those, and 60 paired B-blocks, where each pair can be chosen from one of six, making assembly of the peal quite easy. There are then 73 round blocks to link. By choosing the B-block pairs carefully extra Q-sets can be found which can be plained to reduce the total number of bobs.
- [CompLib 90595](https://complib.org/composition/90595) 576 bobs
- [CompLib 85949](https://complib.org/composition/85439) 576 bobs

There are 73 round blocks formed using 21 plains, so there is the chance of finding 72/2=36 Q-sets to link them into one block, the peal, which would add another 36*3=108 plains, so 129 plains and hence 711 bobs, but I have not found a peal using this block with that many bobs.

### 75 round blocks
```
2314567QS---------P------PP---------PPP------P--P--------P--------P---------PP---------PP*1(1)
2341576QS---------P------P--P*1(1)
2761534QS--------P-------P-PP*1(1)
```
#### Signature: 12:3+21
This takes the contents of 12 whole B-blocks and puts them into 3 round blocks using 21 plains.
There are then 12 B-blocks which are pairs of those original blocks before they were reconstituted, and 60 paired remaining B-blocks.
- [CompLib 93211](https://complib.org/composition/93211) 579 bobs

An upper limit of bobs in a peal on this plan is as follows: 21 plains, 75 blocks, so a possible maximum of 840 - 21 - 3 * (75 - 1) / 2 = 708 bobs.

### 77 round blocks (a)
```
2314567QS---------P--------P---------PP---------P-P------PP*1(1)
3671245QS---------P------P--P*1(1)
3517246QS--------P-------P-PP*1(1)
2314675QS--------P--P------P-*1(1)
```
#### Signature: 11:4+18
Upper limit of possible bobs: 840 - 18 - 3 * (77 - 1) / 2 = 708 bobs.

- [CompLib 93112](https://complib.org/composition/93112) 555 bobs
- [CompLib 85001](https://complib.org/composition/85001) 552 bobs (blocks reversed)
- [CompLib 88208](https://complib.org/composition/88208) 549 bobs

Instead of minimising the number of bobs, we can choose to reduce the number of sets of odd numbers of bobs in a run. This helps maintain the alternation of quick and slow work for the bells. Doing that gives the following peal, where the only runs of an odd number of bobs are single bobs, and there are only 18 of them. The 4-bob and 6-bob sets come at the start of the slow for some bell, whereas the  98 of the runs of 2 bobs are in quick, 23 are in slow. The treble does not have any odd bobs behind, just 0,2 or 6 bobs.
- [CompLib 84174](https://complib.org/composition/84174)
    - 594 bobs
    - 18 isolated bobs
    - 121 runs of 2 bobs
    - 7 runs of 4 bobs
    - 51 runs of 6 bobs

I think this peal would not feel like a Thurstans twin-bob peal as there are so many more bobs, but might be slightly easier on the band than other bobs-only peals.

### 77 round blocks (b)
```
2314567QS---------P-------P---------P-P------PP---------P-P*1(1)
2736514QS---------P------P--P*1(1)
2174563QS--------P-------P-PP*1(1)
5263417QS--------P--P------P-*1(1)
```
#### Signature: 11:4+18
- [CompLib 82690](https://complib.org/composition/82690) 582 bobs
- [CompLib 93059](https://complib.org/composition/93059) 546 bobs
This peal has 30 fewer bobs than any magic block peal.
