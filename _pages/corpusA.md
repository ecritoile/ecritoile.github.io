---
permalink: /corpusA/
title: "Corpus Assignment"
---

## Introduction

What if we could separate our work life and personal life? *Severance* is an American television show that takes this common desire and cranks the dial to eleven. The premise of *Severance* involves the development of a technology that has allowed this desire to be literally realized—workers can undergo the eponymous “severance” procedure to surgically separate their workplace and non-work memories, thus resulting in two separate personalities. The show follows Mark Scout, a severed worker who leads a team of other severed workers (Helly, Dylan, and Irving) in Lumon Industries’ Macrodata Refinement department. As questions arise concerning their workplace and severance, a thrilling journey in search of truths starts to unfold for Mark and the team.

Though the first season of *Severance* released in 2022, I watched the show for the first time earlier this year. I was immediately hooked. I found everything about the show, from the eccentric characters and the off-kilter workplace dynamics between them to the emerging questions of agency and neoliberalism, simply mesmerizing. I binged all nine episodes of the season in a few days and was beyond relieved to learn that Season 2 had just started being released weekly. As I eagerly await the next episode, I found myself drawn to the prospect of studying a corpus of Season 1’s subtitles. What kinds of findings can a distant reading of a show’s subtitles yield—especially when the show is one laden with subtlety and deception at every corner?

## Voyant Tools

I was able to track down the subtitle files for all nine episodes on Open Subtitles. A step that I had to take was converting the files from their native format of SRT to TXT, which was done with the aid of GoTranscript, a website I found online. I found it notable that though I was starting with digital material (transcript files), I still had to take care to ensure that it was in the proper format (.txt) before I could begin the study—I recognized this as a step of mediation, a fundamental activity of digital humanities research, As described by Johanna Drucker in the introductory chapter of *The Digital Humanities Coursebook*, “[b]orn-digital materials are also highly mediated and decisions about their formats are crucial to their use as well” (3).

I put the compiled folder of nine files—one for each episode—into Voyant Tools (processing), and this is what it showed me (presentation):

![Image 1](/assets/images/Corpus/c1.png "Image 1")

What I immediately realized from seeing the word cloud was that Voyant Tools seemed to reveal much less than it had done for the other corpuses we had tested in class. Even with the implementation of the default list of stopwords, the most frequent words in the corpus were: i'm (255); know (226); it's (226); just (200); okay (194). One can also spot the names of the main characters, like “Mark” and “Helly” in the word cloud. They were words that did little to reveal anything of interest; they were words used in conversations. This lack of immediate findings was due to the fact that the subtitles of the show consist entirely of dialogue. 

Though this is obvious in hindsight, it was a factor and characteristic that I hadn’t acknowledged or really been aware of prior. It was a moment in which I found myself reflecting about the unique nature of writing a screenplay—so much must be conveyed to the audience through the dialogue exchanged by and between characters, dialogue that must be at once expository and effusive yet believable and natural. Viewing the show only through its dialogue was in itself an enlightening experience.

I found the Summary tab to be a little more enlightening in the statistics it provided regarding the files:

![Image 2](/assets/images/Corpus/c2.png "Image 2")

As shown here, the first three episodes of the season are the longest in document length—though I was tempted to draw meaning from this, these stats actually coincide with the actual lengths of the episodes. Episodes 1 to 3 are all longer than 50 minutes, which makes them longer than the other six episodes (they are all 40-49 minutes). Instead, take a look at the Average Words Per Sentence statistic: it again lists the first three episodes as having the most words per sentence on average. I believe this to be a reflection of how there is more to be done in the earlier episodes of a show in terms of worldbuilding—this requires more exposition to be done through dialogue, thus resulting in wordier sentences. I also found it interesting that the first episode has the lowest vocabulary density despite being one of the longest episodes. I believe this also has to do with the pressing case of worldbuilding—certain words are repeated in the dialogue to build, label, and emphasize parts of the world of *Severance*.

