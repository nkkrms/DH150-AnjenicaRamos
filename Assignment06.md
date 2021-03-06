# Assignment06: Low-Fidelity Prototype
##### Anjenica (Nikki) Ramos
##### DH 150: User Experience Design, Spring 2020 - Prof. Cho


## Project Overview: W.H.O. Covid-19 site 
The World Health Organization is a trusted international health agency which coordinates health efforts within countries of the United Nations, and, thus, currently serves as a leading source towards COVID-19 initiatives. This project will povide insight towards improving the presnetation of the information and navigation on their COVID-19 site, which features factual basics, advice and resources, as well as regularly updated regulations and statistics of the ongoing pandemic for the public. Prior user research with site testing and interviews have revealed problems in the current website's interface structure, as well as a lack of key, actionable resources, such as COVID-19 information that pertain to a user's location and a symptom-checker. 

Through the creations of personas and scenarios, I was able to explore these problems further, and my work thusfar has led me to design the following features in a mobile version of the site: 
1. **A more organized tabular homepage** -- overall cleaning how the landing page is presented because clashing formats, colors, lacking of design heuristics makes the site slightly disfunctional and discouraging to use
> For this, I imagined a 47-year old father, teacher, and department chair, Dan Miller, whom many in his network reply on for guidance and reliable information. This largely follows the high, yet everyday stakes that come with seeking COVID-19 info, as users need well-designed resources to be able to understand the details themselves (minimalist organization and communication), be able to refer back to this time and time again (where credibility and memorability come into play), and this resource to others (i.e. intuition for a broad, public audience). 

3. **Local links/resources** -- it'd be nice if the site can use your location information to have a section about local statistics, local resources, and local guidelines (ex. shelter in place regulations)
> For this feature, I pictured a work-from-home milennial user, Bethany Ramirez, who has just relocated to a new area for work. They are tech-savvy enough to seek information from the internet, and particularly need guidance in navigating the pandemic while settling in an area whose local sanctions, resources, and statistics are unfamiliar to them. While one could scower the internet and numerous unkwnown organizations' websites and news agencies, it'd be nice to have these all featured, or vetted and linked. This benefits multiple parties by connecting users to local offerings and them to their target audience.  

2. **A Symptom checker/sickness protocol** -- there is currently not a section which focuses on COVID-19 symptoms, as well as action items for users to take if they think they may have COVID-19, how to get tested, when to seek help, etc.
> Here, I envisioned Kathryn Chen, a small business-owner and single parent for whom English is not their first language. In a situation where she may have been exposed to the coronavirus, she needs key symptom information to take necessary steps for her health as well as planning childcare for her daughter. This addresses such a critical situation with trustworthy action steps, which is especially key in an internet full of pseudoscience remedies and varying experiences. 

Now, through low-fidelity prototyping, I can begin bringing these ideas to life. Through drafting user interface designs and creating a workflow of users' interactions with the mobile site, I am able to translate the research insights to a (rough!) product. From here, testing is key to see designs in action and gather feedback for improvement. It is always important to consult participants to understand design shortcomings from outside perspectives that the designer may be blind to. From here, we can then refine designs to continue with the product's development. 









## Prototype 

### Features + Tasks:
This low-fidelity prototype features, which have features within their sections: 
1. redesigned tabular landing page
   - mobile friendly 
   - hierarchical organization based on relevance 
   - usage of icons / descriptive labeling 
2. symptom checker (survey)
   - track selected symptoms
   - provide recommendations/action items based on results
   - ability to learn more with general symptom info directory 
3. local dashboard 
   - set location services/area 
   - have a tailored dashboard to user's area
   - links to local government sites
   - database of local resources + search navigation
   - database of local news agenices + search 
etc:
   - accessibility: avoidance of typing (unless search), scroll/click based
   - colors not strict, just to distinguish options from buttons!
  
   
