# Faith

## Part 5

### Sonnet 66

Here is my favorite Shakespeare sonnet:

> ### $\Huge &#8220;$
> &ensp;&ensp; *Tired with all these, for restful death I cry,*</br>
> &ensp;&ensp; *As to behold desert a beggar born,*</br>
> &ensp;&ensp; *And needy nothing trimm'd in jollity,*</br>
> &ensp;&ensp; *And purest faith unhappily forsworn,*</br>
> &ensp;&ensp; *And gilded honour shamefully misplac'd,*</br>
> &ensp;&ensp; *And maiden virtue rudely strumpeted,*</br>
> &ensp;&ensp; *And right perfection wrongfully disgrac'd,*</br>
> &ensp;&ensp; *And strength by limping sway disabled,*</br>
> &ensp;&ensp; *And art made tongue-tied by authority,*</br>
> &ensp;&ensp; *And folly, doctor-like, controlling skill,*</br>
> &ensp;&ensp; *And simple truth miscall'd simplicity,*</br>
> &ensp;&ensp; *And captive good attending captain ill.*</br>
> &ensp;&ensp; *Tired with all these, from these would I be gone,*</br>
> &ensp;&ensp; *Save that, to die, I leave my love alone.*
> ### $\Huge &#8221;$
>
> &ensp;&ensp;&ensp;&ensp;&ensp; - Sonnet 66, Shakespeare.

