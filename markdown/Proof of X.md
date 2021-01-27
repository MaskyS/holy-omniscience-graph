- **metadata**
    - [[type]]: #article
    - Author: [[Julian Lehr]]
    - [url](https://julian.digital/2020/08/06/proof-of-x/)
- ## Intro
    - Sparked by [an interesting Twitter discussion](https://twitter.com/dwr/status/1273307320911450112), I’ve spent a lot of time recently thinking about different proof-of-work mechanisms.
    - When I say proof-of-work, I’m not talking about consensus algorithms like the ones that some crypto currencies use. I’m talking about social networks.
    - At their core, social networks are primarily about one thing: Building social capital through signaling. As I wrote in [Signaling as a Service](http://julian.digital/2020/03/28/signaling-as-a-service/), signaling can be broken down into three different components:
        - **Signaling Message**
            - A hidden status subtext you’re trying to convey about yourself
        - **Signaling Distribution**
            - The channel through which you’re communicating your signaling message
        - **Signaling Amplification**
            - Ways to boost your signaling message to compete against status rivals
    - For example: A Patagonia vest signals both a prosocial attitude (__“I care about the environment__“) as well as wealth (“__I can afford to spend $500 on a jacket__“). Depending on where you live, it might also signal something about [your occupation](https://vcstarterkit.com/).
        - ![](https://julian.digital/wp-content/uploads/2020/07/patagucci.png)
    - In order to signal these messages to others and build actual social capital you need a signaling distribution channel. One option would be to wear the vest in public where others can see it – but there are obvious physical constraints to the size of the audience you’d be able to reach.
    - This is where social networks come in.
    - Their primary role is to distribute signaling messages at scale and transform them into quantifiable social capital (in the form of likes and followers).
    - As social networks grow, they increase the potential reach of your signaling messages – but they also get crowded with status rivals. This is why social networks typically provide you with a set of signaling amplification tools. These tools help you boost your signaling messages and stand out from the crowd.
    - In [Signaling as a Service](http://julian.digital/2020/03/28/signaling-as-a-service/) I compared signaling amplification to [[Eugene Wei]]’s [idea of proof-of-work hurdles](https://www.eugenewei.com/blog/2019/2/19/status-as-a-service), which he describes as follows:
        - > Almost every social network of note had an early signature proof of work hurdle. 

For Facebook it was posting some witty text-based status update. For Instagram, it was posting an interesting square photo. For Vine, an entertaining 6-second video. For Twitter, it was writing an amusing bit of text of 140 characters or fewer. Pinterest? Pinning a compelling photo. You can likely derive the proof of work for other networks like Quora and Reddit and Twitch and so on. 

Successful social networks don’t pose trick questions at the start, it’s usually clear what they want from you.
    - But the more I think about it, the less I like the comparison. I actually think that Eugene’s proof-of-work theory only scratches the surface of what social networks actually do. Let me explain.
- ## A closer look at proof mechanisms
    - Take a look at this very cliché Instagram picture. The photographer clearly put a lot of thought and effort into its composition and applied different filters and editing tools to make it look nicer.
        - ![Full disclosure: I actually took this picture from Unsplash. No influencers were harmed during the production of this blog post.](https://julian.digital/wp-content/uploads/2020/08/creativework.png)
    - It’s a perfect example of Eugene’s definition of proof-of-work.
Proof-of-**__creative__**-work, to be more exact.
    - Editing your photo helps to amplify your signaling message and sets you apart within Instagram’s status arena (aka the newsfeed). It also adds additional signaling messages to your post: __“Look how great a photographer I am”__ or __“I’m a creative person”__.
    - But those are not the main signaling messages you are communicating 
here. What you really want to tell your followers with this photo is something along the lines of __“I’m a world-traveler”__ and __“I’m in a happy relationship”__ (which in turn are also just signaling proxies for wealth and mating worthiness).
    - The photo and the location tag are your proof points.
    - ![](https://julian.digital/wp-content/uploads/2020/07/igexample02-1.png)
        - ((If you look closely, you’ll notice additional hidden signaling messages in the form of Allbirds sneakers and what’s most likely a Patagonia vest → proof-of-ownership))
    - Social networks are therefore not only signaling distribution (and 
amplification) networks – they also allow users to prove their signaling
 messages.
    - The creative proof-of-work is just pretext and helps to boost your post. What’s more important are the additional proof mechanisms that social networks provide. In the case of Instagram those are photos and location tags.
    - Instagram is essentially “pics or it didn’t happen”-as-a-service.
- ## Implications for new social networks
    - When new social networks emerge they have to introduce new proof 
mechanisms to differentiate themselves from existing incumbents. These 
can either be novel proof-of-creative-work hurdles or completely new 
proof-of-x mechanisms.
    - TikTok is a good example for proof-of-__creative__-work innovation. The app provides creators with a powerful set of video editing tools that have opened a whole new level of creativity.
    - The cost to participate in TikTok’s status game is a lot higher than Instagram’s (compare a well-made dance choreography on TikTok to your median Instagram travel post) – but its powerful feed algorithms also make discovery easier and thus reward users faster and with more social capital.
    - TikTok doesn’t add any new proof points beyond its novel creative work hurdle though. You can signal and prove your creativity but you could achieve the same by uploading your video to Instagram.
    - Strava, on the other hand, introduced an entirely new proof mechanism: Proof-of-physical-activity. By using your phone’s GPS sensor (or a 3rd-party fitness tracker), users can actually prove how much and fast they ran or cycled. In contrast to [Instagram](https://www.telegraph.co.uk/news/2017/10/20/grounded-private-jet-hire-helps-russians-fake-lavish-lifestyles/) [photos](https://www.vice.com/da/article/wdaqgw/instagrams-ballers-discount-private-jets-324), Strava’s proof mechanism is a lot harder to fake (though there are [exceptions](https://www.google.com/search?q=fake+strava+5k+downhill&oq=fake+strava+5k+downhill)).
    - ![](https://julian.digital/wp-content/uploads/2020/08/stravaproof.png)
    - What’s great about Strava is that it reinforces a behavior that’s actually good for you: While the status game that initially got you into the app might be zero sum, the actual physical exercise you have to put in to compete has a very positive, compounding effect.
    - The question is: What other social networks should we build that could have similar positive feedback loops? And what are their proof mechanisms?
- ## Strava for X
    - Let’s start with the two examples in [this tweet](https://twitter.com/dwr/status/1273307320911450112).
    - ![](https://julian.digital/wp-content/uploads/2020/08/tweetstrava.png)
    - I love the idea of a **Strava for Cooking** – but I’m very skeptical that it can be built. Why? Because the necessary proof mechanisms don’t exist.
        - The primary metric you optimize on when cooking is taste. But how would you measure or quantify taste? The closest proxy to taste that we have is optics: How good does the meal that you cooked look? This can easily be proved with a photo .. but that’s a proof-of-work mechanism that Instagram already offers (including filters to make your food look nicer). As long as no one comes up with a better proof mechanism for cooking, I think it’s unlikely that we will see a successful social network in the space.
    - I’m more optimistic about **Strava for Learning**.
        - While the activity of learning itself might be hard to quantify, you 
can measure the outcome of learning: knowledge. Has anyone built a  multiplayer version of [Anki](https://apps.ankiweb.net/) yet? Flash cards would be a perfect proof-of-knowledge mechanism and could easily be turned into a game where you compete against friends.
    - Similar to physical activity in the Strava example, learning is not something that most people enjoy doing. As TikTok founder [Alex Zhu points out](https://youtu.be/wTyg2E44pBA?t=245), education goes a little against human nature. In combination with a strong enough signaling mechanism however, you can get users to participate. It’s kind of the opposite of [Chris Dixon’s famous “Come for the tool, stay for the network” strategy](https://cdixon.org/2015/01/31/come-for-the-tool-stay-for-the-network). Come for the status, stay for the tool.
    - A related product I’d love to see is **Strava for Reading**. Imagine an eBook reader that not only tracks how much time you spend reading but also *what* you are reading. Based on these proof-of-(reading)-work mechanisms you could build streaks or GitHub-contributions-like visualizations that incentivize users to read more (and more regularly).
    - ![](https://julian.digital/wp-content/uploads/2020/07/githubforreading.png)
    - You could even build leaderboards for different topics based on the content
 of the books and articles you read. Or think about a score that indicated how balanced your reading behavior per topic was (to incentivize users to read takes on political topics from different perspectives).
    - Unfortunately, I think it’s unlikely that we will see a product like I described anytime soon. [The world’s largest bookstore, most popular eBook reader, and biggest social network for books](https://twitter.com/lehrjulian/status/1086659965719404544) are all owned by a company that has very little competency in design and user-facing product innovation.
    - (Side note: Amazon’s monopoly on books might be the most underrated sub-optimal equilibrium in tech.)
    - Another app that would be interesting is a social investing app. Think “Robinhood but as a social network”. It seems like investing is already quite a social activity – just look at [communities like r/wallstreetbets](https://www.bloomberg.com/news/articles/2020-02-26/reddit-s-profane-greedy-traders-are-shaking-up-the-stock-market). As [patio11 pointed out](https://twitter.com/patio11/status/1250703738634829824), Robinhood already feels more like a game than a finance app.
    - ![](https://julian.digital/wp-content/uploads/2020/08/robinhood.png)
    - So why not build an investing app that opens with a feed of all your friends’ investments and their returns over time? Instead of sharing screenshots on Reddit and Instagram you could prove your investments right in the app.
    - **Note that an app like this would not be about signaling wealth. It’s about signaling __being right__ and the ability to prove it**. This is probably an even stronger and more engaging mechanism than signaling wealth – and the reason why I’m still bullish on prediction markets.
    - Perhaps a well-designed, consumer-friendly prediction market app would be the ultimate proof-of-x social network. **Strava for being right.**
- ## A Closing Ask
    - While we are on the topic of being right: Do you agree with my thoughts in this post? What other social networks and proof-of-x mechanisms would you like to see?
    - Please leave [your comments here](https://twitter.com/lehrjulian/status/1291397928788135942).
    - __Thanks to [Dan Romero](https://twitter.com/dwr), __[Des Traynor](https://twitter.com/destraynor),____ __[Jan König](https://twitter.com/einkoenig), [Max Cutler](https://twitter.com/cutler_max) and [Zack Hargett](https://twitter.com/zackhargett) for reading drafts of this post.__
