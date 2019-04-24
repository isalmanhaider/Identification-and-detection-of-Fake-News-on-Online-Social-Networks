# Identification and detection of Fake News on Online Social Networks (in progress)
A research report on the Identification-and-detection-of-Fake-News-on-Online-Social-Networks

## Abstract
During the 2016 US presidential election, the phrase “fake news” found its way to the
forefront in news articles, tweets, and fiery online debates the world over after misleading and
untrue stories proliferated rapidly. Social networks are very useful and a focal part of our life and
day to day communication since they provide us with an ideal platform for keeping up to date
with the latest information, news, activities happening across the world based on our interests
and profiles we like/follow and people we add/follow. However, because of the openness and
freedom of speech social networks such as Twitter and Facebook are also proving to be a fertile
ground for spreading fake news and due to the mass of public that is connected on these social
networks enables the information to diffuse and reach a large number of people in a short span of
time. The spreading of fake news on social networks, especially in times of disaster, or on
matters involving national security brings unwanted effects on the lives of individuals and
societies. The main aim of this report is to understand the fake news problems, it’s possible
adverse effects on consumers and to determine the most common features of fake news on social
networks whether that is content of its propagation. The results of this study will, later on, be
used to find out improvements in the currently existing approaches or devise a brand new
strategy to combat the problem of fake news. We studied over 20 research papers on the
identification and detection of fake news on social networks and analyzed their approaches and
datasets used. We came to the conclusion that the approaches used for the identification of fake
news on social networks can be broadly divided into three main categories, listing the most
prominent aspects in each category i.e based on content, social context, and propagation.

## Introduction
The use of social networks has rapidly changed the way people communicate and access
news and information online. Social networks connect a large number of users distributed across
different regions all over the world, with Facebook alone having more than 2.23 billion MAUs.
Twitter with 335 million MAUs. Social networks like Twitter and Facebook provide a medium
which enables people to influence each other’s decisions on important issues such as health,
shopping, traveling, and professional concerns.

While social networks are mostly used for communicating, they are also being used to
share news on current affairs and other important information. Now more than ever, people rely
on social networks as a source of news. For example, at any point in time, 85% of the trending
topics on Twitter is related to news on current affairs. Unfortunately, there are people who
misuse social networks by spreading fake news, rumors and propagating misinformation.

Fake news is news whose context has been intentionally changed and manipulated in
order to influence the readers’ opinions on facts of the events taking place in the real world.

The problem addressed is the explosive growth of Fake news is news whose context has
been intentionally changed and manipulated in order to influence the readers’ opinions on facts
of the events taking place in the real world and its erosion to democracy, justice, and public trust.
As the quote says "Falsehood flies and the truth comes limping after it" and in this regard,
several algorithms and models have been proposed even a Fake News Challenge is conducted
every year for developing models and algorithms for the identification and eradication of fake
news on the internet. The best performing so far are CNN and RNN based models achieving an
unprecedented accuracy of 83.4%.

In order to track the spread of hoaxes a model was proposed by Tambuscio that uses the
following four parameters: spreading rate, gullibility, the probability to verify a hoax, and
forgetting one's current belief. Now on average, almost every organization employ social media
accounts on Twitter, Facebook, and Instagram for the purposes of announcing corporate
information such as earnings reports and new product releases to get maximum reach.
Consumers, investors, and other stakeholders take these news messages as seriously as they
would for any other mass media.

## Importance
The importance of this real life problem can assessed from this that even the World Economic Forum warned about “​digital wildfires” AKA fake news that will be one of the biggest threats faced by society. ​ If fake news can overturn US General Elections, or can break our a CHAOS or public RIOTS it can do harm of any nature to anyone and anything. It is a digital bacteria that can erupt and penetrate to thousands and millions of people across the globe within minutes. Would you put your life and thoughts gets polarised or hoaxed by fake news? This question isn’t difficult to answer. As confessed by CEO of Facebook, Mark Zuckerberg, himself, that during the 2016 US presidential election campaign 126 million American users on Facebook were shown Russian-backed, politically-oriented fake news stories solely for the purpose to hoaxed their thoughts. And this number exponentially increases when those users without verifying diffuse/share it further among their circles both online and offline as only internet users cannot accurately represent the demographics of the entire population. It will be highly beneficial and of great use, if there is a way to verify and validate news and bifurcate authentic and fake news. The information that people listen to and share in social media is largely influenced by their social circles and relationships they form online.