The next thing I did was to add more stopwords in the hopes of narrowing the data down to more interesting terms. I added frequent words that I found to be less important (some examples are: i'm; know; it's; just; okay; yeah; like; right; oh; you're; sorry; think; that's). This is what the word cloud looked like after adding more than thirty terms to the stopword list:

<iframe style='width: 630px; height: 519.34px;' src='https://voyant-tools.org/tool/Cirrus/?stopList=keywords-0e72f3f0e64e96b023a9fdeb5f2cf565&whiteList=&visible=75&corpus=411ca7a332b564d5b3fd48d9d97bce61'></iframe>

The adjusted word cloud did look more interesting—for example, the frequency of character names seems to be a good indicator of the size of the role they play in the show. Mark, being the main character, is referred to the most (146). He is followed by Helly (79), with Dylan (47) and Irving (36) bringing up the rear of the quartet. This matches my experience with the show—the four members of the team have varying screen time, which corresponds with said differences in frequency.

Other important proper nouns seen here are Lumon, the name of the company that Mark works at, and Kier, the name of the founder of Lumon (it should be noted that Kier is not a character in the show—his descendents run Lumon, but he has been long gone). The frequency with which Lumon (50) and Kier (30) are referred to is indicative of their presence throughout the setting(s) of the show. I find this to be in direct connection with *Severance*’s messages on neoliberalism, especially about corporate control and its encroachment upon the private sphere of the individual. The frequency makes further sense given that Lumon employs cult-like practices in glorifying Lumon, deifying Kier, and indoctrinating its severed workers on its lore and myths. Characters are often seen quoting Kier, for instance.

Another interesting observation: I was curious about the difference in frequency between the words “innie” and “outie,” which are the respective terms used by characters in the show to refer to the “work life” and “personal/non-work life” portions of a severed individual. This was what a quick search showed:

![Image 4](/assets/images/Corpus/c4.png "Image 4")

Though the context varies, “outie” is usually spoken by innies and “innie” by outies. In other words, innies talk about their outies and vice versa. As shown above, the word “outie” is spoken much more often than “innie.” From this, it can be concluded that innies think and talk about their outies much more than outies do with innies. There is thus a comparable lack of acknowledgment concerning the existence of innies, much less their individuality and right to life—innies are aware (and continually told) that their existence predicates on their outie, while outies often regard innies as a simple means to an end, and as fundamentally lesser. This relationship is central to *Severance* and is a focal point of interest and debate—it is fascinating to see how it can also be observed through such distant reading.

## R

Shifting over to the RMarkdown notebook Identifying the Most Distinctive in Three (Sets) of Texts, I compiled and split the nine subtitle files into three texts: one of Episodes 1-3, one of 4-6, and one of 7-9 (I will refer to them as E1-3, E4-6, and E7-9 henceforth). I input these three text files into the notebook to compare the word usage proportions between texts. These are the graphs it yielded:

![Image 5](/assets/images/Corpus/c5.png "Image 5")

The two graphs show the word usage proportions of E4-6 and 7-9 to that of 1-3. The biggest observation that can be made here is that one can see which characters, themes, and set pieces become more or less prominent as the season progresses.

For example, “Burt,” the name of another character, can be seen in the bottom right quadrant for both graphs, meaning that he becomes more important in E4-6 (>0.30%) than he is in E1-3 (>0.05%), and only more so in E7-9 (>0.50%). This tracks, as Burt is first introduced in Episode 2 in a brief scene and only appears again from Episode 4. Burt’s main character arc has to do with his relationship with Irving—and as their relationship grows, so does the character’s prominence in the show.

Mark is in the top right quadrant for both graphs, meaning that he is referred to very often (only after “yeah,” it seems) and is thus important throughout the whole season. The node is on or near the line of equality for both graphs, which means that his importance as a character remains consistent throughout the show. He is the main character, after all.

