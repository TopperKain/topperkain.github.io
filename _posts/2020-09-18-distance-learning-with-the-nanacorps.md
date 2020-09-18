---
layout: post
published: true
categories: Remote Learning Family
---
## Or the rise of the Nana Corps

The school year has begun for begun for my family. In this time of COVID19, that means “hybrid learning”- two days a week at school and three days a week at home for my 1st and 2nd grader, with half the class (a “cohort”)  in person Monday/Tuesday and half in person Thursday/Friday. I’m happy with this arrangement- I think it provides the needed socialization for my kids while providing a good firewall against rapid disease spread. However, the teachers are primarily dealing with the in person “cohort”, a LOT of the at home learning falls on the family. So how are we coping with distance learning. 

> Hint- the grandparents are helping. A lot.

<figure>
  <img src="{{site.baseurl}}/media/distance learning chairs.jpg" alt="Girl sitting in a chair with stuffed animals"/>
  <figcaption>Adorable distance learning. Also, not my family- This from an ad for Lifetime branded kids chairs I saw at Costco. Serious props to the brand manager for nailing COVID marketing. <a href="https://www.lifetime.com/lifetime-80473g-childrens-stacking-chair"> Manufacturer's page </a></figcaption>  
</figure>

## Setting the objective
I was confident by early July that we would not being going back to business as usual for school, so my wife and I were able to get a head start on our planning. We identified 4 primary objectives for our distance learning experience.

1.	Ensure the kids get a high-quality education.
2.	Enable the parents to continue their careers.
3.	Improve the kids socialization.
4.	Keep everyone in the family sane.

I will say that his is the most formal articulation I have gotten to for these objectives, they were more an understanding built up over hours of discussion about the school situation, how we’d deal with it, and how angry we are at the illogic of opening bars before schools (but that’s another post.)
We pretty quickly realized that there was no way to achieve our objectives with just two parents. Even though I work from home, I think the COVID19 crisis has pretty well demonstrated that working from home and homeschooling are mutually incompatible. We needed support. We needed grandparents.

## Building the team- Bring in the Grandmas! (and Pas)

My wife and I are blessed to have loving, supportive parents. We are also fortunate that they love and miss their grandchildren enough to help us multiple days a week with their education. There is just one catch- due to distance and health concerns, they can’t be physically present with their grandchildren. This was going to be distance grandparenting all the way through.

<figure>
  <img src="{{site.baseurl}}/media/picturephone-antique.jpg" alt="Antique picture phone"/>
  <figcaption>My mom used a videophone like this at the 1964 New York Worlds Fair and dreamed of having one. More than 50 years later, she using on like it everyday with her grandkids. This is really, really, cool! Photo Credit- <a href="https://www.flickr.com/photos/jeepersmedia/9712458483/"> Mike Mozart, under Creative Commons Attribution </a></figcaption>  
</figure>

## Creating the space
Effective working from home requires the right tooling and an effective working space. In our case, we already had a perfect space- my home office. My home office is a 200 sq foot shed I rebuilt and finished to be ½ workspace and ½ man cave. My dad and I took it down to studs and rebuilt it in 2018, then I got some contractors to do the electrical, insultation and drywall. AC is provided by a portable floor unit, heat by a space heater, and water by a water cooler. It was the part of the house that was completely my space- I built it, I decorated it, I spent my work days in it, and I put my hobbies in it. I loved that little shed.

Anyways, my kids have completely taken it over. We have 2 desks- my former desk and writing desk that we got from my in-laws in 2007[^1] . I dug out a some wall decorations from my childhood and put them up, including a needlepoint teddy bear picture my mom made me and a firetruck that no little boy should be able to resist. We also bought “educational posters” and hung a whiteboard. We softened the floor with a nice big rug. Finally, we moved books and bookshelves to create a nice little library aesthetic.

It’s a pretty cute a setup at this point, even as I bemoan the loss of my man cave.

## The Tools

In parallel to setting up the space, which honestly was mostly my wife’s doing, I was working on setting up tools and processes to enable the grandma’s to effectively work with the kids. Here is what I ended up with:

### Videoconferencing
-	For monitoring the kids- <u>Amazon Echo Show</u>- Both grandma’s wanted a fixed camera set up- apparently the “running around with the phone while on FaceTime” routine was getting old. We settled on the Echo Show primarily because of the perceived ease of use and the “drop in” capability. Grandma can just pop in even the boys are trying to be sneaky. The audio is good on both ends and the video is adequate.
-	For sceensharing- <u>Jitsi Meet</u>- This program is GREAT. Its free, open source, and uses the open protocol WebRTC. Its also stupid easy to use. We are using purely for screen sharing, as we find it better to use Echo Show for actual talking, but this is what enable grandma to see each kids screen. We are now experimenting with each kid logging into their own meeting and sharing their screen to that and grandma being able to get both feeds simultaneously.

