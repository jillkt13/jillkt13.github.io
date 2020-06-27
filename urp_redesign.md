# Redesigning our main conversion landing page

For years, one page on our website has been a white whale. The conversion landing page is essentially the “Access denied” page on our website. Users will see this page if they are not authenticated to get access to the content on the page. It accounts for 55% of all incoming traffic to the site and had a bounce rate of nearly 75%. 
This page is so complicated because it has to do a lot of different things. It needs to simultaneously communicate to the user that: 
* they have arrived at content
* they do not currently have access to the content
* they have certain actions to take to get the content, depending on whether they are affiliated with an academic institution or whether they are an independent researcher

**My challenge:**  Provide the context and research necessary to completely overhaul this page so that users are able to get access to the content if they want it. 

**My Contribution:** project scope, facilitation, product strategy, analytics implementation, interview moderation, wireframes, web analytics, impact mapping


## Method and Approach

### Design Jam

Given the ambition of this project, I argued in favor of leading a design sprint for our entire team. I adapted the typical design sprint framework to meet our needs as a team. I built out an entire agenda for 4 half-days of focused design research work. Before the design sprint commenced, I did a lot of preliminary work pulling together prior research, quantitative data, and heatmap data. By doing so, I built our current understanding of the page in order to design for the future. This background research was crucial for the direction we took for the page. We learned that while our business goal for this page was to convert academic institution users, the typical user goal on this page was upstream from that goal: they wanted to preview and evaluate the content before taking any action to get full access. With that in mind, the designer and I developed the following problem statement:

<img src="/images/Screen Shot 2020-06-27 at 2.39.09 PM.png" width="225">

During the design sprint, I led sessions focused on understanding prior research on the page, detailing user journeys, developing a problem statement for this work, and sketching exercises. Following these sessions, the product designer and I collaborated on a prototype to validate in 5 initial user testing sessions. 

Finally, I led a user testing watch party with 10 colleagues involved in this work. Based on the findings of the team during this watch party, we emerged from the design sprint with a bunch of ideas to revise our prototype and test with more users. 

### More user testing

<img src="/images/Screen Shot 2020-06-27 at 2.15.26 PM.png" width="275">

For our next round of testing, I established a list of three things that all users must successfully be able to do on the redesigned page:
1. Can they evaluate the content to decide if they want the full article?
2. Can they determine whether or not they have access to the full article?
3. Can they take the necessary steps to get access to the full article?
I conducted several user testing sessions where users were presented two versions of the redesign and given tasks to evaluate their success on the above goals. A clear winner emerged from this testing, which led some members of the team to push for implementing the new design and begin optimizing smaller items on the page, like button copy. Given the importance of this page and its massive amount of traffic, we knew we needed more testing.

### Experiment

To collect data at scale and validate, I proposed a large onsite experiment. The development team began work on an MVP-version of the redesigned page. I built out an extensive experiment plan. While some team members pushed for a simple a/b test focused on a single metric, I argued for an expanded scope to the experiment. I felt that the page was complex enough that it merited a more profound investigation than looking at uplift in conversion rate. In particular, I argued for a larger-scale experiment because: 
* the old and new version of the pages were vastly different, preventing an easy 1-1 comparison of a key metric
* our point of view for this page went beyond mere conversion, therefore we’d need to evaluate several metrics to get a cohesive perspective on success
I developed the table below to summarize our multiple goals for the page and various user types and aligned metrics to those goals. In partnership with the developers and our web analyst, I helped implement the tracking that would allow us to measure these variables. Not all of our variables were easily tracked in Google Analytics, so I had to think through Plan B and even Plan C options to get the tracking we needed to assess success. For example, we ended up relying on a heatmap tool to look at general engagement metrics like scroll rate. 

<br></br> | Current page | Redesigned page
------------ | ------------- | -------------
**Evaluating content** | | 
Can they see the preview? | Scroll rate | Click on preview
Can they consult metadata? | Engagement time on metadata | Engagement time on metadata
**Institutional access** | | 
Can they get to institutional login? | Click on modal | Click on button
Can they complete institutional login? | Conversion rate | Conversion rate
**Independent access** | | 
Can they get to preferred independent access method? | Login, register, or purchase | Login, register, or purchase
Can they complete their access method? | Conversion rate | Conversion rate
**Other metrics** | | 
Bounce rate | It should decrease on the new page, since it is hypothetically a better experience with a clearer CTA
Time on page | It could go up if users are spending more time evaluating content or down if it's easier to take the next action  
Pathing data | What is the order of actions taken on the page? Are users toggling between access methods? 
User support contact rate | We will work with support to monitor feedback on the new page  

Following the experiment period, I had a lot of data analysis work on my hands. I chased down the numbers we needed, tested for statistical significance, and analyzed them to tell a story of what we had learned about the redesigned page, with a focus on recommendations for future implementation.

## Impact

* On a more abstract level, this initiative helped me and the team create a point of view for this highly trafficked page that was backed by evidence—both quantitative and qualitative—instead of preconceived notions. This foundation allowed us to optimize and make adjustments to this page with a few ultimate metrics and goals in mind to guide us.
* The final results of the experiment showed great success. The bounce rate decreased by 13%, meaning the redesign was more successful in supporting users to evaluate the content and decide if they’d like to view the full article and therefore also more successful in getting more users into the conversion funnel. The conversion rate for users with institutional access increased by 2.5%, a pretty big and statistically significant uplift. 
<img src="/images/Screen Shot 2020-06-27 at 2.31.06 PM.png" width="325">

## Reflections

* *Collaboration is key:* I argued in favor of including more participants than just our product development team in the design sprint. We had representatives from Marketing, User Support (who field hundreds of complaints on the conversion page every year), and the Content (who liaise with publishers to set the access restrictions on this page). Their perspectives were so valuable as we brainstormed the goals and metrics that indicate success for this page. Later on in the process, collaboration with the web analyst was invaluable in developing an effective and complex experiment plan.
* *Lean into complexity:* Previous attempts to redesign this page focused solely on the conversion rate. It was seen as the Access Denied page, and the assumption was that to be successful, this page simply needed to get people into the funnel and grant them one of our site’s forms of access. But my careful work in pulling together previous data on this page allowed us to reimagine our point of view for this page, positioning it as not only a conversion page but also a place for people to evaluate content metadata and previews. I also was careful to note that because of our site’s complex access model, this page had to serve users with multiple types of access (or no access, for that matter). This complexity made our job a lot harder, but it also helped us look at this page and our success criteria for it with clear eyes. By acknowledging its complexity—and designing and researching for that complexity—we were able to develop a solution that met more of the needs of more of our users. 