> [!NOTE]
> ### Academia & medicine
> 
> The relevance of "Art made tongue-tied by authority and folly, doctor-like controlling skill" is impossible to communicate. It's no coincidence that "doctor-like" is the simile Shakespeare turned to, as that is the perfect description of the kind of authority he refers to, which governs, not just Chenliang's group, but most of the university, academia, and — most un-medically — medicine. 
>   
> My intuitive ideas, way ahead of their time, were often preemptively dismissed and disregarded, until I found the right phrasing and pictures for the faculty to teach and convince them, like the use of rewards from past actions to inform new actions in similar states, similarity as measurable by geometrical (Pythagorean) distance between datapoints or representations, decomposing datapoints into parts and relations, or efficient relational reasoning by prioritizing information relative to those parts. "Simple truth miscall'd simplicity."
>
> I proposed these fundamental insights, and what methods would correspond to them, while they were still original or before they had specialized appreciation:
>
> - (a) An agent "choosing" actions at first randomly in an environment, given "states" as input, remembering the actions chosen in a memory together with each state; then in future states, looking at those past actions, in memory, that corresponded to the most similar states to the current state, and taking the ones that got the highest environment rewards in the past, or, with some probability, exploring via taking random actions to get more state-action memory
>    - (relevant method examples: such as via K-nearest neighbors; symbolic and neural episodic control methods; parametrically rather than symbolically via RNNs or Decision Transformers),
> - (b) "similarity" as measurable by geometric distance between those numbers ("states") that represent input datapoints
>    - (relevant method examples: such as via Euclidean distance, cosine distance, parametric distance),
> - (c) decomposing those representations into representations of parts and relations
>   - (relevant method examples: such as via segmentation, parameter re-use inductive biases in neural networks like convolution, recurrence, attention, vector-quantization; or, more elementarily, weighted sums with non-linearities),
> - (d) efficient relational reasoning by prioritizing information for each part relative to each other part
>   - (relevant method examples: such as via MHDPA on vectors),
> - (e) representing each part with numbers that don't vary much for that part unless there are meaningful contextual changes
>   - (relevant method examples: such as with parameter re-use inductive biases in neural networks like convolution, recurrence, attention, vector-quantization; or gating; or frozen parameters of trained or symbolically-programmed encoders),
> - (f) training multiple such wisdoms in parallel to vote across each other and create a more general diversity
>   - (relevant method examples: such as via ensembling, evolutionary populations, and, more elementarily, mini-batches), and
> - (g) representing concepts more generally by learning across far more varied domains
>   - (relevant method examples: GATO).
>
> Each, individually or grouped, were dismissed by the faculty when they were still essentially mine (not always, but at least as the field of deep learning progressed, slowly), as I was repeatedly gaslit by my faculty listeners, with their authoritative rejection or suspicion, into doubting or tripping over my own far better understanding, as I tailored everything carefully to their understanding into symbolic methods or symbolic-neural hybrids, since most of them, initially, were skeptical of pure deep learning or thought deep learning was a fad.
>
> The CS department's faculty, with occasional exception, couldn't hear anything that they didn't want to, that they hadn't already internalized for multiple decades during their careers, that they weren't already clinically versed on, taught to them through their studies, normalized by their colleagues, and standardized, discussing "needy nothing trimm'd in jollity" while my ideas were "miscall'd simplicity" until they became mainstream, with credit for my teaching then "unhappily forsworn."
>
> As well as just simple intuitions that were pedagogically better:
> - (a) Randomness and diversity to escape local or "instantaneous" search limitations (local optima, myopia, e.g. myopic derivatives, and the process of searching/data-acquisition),
> - (b) gradients as directions of most increase, whose finger can point both opposite less error or forward towards more reward, the latter especially when differentiating an actor through a good differentiable predictor, or predictors, of immediate and any future outcomes, where "good" depends on the quality and quantity (perhaps prioritized for efficiency and exploration-sake) of memory/data learned-from and the outcome-goal(s),
> - (c) curriculum learning as prioritized experience replay, where data that there is most to learn from is prioritized for learning,
> - (d) learning rate schedules as exploration/exploitation tradeoffs,
> - (e) parameter-reuse methods for invariability and greater training diversity,
> - (f) training stability via incremental progress, as in small gradient steps, additive updates layer-wise, or diffusion, except not necessarily temporally,
> - (g) [more advanced math](https://github.com/slerman12/Teaching/blob/master/Other%20materials/Integrals.md) usually pertaining to calculus (non-instantaneity, bi-directionality, cross-derivatives), backprop as just an algorithm for taking a derivative, wherein the change that would hypothetically increase or decrease a function is disseminated, operation by operation, from the output back to the input, to each parameter in that function, 
> - (h) [LSTMs as biological neurons](https://drive.google.com/file/d/1i5hS2iDVuo24PnGicvn5dIZYXUzDfPAl/view?usp=share_link), and
> - (i) ["Convolution is all you need"](Ancillary/Conv-is-all-you-need.md).
>   - Quick rant, but worth reading:
>       - "Attention is all you need" sounds like a reply to "You just want attention." It’s in bad taste. That’s the name of the paper from DeepMind that most revolutionized deep learning after 2017. My later paper under Chenliang was going to be called, ["Relation is all you need,"](https://docs.google.com/presentation/d/1QbWNfnWAgm0rHTy4EFnDrjpaMP7Ako6isNxOUSR17_A/edit?usp=sharing) which brings the idea slightly closer to "Relationships are all you need" or John Lennon’s phrasing, "Love is all you need," and the method it uses is more algorithmically democratic (which is a good analogy, since governing systems are systems/algorithms for decision-making, meant to compose the knowlege and wisdom of smaller parts to that of larger collectives, relationally).
>         - I was rushing to make [this](https://docs.google.com/presentation/d/1QbWNfnWAgm0rHTy4EFnDrjpaMP7Ako6isNxOUSR17_A/edit?usp=sharing) into an ECCV, 2022 paper, because Chenliang said it makes him "sad" that almost no one in his group was submitting to ECCV, 2022. Solely out of love, I was about to rush another extremely fundamental new MHDPA innovation just because he ended that week's meeting, the week before the submission deadline, with "It makes me sad." I managed to run one experiment in time ([see here for code](https://github.com/slerman12/UnifiedMLold2/blob/master/Blocks/Architectures/LermanBlocks/ViRP.py)), and then resumed my regular work because I still had all of UnifiedML to build, and not even a tacit hint of dissatisfaction from Chenliang.
>         - He was the least-unappreciative of all of the CS faculty of my work, and that became more true than ever with each year he saw my thinking, efficiency, and work ethic, but just as quickly lost sight of that when he remembered my paper count, despite the fact that he was usually tolerant to my submitting fewer papers to conferences compared to his other students, actually, especially as he was pragmatically satisfied by my work under the Mechanical Engineering funding, and as he and the whole Computer Vision lab were largely really impressed and believed in the GATO-like UnifiedML framework I was building.
>           - Again, as Niaz said, "I don't know what he was thinking."
>       - "The attention mechanism as we propose it can be useful for everything deep learning is used for today." That’s what they should have called their paper. Man, there is so much stuff to man-splain to my fellow AI people. "Attention is all you need" might sound like a creative divergence from norm for an AI academic paper title, like they were trying to have a little fun with the naming, and no disrespect — I encourage that — but in the process of supervised learning, student AIs are provided with labels from a dataset, and "Relation is all you need" would’ve been a better name if the "all you need" structure must be used at all, especially since the "attention" mechanism’s primary usage (generally) is relational reasoning. Heck, "Relationships are all you need" would’ve actually been completely fitting as the paper title.
>           - ("Relation is all you need" would be sort of overfitting, but still better, since "Attention is all you need" has a loss term with really big mini-batch gradients). ("Overfitting" in AI means learning too hard from the training set, and "mini-batch gradients" are just fingers that point to how to be less wrong usually in proportion to how wrong you are; in this case, I might be pointing a little too hard, but in the context of Shakespeare, that would be the more poetic naming).
>       - "Attention is all you need" is the paper that proposed MHDPA, the method underlying most newer neural networks, including ChatGPT.
>         - The fundamental method for relational reasoning in big AI systems shouldn't be referencing a gaslighting association like "You just want attention" when a much better analogy exists. Or use the literal version: "The attention mechanism as we propose it can be useful for everything deep learning is used for today."
>
> I worked under Chenliang and the university's arbitrations as "captive good attending to captain evil," hard work, brilliance, love, and art crushed with interrogations, urgency, and criteria based on ridiculous standards where the quality of the work meant much less than how deeply in the weeds students went to claim "state of the art" in time for the latest conference deadline.
> - I achieved both repeatedly though. For example, my original MHDPA innovation paper in 2018 had to be an end-of-semester "project," and in a semester when I took other classes, and had to apply for the NSF GRFP (which I got a rare and esteemed ["honorable mention" for](https://anon.cs.rochester.edu/news-events/news/archive/2019/2019-04-10_lermannsf.html) with [excellent reviews](https://github.com/user-attachments/assets/87ef2c97-c1d5-4333-9247-a0d28a689efb)), and had my first psychosis, finishing the paper's submission-ready experiments in the hospital. Through unappreciated efforts that were side-tracked into less relevance.
>
> "And strength by limping sway disabled," as I limp, literally, to walk, from the eczema on my legs, as caused throughout my PhD by anxiety, and in my words, trying through repeated disappointing edits to describe the faith forsworn and right perfection disgrace'd while I was coerced, abused ("treated") (with hair loss, benzo gargling, clinical abuse, and more repeated hair losses), and worked there.
>
> ### Love & loneliness
>
> My mom told me the Russian translation of this sonnet translates the last line to mean, that there is somebody in the narrator's life, for him, for whom he still has reason to live.
>
> <p align='center'>"Tired with all these, from these would I be gone, save that, to die, I leave my love alone."</p>
>
> And that might be the interpretation, but I hear in Shakespeare's words that that's not the one he necessarily meant. My interpretation might end up even more controversial than this chapter of this book, really, since a lot of people perhaps want to interpret a romantic notion at the end (my mom knows Shakespeare didn't mean "my love" maternally). In my opinion, "my love" would be a pretty big thematic divergence and betrayal, if after every line (from "purest faith unhappily forsworn," to "maiden virtue rudely strumpeted," to "gilded honour shamefully misplac'd"), Shakespeare's meaning coalesced to, "Well, I could never do that to my girlfriend." Not to man-splain what Shakespeare meant ($\text{\color{green}"sam-splaining" is a distinct form}$), but this is what I think Shakespeare meant:
>
> The narrator referred to himself as a "beggar born," and he cries for death so as to behold himself "desert" from himself, meaning to "leave" himself (to die) and "leave" all of the tragedies listed thereafter. The last line is exactly parallel to this in meaning. He refers to his love: "I leave *my* love" — his literal, un-metaphorical love — "alone." To leave his love is leaving his body. It's leaving his skin. It's leaving his emotion. When a person dies, they don't just leave their life. They leave the constellations of beauty inside them, including all of their love, potentially in lonely isolation. One could even interpret, instead of leaving alone, he'd rather take you all with him. Perhaps the simplest possible interpretation of the word "love" will be called "simplicity" by academics. The un-metaphorical meaning, the literal one — love — is the meaning I think Shakespeare most meant.
>
> This sonnet expresses a tragedy, of someone who has so much love and passion — and it's wasted.
>
> Another interpretation is that his love is tied to a soulmate who he is separated from. I like that interpretation, too, but that would be a fast thematic divergence from the rest of the sonnet.
>
> Every other interpretation, besides this literal one, is wrong in some way that I can specify if they're listed. In short, they diverge from the commentary of the sonnet and undermine the narrator's struggle.

### Friends

> Date: **10/29/23**

[name redacted] messages.

### Allies

Message about preferring to die than legal action

> Date: **10/30/23**

Screenshot

I almost said "It makes me want to die" in the [mass email of 10/30/23](https://github.com/slerman12/BrokenWisdoms/blob/main/3-Disproof.md#email-10302023). Thankfully a friend in a group chat of several people suggested otherwise, or else the University of Rochester might’ve been responsible for doing another coerced hospitalization of me, and a repeat of the cycle of unforeseen consequences from involuntary interventions on me. Either way, however, they could have *plausibly* been responsible for a student and worker's suicide.

> Date: **10/30/23**

Screenshot

### Enemies

Rewind to August, before the six-month review deadline and after I was notified of my stipend and advisor-cut. I took my best friend into this, asking for his advice on an email that I sent, and stating my plans (or lackthereof) regarding legal action:

> Date: **08/06/23**

<img width="150" src="https://github.com/slerman12/Detective-Sam/assets/9126603/d59745f2-cf66-44c3-8cd0-b8faa2ae1cda">

</br>We were discussing [this email (of 08/10/23)](Ancillary/Not-Enough-Carbs.md).

I sent them this email exactly as I showed my friend. That was the best I was able to phrase everything (for whatever reason, perhaps due to revisiting the trauma, my consciousness and my corresponding linguistics weren't in the best state). All of what had gone on was conveyed to them as early as the beginning of August, at least as much as could be summarized in less than a book. Following which, here is how my best friend and I discussed it afterwards:

Screenshots

# Synchronicities

Meanwhile, before and after, astonishing [synchronicities](https://en.wikipedia.org/wiki/Synchronicity) happened that can be listed below and I leave for your judgement on their metaphysical or coincidental nature.

### Chris Kanan (Deus ex memory)

- Indeed, my faith regarding sending my sincere description of the traumas, despite the difficulty of doing so, was somewhat rewarded, though probably not by their conscious intent, rather by a lucky ["Deus Ex Memory"](Ancillary/Deus-Ex-Memory.md), wherein one of the 3 committee members (accidentally) recorded to official record that he really-extraordinarily didn’t remember the details of the meeting on which their termination was based.
- Following this ["Deus Ex Memory"](Ancillary/Deus-Ex-Memory.md) exchange with Chris Kanan, I had yet another reply I wanted to send afterwards that would’ve ruined the conclusive punctuation of the previous, and by chance my internet went down or some disruption to the internet happened after hitting send and I was really lucky that it didn’t go through, leaving this exchange on the note of "we all know what just happened," and a strong discredit to the committee's judgement-making, thoughtfulness, and memory.
- This is the same Chris Kanan who gave the [one and only concrete research suggestion](), which I ended up following [exceptionally and on proven GitHub record]() before the termination decisions, and didn't just get no credit, but also the judgement that I "refused to follow" committee advice as the justification for the termination decision, despite the advice being disproportionately hard and intense ("invent a new RL systems algorithm before the next meeting", [paraphrasing]()), and having done it quite extraordinarily really via a novel accelerated parallel priority experience replay with sampling-without-replacement algorithm with memory-mapping, and truly-shared RAM. There was nothing like it, still isn’t, and it’s by far the best RL implementation of experience replay and adjacent sampling algorithms, as well as being novel as an algorithm itself via the sampling-without-replacement, which I described to my advisor’s satisfaction in literally the meeting in which he next notified me of my stipend and advisor-cut, since that was his intent for the meeting.
- The theme of memory is a big coincidence in itself since what I implemented was a large-scale, dynamically growable, rewritable, truly shared RAM and adaptive memory-mapping across devices parallelized lifelong replay memory. [TO DO: Stress this way more]
- I never met Chris Kanan in person and my advisor suggested him as one of the last-minute replacement committee members. Note: I don't think he should be punished for this. I think whatever powers-that-be that regulate his consciousness proved stronger than the ones that facilitate the atmosphere/landscape of the formal University of Rochester, and did good amid impossible programming.

### Jordan Peterson

My benzo trauma was with a [comparatively](https://www.mdcalc.com/calc/10091/benzodiazepine-conversion-calculator) higher dose than what Jordan Peterson took (he took approximately 12% - 80% the dose I did, and that's when I was taking them at the lowest dose the psychiatrists had reduced to), and preceded the situation Mikhaila Peterson, his daughter, described ([originally on her channel](https://youtu.be/laheAXdZK7w)), about how the professional psychoanalyst was caught off guard by the severe damages that the drugs caused, wherein he took [0.5 mg](https://ashnavabi.com/2022/01/19/jordan-peterson-was-not-addicted-to-benzos/) of [Clonazepam](https://windwardway.com/rehab-blog/jordan-peterson-finishes-lengthy-treatment-for-addiction/) per day as prescribed, reportedly, and unlike him I didn’t have the entire Russian army brigade bringing me into health (he went to Russia, where they were the first to have the medicine and specialized treatment to help him).

### Mikhaila Peterson

Prior to that, by coincidence, his daughter Mikhaila (thankfully) recommended the steak-only diet (for an independent thing), which is where I heard it from, a clip from her podcast. That’s a global-level synchronicity involving them that happened after I was put through all of this crisis, which contributed to bringing me out, as well as my hair growing back, thanks to her diet recommendation.

### Timing of benzodiazepine coercion [diagram](https://github.com/slerman12/Detective-Sam/assets/9126603/497f6d9b-ff12-4e6a-97c5-e5230c05e505)

I finished making this [benzo-timeline diagram](https://github.com/slerman12/Detective-Sam/assets/9126603/497f6d9b-ff12-4e6a-97c5-e5230c05e505) just as Pink Floyd's [Comfortably Numb](https://youtu.be/_FrOQC-zEog?si=riY-TNigVjimQ_iT) started playing on my Spotify's radio on shuffle, a song about a doctor taking a patient named "Pink"'s soul through "medicines" meant to help him. The next song was Psycho Killer which I'll interpret as psychiatric killer. Oh and then Alabama  Song (Whisky Bar). Not bad. Rgearding Whiskey Bar, any song about alcohol is fitting for the topic of benzos, since they both work by GABA as the mechanism of action. In fact, I introduced a fellow hospital-inmate Lily to Elliott Smith for the first time in the hospital with the song [Between the Bars](https://youtu.be/2FmYzACF-kg?si=DLaBako9OolIYuVx) (about alcohol... not about Xanax bars, though Xanax is another benzo and "bars" is the colloquially and sometimes clinically used term for pills of them) while we were in the hospital (linguistically like: between the bars of confinement). It was the only song I thought to show her in the one situation when we were allowed to pick our own music, and she remembered and liked it. Also coincidentally, she was keeping a synchronicity list while we were there. While some of these are clearly just linguistic, the timing of [Comfortably Numb](https://youtu.be/_FrOQC-zEog?si=riY-TNigVjimQ_iT) and the next two songs seems worth noting since many people, like Lily and myself, appreciate synchronicities. Two more: (1) speaking of timing, the [diagram](https://github.com/slerman12/Detective-Sam/assets/9126603/497f6d9b-ff12-4e6a-97c5-e5230c05e505) is about a chronology (not of songs, but of benzo trauma), and (2) Lily’s last name is phonetically pronounced "Jung," the depth psychologist who coined synchronicities.

### CMT deletion of record

CMT (the portal that was used to submit to the "NIPS" 2018 conference, today called NeurIPS) deleted their record of my MHDPA innovation paper, the one that foretold ChatGPT to my university's professors (or tried to), the same month when I was terminated (CMT’s deleting of that record at around that time can be verified, since they sent out a notification email on 10/20/23 to everybody that they were updating their data retention policy). But in 2018, the paper was sent out to Henry Kautz and Daniel Gildea by email, and submitted to the class as that class’s end of semester project also via email. So the digital record does remain to verify the paper and its being written in 2018 with the first initial successful experiments, and email record of Henry and Dan's respective advice on how to mathematically or linguistically describe MHDPA, claiming more math was needed and that "relational reasoning" is the wrong term (though what I had and stuck with is now the convention, and already had some precedent then). That’s not to insult Henry or Dan. There’s also clear record that, most deep learning and natural language processing researchers, even outside of the University of Rochester, [weren't too abundantly "foretelling" of MHDPA's importance](https://scholar.google.com/scholar?q=mhdpa&hl=en&as_sdt=0%2C33&as_ylo=2017&as_yhi=2018) (the link is to two papers that were, the earliest papers to use MHDPA at all, also from 2018, and others that just directly referenced it) at the time of my paper. Both of those two papers used MHDPA for something fundamentally new, but neither innovated directly on MHDPA, meaning mine was probably the first to do so, ever. While I was finishing up the code for my MHDPA innovation in Montreal during NeurIPS (called "NIPS" at the time) 2018, I met one of the authors of [one of those two papers](https://proceedings.neurips.cc/paper/2018/hash/e2eabaf96372e20a9e3d4b5f83723a61-Abstract.html), Ryan Faulkner, and we got lunch and he said he'd recommend me to a position at DeepMind (he was miraculously impressed with me). 

And not only foretold to my university's professors, but innovated on and executed successful experiments verifying the early innovation — and formal paper submission, later derailed by me having to switch advisors, fields, and put on deadlines, not to mention all of their doubt, skepticism, and lack of enthsuiasm (oh but enthusiasm came later when MHDPA exploded, with Henry even telling me on email record, after he was no longer my advisor, that I should work on vision transformers!).

### Sam "Altman"

The head of OpenAI, the company that invented ChatGPT (that used MHDPA), whose name is "Sam Altman" (mine is Sam Lerman) — "Altman," which is not German Ashkenazi for "teacher" — was terminated as the head of OpenAI in an unusually sensationalized situation exactly 17 days after my termination as PhD student, just in time for my birthday (exactly one day before), then was brought back.

They were working on some AGI project called Q*, and the synchronicity may have been meant to give me hope, but [it didn't](https://github.com/animal-tree/SuspiciousnessofSynchronicitiesAndParanoia/blob/main/Synchronicity-Paranoias.md).

### Michael Scott’s paper factory

Michael’s name [is mockable](https://youtu.be/ZPKdJGY0YyE?si=ja-odwAD_z7G98ZK) (that links to a story arc from The Office, where the main character, Michael Scott, starts his own paper company, much like the academic factory that I was being pressured to publish faster in, except regular papers). 

But from the age of three and two thirds, until 11th grade, as a result of the Uzbek mistranslation when we moved, mine used to be much more mockable. 

As I described to my friend: 

> ### $\Huge &#8220;$
> These quotes express that I am writing something, but i am aware that this writing is in quotes. Therefore do the quotes bias their own measurement of what is being written? I think so. Lest this paragraph thus far would not be entirely about the quotes.
>
> Anyway, I'm thinking about "Sam" - the name. Did you know, \<friend's name\>, (okay apparently this is a targeted-audience writing-prompt), that my name was Semen until 11th grade? This is new information to you as far as I can recall, but a major part of the story of my life. "story" sounds pretentious and there I go with the quotes again. 
>
> Yes, my name was legitimately, legally "Semen". From the age of 3ish/4 to 11th grade. And every bully and teacher and substitute teacher knew it. No one told me I could get a lawyer let alone a lawyer would do the process of changing the name for free! My mom to this day thinks it wouldn't have been possible before 11th grade, for free anyway. And we were poor. Lower-lower class poor. 
> 
> Maybe a lawyer and court would've sympathized with a kid wanting to change his name from "Semen", maybe not. But of course, it shaped me. Into being the odd weird "semen" that I am today. In actuality, my name is Seamón<sup>$\text{\color{green}[1.]}$</sup> or Soema, or the Americanized: Sim'on or Shimon<sup>$\text{\color{green}[2.]}$</sup>. In Hebrew these names mean wisdom. In the Kabbalistic teachings, two types of wisdom: seeing as the complement to hearing, hearing as the complement to seeing. I think I mentioned this already. I won't rehash but something something new paragraph.
>
> Anyway, I like Sam. Because Sam in all the fantasies and mythos' of modern time means "innocence." "Samwell", "Samwise", "Sam". It means "this person has a wisdom, but from the good of his heart, not his intelligence." It means "this person is naive, but he has a good heart." I like the name Sam. "Shimon" means "this person is wise through his intelligence." It's true, but it's not me all the time as you know. I like "Sam" though.
> ### $\Huge &#8221;$

$\text{\color{green}[1.]:}$ I think "Siímyon" might be the best spelling.

$\text{\color{green}[2.]:}$ My Rabbi, who I hadn't met before 2022, actually told me this. He designated me as "Shimon," and told me that "Shimon" means "to hear" in Kabbalistic teachings. In Kabbalistic teachings, "to hear" is the complement to "to see." It's the second way of knowing. To hear is to understand, it's to fine out the meaning from the varied knowings, whereas "to see" is to know — it’s the sense or awareness of truth; no teaching needed. My mom being a music theory professor in Samarkand when I was born, I find it meaningful if this was my birth name, though really it had nothing to do with the Kabbalistic interpretation. My great-aunt’s late husband was named Siímyon. When my kindergarten teacher truncated my mistranslated name to "Sem," it became "Sam," which is also synchronistic to where I was born, Samarkand. 

### "Life ruined" post, entire-forum being deleted 5 months after I emailed it to the faculty/administrators 

Description [after having shown it to Niaz who commented in person about it (and to faculty/administrators), and writing BrokenWisdoms as a result of the depression and fear that came from losing my only description of those events, one I hadn’t backed up anywhere, with comments from others about having experienced similar things, the trauma of benzodiazepine addiction/coercion, and expressing extreme sympathy, and it was the top post in that for 4-ish years running]

### House on May St. 

Description