Between these two tools, the grandmas are pretty good at monitoring what's going on and helping with any learning speedbumps.

### Computing
<u>Laptops</u>- my kids laptops are older than they are and they work fine. I think the total combined value of the laptops is less than the echo show. One is running Windows 10, the other Ubuntu. I don’t recommend running Ubuntu if you don’t have someone in your family that knows that knows what “sudo” is. I’m glad we have laptops though- I don’t think doing this via tablets would be feasible.

### Site blocking
<u>OpenDNS and Raspberry Pi</u>- I never thought I’d set up network blocking in my house. I thought it silly and trusted my kids. Then one of them innocently tried to search for “pictures of brown bunnies” <sup>NSFW</sup> and we found out what a filthy place the internet is. Additionally, we needed to start blocking access to games in, as the kids can get quite distracted by massive multiplayer online nibbles (seriously, this is a thing- littlebigsnake.com).  I settled on a free setup using Cisco’s OpenDNS (<https://opendns.com>) and the PiHole ad blocking/DNS software running on a Raspberry Pi (<https://pi-hole.net/>), because I’m a nerd. This setup probably requires its own post, but it has the benefit of making the internet better due to adblocking as well. For the less technically inclined, there are options such as the Disney Circle (my router had this as a built in feature, but I had huge performance problems), net nanny, and clean router. If you just want to block questionable content, you can use the instructions at <https://cleanbrowsing.org/guides/windows> to reduce the likelihood of accidents.

### Printer
I bought whatever was on sale. I’m annoyed to have to print things again, but this is a school requirement at this point. I’ve also found myself printing more stuff generally for the kids to use, outside of school- they like the physicality of it.

So far these tools have done a good job of enabling the grandmas to communicate and monitor the kids while enabling the kids to get their work done.


## Wrangling Complexity
Now that I’ve spilled words on the tools we use at our house, lets talk about the tools used at school. There are 21 separate IT systems in use for education, communication, or administration at my kids school. Between my 2 kids, I have 22 different log-ins to manage. This is absolute insanity. 

In order to enable the Nana Corps, we’ve consolidated information on every IT system into a single shared OneNote notebook. Every link, username, and password (if not totally inappropriate) is stored there, with instructions on how to login and what it is for. Additionally, we have copies of the kids schedules in there, and we copy any communication or documents we receive to a shared folder on OneDrive. 

I also held a pre-start of school training for the grandparents on all the tools and systems we are using. This allowed us to work out the kinks without the kids jumping up and down at the same time.

This pre-work has been remarkable effective. I was expecting way more questions about how to get where, but so far I’ve been able to work almost the whole day while the kids get their work done then enjoy story time or dance parties with the Nana Corps.

## Results
While things have been going well for the first 3 weeks, it hasn’t been perfect. Our boys have had a few issues paying attention to the Nana Corps, who isn’t there to tap their shoulders physically and remind them to get back to work. To deal with chaos we’ve taken few in classroom techniques we’ve seen.
-	<u>The rewards chart</u>- in order to provide incentives for the kids to behave and get their work done, we have moved to using “reward” charts for good behavior. The kids get daily marks for citizenship with nana, citizenship with their family, schoolwork, chores, and bedtime/morning at this point. We are starting with printed templates ([from here](https://templatelab.com/reward-charts/)), but ordered some magnetic ones like this: [magentic reward chart](https://www.walmart.com/ip/Melissa-Doug-Deluxe-Wooden-Magnetic-Responsibility-Chart-With-90-Magnets/33359769) for the future.
- <u>Recess</u>- We have rapidly realized that we need to be serious about the scheduled break times, including having the Nana Corps send the kids outside to play. Getting yayas out is important.

I’ve also accepted that I’ll need to go out a few times during the day to help get them back on track. There is just no beating a physical presence sometimes. We’ve also a couple meltdowns over “not having anything fun to do” that we are working through. If anyone has any suggestions, let me know.

Overall though, I think this has been a success- I’m able to work at least 90% of the time, my kids are getting 100% of their work done each day, and the Nanas are getting to spend more time with their grandkids. A good deal for everyone. 

[^1]: That desk has also served as media center, kitchen table and display platform. I have never owned a more versatile piece of furniture.