### Wireframes/Wireflow (original)
note: view/save-able versions are [*here*](https://drive.google.com/drive/folders/1321mlnP-ATo8WMRQbyc56xphFG0HGX6K?usp=sharing)
![wireflow of symptom checker](photos/06.1.png)
![wireflow of local dashboard](photos/06.2.png)

## User Testing 
User tested the originally drafted low-fidelity prototype on the tasks and features presented. Session was captured through ipad screen reocrding as the user interacted with the digtal wireflow. 

Video of UT session [here](https://drive.google.com/file/d/1QaN-jHDG5x8_JDTC7U5AZAyU04GKqjwz/view?usp=sharing)

![wireflow of UT symptom checker](photos/Page1.png)
![wireflow of UT local dashboard](photos/Page2.png)

#### Testing Insights + Proposed Revisions 
- For the landing page's menu options, which intended to revise the UI and organizational problems of the site, the tester interpretated the "by the numbers" COVID-19 statistics portion differently than I imagined. I intended it as the display of current worldwide numbers (with just placeholder labels) in the middle of the page, but they suggested changing the placement to the top or within a menu tab.
> I'll definitely be considering moving this feature to the top (maybe smaller), since, the process made me realize, *wait, why'd I put it in the middle where it interupts the tabs in the first place?*

- For the symptom checker, I think it was unclear how you actually move from one page/frame to the next. My intention was that you select options in a list, and then a yes button appears. However, this made me realize how redundant it is since pressing the options is an indication of yes in the first place, and that, no matter what, yes or no, I intend the survey to go in a specified other that you have to move on to the following page either way. In relation, testing the user made me realize I didn't include a back button just between the pages of the survey, though I had them to return to the home page (so the user couldn't backtrack/change answers).
> Instead of yes/no buttons, have users indicate a "yes" by clicking and "no" by just not clicking, and have next/back buttons on the bottom for navigation.

- My intentions were that, when the survey concludes, you receive a recommendation for the course of actions, then you can choose to read more about symptoms or view the symptoms you had indicated as you having. Just because the frames were next to eachother, the user had thought that the end of the survey leads to reading about symptoms in general, then going to specific recommendations, instead of the other way around. 
> I think this was just general confusion, and that it still makes sense to present the 'results' that pertain to the survey taker first, then providing the option for further general reading. Though, instance like this just relate to how I layed out the wireflow. It was not always linear, since the frames presented varied on the clicked/selected features and I tried to fit it in one page. I think the tested felt restrained sometimes on trying to pick the 'correct' thing based on what is 'next' in position, but this did make me heavily watch for this distinction throughout the trial, which was helpful to be aware of. 

- For the local dashboard feature, the user did correctly do the task as well, particularly realizing that location must be set first before going to the dashboard itself. I thought this might be confusing since, again, layout of the frames. However, they got confused at how to actually set the location services. I intended to present two options, either using your location services automatically or manual input. However, this brought to light some revisions I can include.
> I should rephrase the instructions to be clearer, somethinglike *"To use the local dashboard, please choose one of the following options to enter your location,"* then have the two button options. Also, it may be helpful, as the user pointed out, to be able to enter a variety of inputs, like country, state, zipcode, etc and have the WHO site interpret it. I think logistically, it'd make sense just to do it by nation since it's an international agency, and this may be more of a backend coding thing to think of. However, in terms of the interface, that can be made more clear with instructions.

- For the dashboard itself, the user immediately gravitated towards the resource button and thought the other screens pertained to that. I didn't expect that last one to catch their eye, so I then prompted the tester to rank the buttons' importance to them, which definitely pointed out things I didn't consider about the hierarchy of presentation. 
> I'll be changing the buttons order to have news, then resources, then state policy. In addition, I'll also be considering the local statistics portion to be a graph of the current cases (though maybe that depends on whether that data may be available practically? Or are we allowed to just dream ideally since we won't be implementing this in real life with the real WHO).

- Technical difficulties: I general, my tester (my dad) was unfamiliar with using my ipad and apple pen to draw on the wireflow. I let him practice a bit before recording just with the basic writing functions of the drawing app I was using, but in general he didn't make a lot of notes and would just verbalize his two cents. I just started jotting them down onto the wireflow as we went - he would talk and point where, and I would write notes to myself sometimes. (He the path and most other motions himself though!) 



## Reflection

To summarize my process, I initially reviewed my existing user research thusfar to gather key findings: what flaws were most prevalent in the existing site, how users interacted with the site (positively and negatively), users' behaviors and values, and missing feautures that may prove useful. Then, I turned these specific insights into tasks and features I wanted my prototypes to test. I originally created a rough verbal/note tree map to create a foundation for wireframes. In drawing the wireframes, I sought after a mobile-friendly, intuitive, minimalist design in how I presented buttons/options. Afterwards, I established the flow by clarifying the interaction points and each step/screen. I'd say this part went generally smoothly, as it builds on previous weeks' learning and helped me come in with a thought process in mind. It did take longer than antiicipated though, partly because I didn't realize just how much thinking goes into planning out something app/site features: every button, every presentation decision, every connection. I learned that it actually requires a lot of underlying hypothetical thinking as well (kudos to developers out there), even at the low-fidelity level. 

For user testing, I had the participant try to go about the steps of flow with their own intuition. The only thing I would note is that I did make little border marks (grey boxes) on their sheet as a basic guide because I had a hunch that the layout of all the wireframes may be confusing in a way that's just counterproductive to the user. Overall, I think my participant was able to grasp the purpose and utility of the features. In this way, the testing went well because I had become more comfortable with the process from previous assignments' practice. However, it was still a touch-and-go in terms of how freely we should let the user independently configure the wireflow versus ask guiding questions, which may encourage them to talk aloud, but also may influence their answers. The tester was able to complete the tasks, though not in the direction I always particularly foresaw. 

I think a lot of the knowledge gained that came from this experience were implicit through practice and, also in the user testing, observing user behavior - it's not always necessarily something they said or wrote; it's in noticing the points of hesitation or overlooking points (which shows what grabs attention, what's ignore-able) sometimes. I was brought to question order and directionality (does it need to be in this order? how else can this be organized? based on what the user expects). I will definitely be able to revise the prototype from this in order to add the new considerations  noted. It'll be valuable to transform these feedback into changes for a high-fidelity mockup later on. 

