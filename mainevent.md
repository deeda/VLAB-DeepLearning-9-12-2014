<img src="http://i.imgur.com/Vkmqwsd.jpg">

Panel intro:

Naveen Rao - Qualcomm pHD neuroscience - developed chips - building hardware solutions to building everything in deep learning 

Ilya Sutskever - Google Brain  

Elliot Turner - AlchemyAPI

Adam Berenzweig - Clarifai

Stever Jurvetson - Intro / moderator 

========

<h3>Adam - Clairifai</h3>

Can't talk about deep learning without talking about data. <br>
What happened when machine learning hit big data.<br>
* Data from physical world - pics - audio - sensors etc
* Data humans produce<br>

Search/sorting/computing statistics etc - used to be about all about data that was typed by humans - data entry 
starting with computers - everyone was producing data<br>
* all this data had to be filtered through the human brain 
* bridging the gap between recorded physical data to measurements of physical data and turn it into symbols and use it to search and sort<br>

For EX: 

   take an image and provide meaningful contextual tags/info<br>
   drags pic - shows tags based on the image of trees (pic of trees
   VW - auto - vehicle volkswagen mini transportation (pic of VW bug)
   kids - children- clown - circus - carnival (pic of his kid) 

Labels 
||||||
Hidden Variables
||||||
Features 

A component needs to be trained to get it to work properly 
Reward or Penalize weights in algorithm that get something right or wrong
Geoff Hinton and Yann LeCun - History of neural networks 
1980s - NN dark ages - getting beaten by other technologies 
Once GPUs and other algos hit - NN beat everything -- 2009 
   This allowed to look at more data, bigger models, faster iterations

<b>Deep learning error rates 2010 - 2014</b>

2010 - 2011 - not much - traditional CV - up 6o 70% error rate<br>
2012 - Deep learning jump to less than 20% error<br>
2013 - 2014 - all about Deep Learning - less than 7%<br> 

<b>Convolution Neural Network</b><br>

Convolution -> Pooling ... Fully Connected... Output Predictions<br>
Multiple layers of classification / analysis 

With Neural nets - and research that matt did as a phd - compare it to black box 
First layer of filters that were learned (image of multiple groupings of colors)
biological evolution and neural nets - lead to classifiers of modern NNs
	what the filters have learned
Showing - 9x9 grid of images 
	husky detector 
	start simple - get higher and higher levels of meaning 
What is it for?
	you what to show someone a pic - take phone out - start scrolling - cant 	find the image through all the images in your phone (not easily) occurs 	across many domains - shopping - stock photos - consumer photos - sat 	images - etc ------ auto tag and organize images without any work - 	easily find images by tags or images

Deep learning is forming a bridge between physical and technical world - take pic - buy, find, share, et 

Naveen 

CEO of Nervana Systems 

Approaching deep learning from the hardware angle 
Interesting things going on with computation 
Its a form of computation
nodes doing things in parallel is a different form classical computers 
instead of fixed mathematical outputs - fuzzy math - around probability etc
	for example how an animal computes something as good bad etc 
brain uses 20w of electricity - laptop uses 50w
not only have algos but also have tons of data - now can build hardware for it
now have use cases for scaling up 
	what did biology do to solve these processing problems 

Ilya 

Research Scientist - Google Brain

Deep learning is exciting because it actually works 
anytime you have a lot of input / output examples 
	object recognition - speech recognition 
very philosophically satisfying 
very simple ideas + very simple algorithms = very complex results 
	first year calculus and some basic stats etc lead to big results 
Big data is very important for all of this    
See lots of non-linear progress in the future 

Elliot 

Founder CEO - AlchemyAPI

Democratize Deep Learning
helping corporations solve business problems 
	care about the outcomes 
Cut his teeth on network intrusion detection systems in the 80s 
Think of things as an AI stack 
	capabilities build on capabilites  
	understand images and languages 
	then what questions you should be thinking about 

----------------------

<h1>Main Q/A</h1>
Steve - wondering in the longer run - does advantage shift to those with access to big data - consolidation vs empowering the small guy

Naveen: selling intelligence / skills - data enables machines to sell skills 

Steve: yes you sell machines to everyone - and you sell a platform stack - but in the future people don't  understand what or why things are happening in DL
Whoever has the most proprietary data gets the most benefit? 

Adam: yes more advantage if you have more data - but make partnerships of expertise vs data/needs --- how much data is enough? That might make a difference. Whats the size of the corpus needed for your specific domain needed to learn or make use of DL

Elliot: Seeing a real change - shift to automated systems to learn from data without human intervention - very different from Machine Learning or other data modeling - look at facebook for facial recognition - tried learning from a dataset of 1B faces - training with small dataset of similar faces out performed dataset of 1B faces 

Ilya - there will be many students who understand this technology and will eventually work or be able to work for anyone - cannot be consolidated in just a few companies - not a rational fear 

Steve: If you improve the general algos - if you make a breakthrough - do you think it would benefit other groups in DL?

Ilya: yes - great question - if you come up with an advance in NN - then all NN benefit - same for DL - yes - these algorithms are extremely fungible 

Naveen: never have I seen industry publish their work so publicly - Whats happening in DL is that Google etc is publishing all the greatest breakthroughs and helping advancing DL - that information is shared very readily - public brain trust 

Adam: yes, but this is partly to attract talent - you need the data and the talent - so there are plenty of things that google keeps secret but there are some thing that they readily share as well 

Steve: mimicking the brain - NN in the 80s - edge detection etc - question: Do you think technology will literally mimic the entire brain stack? Is that the way its just going to naturally go? If not, what does it lead to? Alien intelligence? 

Elliot: See a trend from human to unsupervised data analysis - its all about teasing out the structure from the natural world - we're not stuck with needing humans to teach. Cats, Dogs, houses, - what people find interesting - we created our first system / classifier without using labels or tagged data --- Scaling is the challenge for all the data is the challenge. 

Ilya: Difficult to predict how NN will evolve - hard to tell - have no idea how to do these things right now. If you look at our NN - 2 conceptual parts - the NN itself that does the computation - second is the learning principle - you can come up with more powerful computation and/or learning principles (how to train with minimal amount of intervention)   

Steve: are you saying there have not been big advances in unsupervised learning 

Ilya: every success story involves unsupervised learning algorithms that outperform every manual supervised learning algorithm Don't know how to come up with these learning principles - each advance will lead to unexpected advances. 

Steve: is this more important than computational architecture 

Ilya - most important is the algorithms - NN can learn a bit of computation - I think progress in the NN side will be the model for multiple non-linear and parallel computation

Naveen: It is interesting that we see these simple cell parallels but i think its just coincidental- silicon has so many properties that are so different from them mush in your head - on the behavioral level yes will look biological - but otherwise we have an artificial system that can do many interesting things - underlying structure will look very different from the human brain - but the behavior of the system will mimic the human experience  
  
Steve: Commercial applications - where is the money? 

Adam: What's the most familiar product you know or thing you know on the internet - you buy things - take pics - look up things on search engines - Clarifai approaching it from several angles - low hanging fruit:  Visual search similar to a pair of shoes you like - take a pic of a jacket and find it for me - or something that goes well with it. Labeling data is costly - replace this with auto-tagging 

Elliot: transform data to action - understand your customers - understand your market - should i trade my stock or close my boarder due to an illness. If you have a smartphone you're already using deep learning - speech translation into text. Transforming data into action. 

Ilya: speech recognition - important that we use it everyday but it needs to become  more accurate. Universal translation by machines to be able to communicate with anyone in the world. 

Naveen - can you make a more rich user experience in the end? Have to make people want it - have to make it sexy - I want my phone to learn my voice and pick out my voice - or my friends voice - all the things Ilya is describing - all these things that add features that make something more sexy. 

Steve: replace your personal assistant - vlab event - youre  always late by 10 min - better leave now - smarter calendar app etc 

Steve: Each of you give your advice to entrepreneurs and engineers - what would you recommend for DL - are there opportunities in data collection. 

Ilya - do as much as you can to become an expert. It is easy in the same sense as rocket science - the principles are easy to understand - the process of making it is hard - do the hard work to become an expert. 

Naveen - what are the benefits and what can I do to engineer a solution that helps a domain that I understand really well. 

Adam - easy to play around with this stuff these days. Learn how to program - learn CS - dont be afrraid to play around with it on a small scale. 

Elliot - play with the simple thing - if you're doing business then focus on the business fundamentals - then look to apply DL if it applies - but don't go looking for a way to plug DL into things that don't need it.  

Steve: there is something powerful about the biology that led you all to come here. What was that? 

Ilya - elegance of problem solving when learning it. 

Biology is such an important template for building artificial systems and CS building logic gates with dna etc - aurthor clarke - technology is indistinguishable from magic - quote
 
