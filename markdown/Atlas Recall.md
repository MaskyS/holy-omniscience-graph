- a [visual]([[visualizer]]) [[search engine]] for finding local/cloud documents/files/texts/photos etc from your [usage history]([[Perfect memory]]), started in [[2016]] and shut down in [[2017]].
- It was available as a desktop app on [[MacOS]] only and had an [[iOS]] companion app on the [[iPhone]].
- ### Shutdown Resources
    - https://www.geekwire.com/2017/atlas-informatics-shut-pulling-plug-encrypted-personal-search-engine/
    - https://techcrunch.com/2017/10/18/atlas-informatics-calls-it-quits-after-less-than-a-year/
- [My]([[Kifah Meeran]]) Personal Postmortem
    - Cost of business far exceeded value captured. Why?
        - - Started off with a freemium model, and based off this [interview](https://www.youtube.com/watch?v=JHDQLDYnfaU&list=ULZFL7xpKjYsQ&index=893) between the [CEO]([[Jordan Ritter]]) and [[Jason Calacanis]], they hadn't made up their mind on how to charge their customers, so they actually didn't implement the paid features part.
        - - From what I understand Atlas captures screenshots for *every* window/screen/visited page, and sends them to their cloud. I imagine that entailed exponential server costs. UPDATE: It might not, if they did image differentials like [[Savant Recall]].
        - - They never seemed to have a defined target market. Sure, they mention enterprises a bunch of time 
    - But this really doesn't make sense to me. If money was the issue, wouldn't it make more sense to wrap up the public beta asap and start gathering paying users, rather than abruptly shutting down the service? Especially given the fact that this was a project in the works [since **2013**](https://cards.producthunt.com/cards/comments/383094?v=1). Something's wrong if you don't consider your software product worth paying for after 3-4 years of development.  
    - - searches only titles of documents
    - cant search notes or calendar content - despite mac being able to.
        - > Recall is rather spectacular when it comes to finding web pages you’ve seen, email you’ve read, PDF documents you’ve opened, and people you’ve opened in Contacts. It can call them up again instantaneously, and when you click Open, you’re returned to the actual web page (in your browser) or email (in your mail program).

Unfortunately, Recall isn’t as impressive at other kinds of documents. It does a great job of finding words you’ve had in chats—but when you click Open, **it opens up a screenshot of the relevant screenful of chat**, rather than opening the chat program and scrolling to the right place. It **does the same thing if you search for an Evernote page, or for an email that no longer exists**.

It’s even **worse at things like Microsoft Office documents, which it can find only by their titles**. It can’t seek inside of them, which is very odd—the Mac’s built-in Spotlight command can do that!

**Recall can’t find text in the Mac’s Notes app, Calendar, or Stickies. It can’t find text in Tweetbot**, my Twitter (TWTR) program. **It’s blind to what’s in page-layout files like Adobe (ADBE) InDesign.**
    - Being cloud-based had several drawbacks:
        - - unescapable privacy concerns every time its mentioned, a sentiment that has grown way stronger today. People are not okay with a centralized info-silo.
        - -storing every move of user = crapload of user data = unrealistic costs
        - - bottlenecked by internet connection, not good given graphic-heavy content and nature of query (search, which already is resource-intensive)
- https://spencerleejames.wordpress.com/portfolio/atlas-recall-user-research/
    - > At the beginning of this project, we met with our sponsor at Atlas Informatics to get a sense of Recall and our sponsor’s goals and expectations for the study. It was determined in this initial meeting that the scope of the study would be limited to testing Recall’s onboarding flow. During this meeting we also discussed the company’s concept of the potential user base and learned that they saw users as being:

    Windows users
    Ages 25-55
    Uses of multiple devices
    Comfortable with sharing digital information via social media and cloud storage services
    Early and late tech adopters

- https://medium.com/@richkolasa/why-notion-so-c8ead733dc64
- https://www.jackvinson.com/blog/2016/11/23/search-or-find-or-recall
- https://finance.yahoo.com/news/david-pogue-review-of-atlas-recall-160114345.html
- https://fluxn.com/atlas-recall fun breakdown of design by.[[Justin Martin]]
- https://appleinsider.com/articles/17/08/12/hands-on-find-anything-fast-on-your-mac-with-the-atlas-recall-app-and-service
- http://www.justinmarxdesign.com/atlas-product-design-brand-identity by [[Justin Marx]], who seems to have been the main guy on the design team.
- https://beta.techcrunch.com/2016/11/02/atlas-recall-a-search-engine-for-your-entire-digital-life-gets-an-open-beta-and-20m-in-backing/
- landing page archive: https://web.archive.org/web/20170520172804/https://www.atlas.co/