One character that actually decreases in importance is Petey, as he makes a physical appearance in the show only from Episodes 1 to 3. His name can accordingly be found on the “left” side of the line of equality in the first graph, meaning that he is referred to less in E4-6 than E1-3. It only moves close to the y-axis in the second graph, which signals how his presence further fades.

A broader observation is that most characters are on the “right” side of the line of equality (even Mark is referred to more in E7-9). I believe that this signals not just the rising importance of individual characters but also the rising tensions and stakes of the overall plot, as characters increasingly develop and act on their purposes and desires.

An instance of a non-character word is “book,” which strays far from the line of equality in the second graph, meaning that the word is spoken much more often in E7-9 (~0.30%) than E1-3 (~0.03%). “Book” refers to an in-universe book named the “The You You Are,” a self-help book that has a profound impact on the innies and prompts them to ponder on their agency and individuality.

## Conclusion

Such is an attempt to investigate *Severance* by conducting a distant reading on its subtitles (its dialogue) by using Voyant Tools and R. The main obstacle I faced is the aforementioned difficulty I sensed when I saw the initial Voyant Tools page. Though I was able to somewhat work around it (by implementing more stopwords, for instance), it was a challenge to draw meaningful conclusions from conducting a distant reading on fully-dialogue texts. This difficulty was something I sensed in comparison to the exercises we had done using Gutenburg files—it can be concluded, then, that the type of the text is a major factor in how effective and useful a distant reading can be.

Despite such difficulties, I was able to find connections that made sense between the results and the show. The graphs made using the RMarkdown notebook were especially useful in tracking which characters became more or less important as the show progressed. There is, of course, caution to be taken in making such conclusions—a character being named more often does not necessarily correlate to their enlarged presence (especially physical) in the show, as names are called not by their owners but by others. The speaker and the receiver of the sentence containing the name must also be taken into consideration. Such details point to how making note of the context of the source material is crucial to accurately interpreting findings from a distant reading.

It is important to note that many of the observations I made were only possible because I had watched the show in its entirety and had an understanding of how its plot unfolded and characters grew. I do wonder what kinds of conclusions someone who has never seen the show before might draw—would they be able to see the same things I did? More interestingly, would they be able to see things I was unable to see due to my predetermined thoughts and biases? There is another point to be made here: the same statistics may lend themselves to completely different interpretations, and the nature of the interpretations can and will depend on the interpreter.

I initially considered this experiment not quite a failure, but a slight disappointment.I found the findings to be a bit underwhelming, especially in comparison to that of the exercises we had done. I have since thought of it in a new light and decided to think of this experiment without said comparison. The difficulties of conducting a distant reading on a show’s subtitles can be seen as its unique challenges rather than hindrances making it less fruitful. As written by digital humanities researchers Geoffrey Rockwell and Stefan Sinclair in *The Measured Words: How Computers Analyze Text*, “Interpretation can be informed by quantification . . . A summary of a book is useless if it doesn’t distinguish one book from another, and relative frequencies are one way to distinguish works” (41). This is precisely what I have done: I have simply substituted the “book” described here with an “episode” of *Severance* and used the emerging relative frequencies to distinguish between the episodes (using R, sets of 3 episodes) and form interpretations based on the present data (quantification) and my knowledge of the show.

Rockwell and Sinclar state that “embeddable analytic toys” such as Voyant Tools and R “don’t try to replace the human interpreter with an artificial interpreter . . . but rather give you ways of thinking through text” (42). In this way, this experiment is not a failure, or even a disappointment—indeed, I have been able to use these analytic tools to view, understand, and think about *Severance* in a completely new way. I daresay call it a success.

## Works Cited
- Drucker, Johanna. *The Digital Humanities Coursebook: An Introduction to Digital Methods for Research and Scholarship*. Routledge, 2021. 
- Rockwell, Geoffrey, and Stefan Sinclair. “The Measured Words: How Computers Analyze Text.” *Hermeneutica*, 2016, pp. 25–43.
- *Severance*. Created by Dan Erickson, Season 1, Episodes 1-9, Fifth Season, 2022.