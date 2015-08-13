---
layout: entry
title:  'Sandbox'
---

# Sandbox

This file is intended as a "sandbox" for trying out the editing
features. Feel free to make changes by clicking the "edit page" link
at the top. (You need to be logged in to GitHub and have write
permissions to this GitHub repository for this to work.)

----------

# Some markdown

* bulleted
* list

1. numbered
2. list

Link: [link text](http://www.example.com)

# header 1

## header 2

### header 3

*italics* and **bold**

`inline code`

----------

# Some visualizations

~~~ conllu
1	བཅོམ་ལྡན་འདས	bcom_ldan_'das	PROPN	PROPN	_	65	vocative	_	Bhagavat|Sanskrit=bhagavan
2	།	/	PUNCT	PUNCT	_	54	punct	_	_
3	བྱང་ཆུབ་སེམས་དཔའ་	byang_chub_sems_dpa'	NOUN	NOUN	_	58	appos	_	bodhisattva|Sanskrit=bodhisattvo
4	སེམས་དཔའ་ཆེན་པོ་	sems_dpa'_chen_po	NOUN	NOUN	_	58	appos	_	The_great_being;_mahasattva|Sanskrit=mahāsattvo'-
5	སྤྱན་རས་གཟིགས་ཀྱི་དབང་ཕྱུག་	spyan_ras_gzigs_kyi_dbang_phyug	PROPN	PROPN	_	65	nsubj	_	Avalokiteshvara|Sanskrit=avalokiteśvaro
6	ཅི	ci	NOUN	NOUN	_	61	nmod	_	"what;_however;_whatever;_can_indicate_question:_""Is_..._(the_case)?;_who|Sanskrit=kena"
7	འི་	'i	ADP	ADP	_	59	case	_	genitive_particle|Sanskrit=kena
8	སླད་	slad	NOUN	NOUN	_	65	nmod	_	"1)_for_the_sake/_purpose_of,_because_of,_in_order_to;_2)_later,_afterward,_*,_again,_bslad,_lhad|Sanskrit=kāraṇena"
9	དུ་	du	ADP	ADP	_	61	case	_	"accusative,_adverbial_accusative,_dative,_and_locative_particle:_to;_in;_as;_-ly;_at;_many;_plural_into._how_many|Sanskrit=kāraṇena"
10	སྤྱན་རས་གཟིགས་ཀྱི་དབང་ཕྱུག་	spyan_ras_gzigs_kyi_dbang_phyug	PROPN	PROPN	_	65	xcomp	_	Avalokiteshvara|Sanskrit='valokiteśvara
11	ཅེས་	ces	ADV	ADV	_	65	advmod	_	particle_indicating_quotation;_thus|Sanskrit=ity-
12	བགྱི	bgyi	VERB	VERB	_	51	parataxis	_	do;_perform;_make;_act|Sanskrit=ucyate
13	།	/	PUNCT	PUNCT	_	65	punct	_	?
14	དེ་	de	DET	DET	_	68	det	_	that;_continuative_particle;_past_and_present_participal
15	སྐད་	skad	NOUN	NOUN	_	70	dobj	_	"voice,_sound,_utterance,_noise,_language,_speech,_words,_news,_dialect,_to_talk,_to_say,_to_proclaim,_to_sing,_to_cry,_to_shout"
16	ཅེས་	ces	ADV	ADV	_	70	advmod	_	particle_indicating_quotation;_thus|Sanskrit=evam-
17	གསོལ་པ་	gsol_pa	VERB.VerbForm=VerbalNoun	VERB	VerbForm=VerbalNoun	82	advcl	_
~~~

~~~ sdparse
Just some tokens
~~~

~~~ sdparse
Tokens/Noun with/Adpos POS/Noun
~~~

~~~ sdparse
A dependency
det(dependency, A)
~~~

<div class="sd-parse">
Alternative syntax
</div>

<div class="sd-parse" tabs="yes">
Dynamic visualization (click "edit!")
</div>

<div class="conllx-parse" tabs="yes">
1   CoNLL-X   CoNLL-X   NNP   _    _    2    NMOD    _    _
2   example   example   NN    _    _    0    ROOT    _    _
</div>

<div class="conllu-parse" tabs="yes">
1   CoNLL-U   CoNLL-U   NNP   _    _    2    nmod    _    _
2   example   example   NN    _    _    0    root    _    _
</div>

<div class="conllu-parse" tabs="yes">
# sentence-label S1
1   CoNLL-U   CoNLL-U   NNP   _    _    2    nmod    _    _
2   example   example   NN    _    _    0    root    _    _
</div>

<div class="ann-annotation" tabs="yes">
.ann annotation example
</div>

~~~ sdparse
Parse with errors
det(no-such, token)
~~~

Right-to-left text (Hebrew, SD format)

~~~ sdparse
דני/NOUN ראה/VERB סרט/NOUN
nsubj(ראה, דני)
dobj(ראה, סרט)
~~~

Same sentence in CoNLL-U:

~~~ conllu
1     דני       _        NOUN    _      _     2      nsubj _ _
2     ראה       _        VERB    _      _     0      root  _ _
3     סרט       _        NOUN    _      _     2      dobj  _ _
~~~

Arabic (CoNLL-U):

~~~ conllu
1     وَ       _        NOUN    _      _     2      nsubj _ _
2     لاحَظَ       _        VERB    _      _     0      root  _ _
3     التَقْرِيرُ       _        NOUN    _      _     2      dobj  _ _
~~~

----------