In addition, social media is vastly used for anti-social behaviors such as cyberbullying, propaganda, hate crimes, and for radicalization and recruitment of individuals into terrorist organizations, conservative and influential groups, etc which is very alarming for society.


## Types of Fake News
Broadly there are 5 types of misinformation that are weaponized into fake news.

<img src="https://raw.githubusercontent.com/isalmanhaider/Identification-and-detection-of-Fake-News-on-Online-Social-Networks/master/images/types-of-fakenews.jpeg" alt="Types of Fake News" max-width="640px">

### 1. Satire: When deceptively packaged as a legitimate news story.
Satire is different from fake news in that its purpose is to entertain or inspire consumers, rather than to deceive them through text writing or art designs/graphics. However because the contents are false even despite being entertainment-oriented in most cases and reveals its own deceptiveness to the consumes, some papers term satire as fake news. There are websites that utter a claim to be satirists but in contrast they do not admit or advertise openly themselves as satire, therefore suggesting an intent to deceive. An example of satire is America's finest news source, The Onion, that is known for Satirical news article. The Onion is an American satirical digital media company and newspaper organization that publishes articles on international, national, and local news bringing huge traffic of 200k per month.

### 2. Propaganda: When containing fabrications and packaged as a legitimate news story.
Propaganda is a kind of fake news that is misleading or highly biased information that is specifically well designed and diffused on the social network to confirm and promote a particular ideological viewpoint by the sender or party that initiates it. Propaganda is distinct from fake news in that it originates from politically motivated actors with the intention of driving public discussion, apart but not separate from financial and
ideological gain. It is not necessarily completely fabricated, and it is not always -- though most of the time -- designed to appear as legitimate news. Propaganda can be packaged as fake news, with the result is both (a) patently false and (b) designed to appear real.

### 3. Misleading or out-of-context information: When also serving as a support for fabrications.
Inaccurate or out-of-context information also know and style based that does not on its own constitute fake news. Fake news publishers often have malicious intent to spread distorted and misleading information and influence large of communities of consumers, requiring particular virality producing writing styles necessary to appeal and to persuade a wide scope of consumers that is not seen in normal generic true news articles. Style-based approaches try to detect fake news by capturing the punchlines and manipulators in the writing style of news content. Misleading or style-based methods can be categorised in two sub categories based on the intent i.e Deception-oriented and Objectivity-oriented.

### 4. Conspiracy theory: Whenpackagedasalegitimatenewsstory.
Social media provides a useful venue for disseminating conspiracy theories, and the sheer magnitude of groups publishing content inhibits users’ abilities to identify credible sources. Moreover, social media algorithms curate personalized news feeds based on users’ past “likes” and reported interests, creating echo chambers that amplify information, distort perceived consensus, and filter out alternative viewpoints. A conspiracy theory is an explanation or interpretation of events that is based on no solid proof, of unanswerable questions of a scripted plan by a group often governments and mainstream media outlets to obscure events. Conspiracy theories just like propaganda are almost and always completely fabricated in one or the other way, even if individual elements of the theories contain ​valuable​ facts, still can be presented as fake news when they are packaged as factual news stories.

### 5. Clickbait: When containing fabrications and packaged as a legitimate news story.
Articles that feature trending headlines designed with persuading words or phrases to get people to click on them, often by presenting a misleading or warped sense of what the post is about are called Clickbait. This does not necessarily constitute fake news, as these types of headlines or accompanying posts can be technically factually true (not fabricated) but nevertheless misleading. Fake news itself also often uses a clickbait format, particularly since its goal is to spread to the maximum number of consumers for ideological or financial gain. Clickbait headlines are often paired with fake news, as well as with content from hyperpartisan sites that contains misleading or out-of-context, but not necessarily fake, information.
