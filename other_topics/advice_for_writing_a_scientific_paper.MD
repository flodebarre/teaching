## Advice on writing a scientific paper (in academia)

Writing the Methods section is easiest: it’s just what you’ve done (made accessible to others). For that reason I’ve heard it recommended as a starting point - to get your foot in. However, grappling with constructing a narrative for your work may make you realise that part of what you’ve done is unnecessary, or that something you haven’t done is necessary, or that it would be better to split into several papers. So I think it’s better to work on the big picture before diving into easy details.

Start by getting as clear as you can in your head about what question your work addresses.
* Anecdotally, I find a fairly common structure in talks (less so papers) is
  * Introduction to the general area of study,
  * What you did, in detail,
  * What the result of doing that was,
  * Speculation as to why that might be of interest to the general area.
* That’s not a compelling structure, because as one follows, it’s less clear why you’re doing what you’re doing. Starting with a question, and explaining (if not self-evident) why that question matters, means people are either hooked from then onwards or they realise as early as possible that what you’ve done isn’t relevant for them.
* The question you present is not necessarily the same question that you set out to answer: there's nothing wrong with finding some result and then realising afterwards that it answers someone else’s important question. And you might want to revisit the question you started with depending what you found, e.g. restrict the scope if you realise there are problems with generalisability.
* I feel (I am perhaps biased) that an exception to this question-focussed approach is when you discover a thing that exists (or existed) that wasn’t known to exist, e.g. a [viral variant](https://www.beehive.ox.ac.uk/hiv-lineage) with certain properties, or a volcano, or an ancient language. There’s not necessarily an obvious question preceding such findings. One could try to shoehorn any finding into this exception, e.g. “I discovered that there exists a statistically significant correlation between variables x and y in my data,” but the fact that you could do something doesn't mean you should. Generally, people are interested in what you find in your data only to the extent that we can generalise from it to something bigger. Which means e.g. considering whether the data you started with was a good thing to start with for the question in hand. So it's better not to shoehorn but to challenge oneself to construct a question to which one’s findings provide a reasonable answer (such as does actionable thing X cause desirable outcome Y).

Plan what you are going to write, and make sure you understand what you have already written, at the level of paragraphs.
Each paragraph should
* collect sentences that are related to each other with an easily definable theme
* avoid repeating something from a previous paragraph (unless this is intentional for emphasis, especially between Discussion and Results),
* come in a coherent flow of ideas from one paragraph to the next.

To ensure that your writing is structured at the level of paragraphs, maintain a list of very short bullet points saying what the main point of each paragraph is.
You'll need to keep that list in sync with the actual paragraphs as you write them - switching between modifying the structure and modifying the actual text until the two things match each other and the plan matches the structure you want.
Depending on what mood you're currently in, it can be better to plan your structure (big-picture thinking) or craft text to match your desired structure (fleshing out details).
Keep that plan visible when you share your draft with co-authors: it's helpful for them to see at a glance what your structure is supposed to be, instead of them each needing to figure it out.
If you start the writing process by creating a draft of this list, that’s a great point at which to get early feedback from co-authors, because the whole point and structure of the paper is clear at a glance and can easily be turned into something different with minimal wasted writing.

As an example of the previous paragraph, I might start by writing this paragraph structure for my Discussion section:  
1. summary: what we did, what we found, how we interpret that finding  
2. refer to previous studies  
3. limitation: non-representative data limits generalisability  
4. limitation: demonstrated correlation not causation  
5. outlook, what should (some) people do now in light of this result
  
I might show this to a coauthor who can tell me immediately that our data is much more representative that I thought, so there's no need to write paragraph 4.
Then I might start to write the actual paragraphs and realise there's so much to say on intepretation that a whole paragraph would be better, in which we should talk about novelty, because interpretation and novelty both help people understand why they should care about this result.
So I'd revise my structure to

1. summary of what we did and what we found  
2. why care: how we interpret that finding and why it's novel  
3. refer to previous studies  
4. limitation: correlation not causation  
5. outlook, what should (some) people do now in light of this result

(Variations on the above structures generally work well for the results section of a results-focussed paper; adjustment is needed for a methods-focussed paper.) 

Another example: I might take a section of my paper that I already wrote without an explicit structure accompanying it, and then try to write such a list to match what I've already written.
As a result I might identify some problems with my existing structure, e.g. one paragraph without an easily identifiable theme, or one point repeated in multiple paragraphs when those sentences would be better collected together.
I would then move around sentences (or delete them) until the text has a sensible paragraph structure.

Having an explicit written list for what the paragraph structure is will help you and your coauthors write text with good structure.
Of course you won't include that list with the actual final text, and so your broad readership won't see quite so easily what the paragraph structure is.
To help them, try to make the opening sentence of each paragraph indicate what the rest of the rest of the paragraph will be about.

The Introduction section should have a roughly funnel structure from broad to specific, ending with an explanation of what you set out to do in this paper: “Here, we...“. I read somewhere, and agree, that the funnel should be such that the closing bit about your work should feel inevitable - you’ve drawn the reader towards your question feeling like the natural thing to work on. In the best case you have provided something completely novel, in which case immediately before your “Here, we...” is an explanation of how no one has looked at this problem before. Normally your result is more incremental, and you can say that uncertainty remains on this particular aspect of a phenomenon, or that the problem is so important that further studies are useful to validate existing results. An example funnel:
* one paragraph on the English SARS-CoV-2 epidemic
* one paragraph on contact tracing
* one paragraph on digital contact tracing
* one paragraph on previous studies of digital contact tracing, mentioning absence of empirical estimates of epidemiological impact
* “Here, we empirically estimated the epidemiological impact of the NHS COVID-19 app. We do this by [very brief summary]”

What I look for in every presentation or paper is what should people do differently as a result of what you’ve found. For a methods paper, it’s normally to use that method instead of the best previous alternative for this particular application. For applied results papers, it might be that doctors/society should consider using more X to get more of desirable outcome Y, or at least that further study should establish your X-Y link more concretely and explore feasibility, cost-effectiveness etc. For theoretical results papers, it might be that other researchers should investigate your new idea because it has the potential to help us understand something which is manifestly important. For a convincing negative result - enough data for statistical power, appropriate kind of data & method for accuracy and generalisability - the implication might be that people should stop pursuing an avenue previously thought to be promising. There are lots of possibilities for how your finding might influence some people, but if you struggle to think concretely of who and how, it’s worth having a frank conversation with yourself about whether your paper was a good use of your time. No use crying over spilt milk of course, but one can strive to not keep spilling milk forever. (This was a big factor in why I stopped working on theoretical particle physics.)

Tenses: I like past tense for Methods and Results, present (or future) tense for Discussion.
Paraphrasing an explanation I was given: mathematicians and physicists favour the present tense for results because there is a feel of timelessness to the findings.
However, in biomedical research, different findings are fairly often in some tension with each other; a single finding is just a higher level of a single observation within a study.  
Methods: We *regressed* y against x.  
Results: We *found* a correlation.  
Discussion: We *interpret* this as evidence that x *causes* y, given the assumed absense of confounders.

And use the active tense for what you did (*We did X*); recommendations to use the passive tense (*X was done*) to sound more netural are so last century.
I read somewhere that the active tense reminds the reader that the steps taken were made by fallible humans, not by some idealised notion of the scientific process.
