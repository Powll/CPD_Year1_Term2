# CPD_Year1_Term2
Base repo for all CPD-related materials for the 2nd term of the 2018-2019 year

## Week 1

The first actual week of term time, in spite of being tired from the Game Jam I am able to focus on the game project, which I have been quite nervous about. I have not used Unreal as much as I would have liked to, mainly because I have been trying to find some tutorials that can at least set me in the right direction with what I need to do - spline related. Our PO meeting went about as well as I expected, we don't have anything to show just yet and to be quite frank I fear we will have a hard time maintaining an Agile work ethic. I will have to research deeper into the usage of Unreal splines with c++, as the lack of online tutorials is going to prove quite problematic. The group crit didn't go as bad as I though it would, although one thing I can say for certain: the difference between Unreal and Unity using teams is clear, and vast at that: we barealy had a working demo while the other team had gameplay, menu, save/load and pause mechanics implemented already.

## Week 2

My frustrations with Unreal grow more, as I am unable to get it to detect the Visual Studio installation on my local machine. This has been impacting my ability to work on the prject quite a lot, but hopefully I'll be able to figure it out. In other news, we had another group development lecture. While I'd like to see more programming oriented lectures of the sort, the one we had this week was extremely insightful into general team work and is sure to prove useful in the long run. As for the PO meeting, there wasn't much progress made since last week, sadly.

## Week 3

Little progress was made in regards to Unreal, although Byron was able to implement some basic customisation code on his end, we are still working with the idea of customising trains, but it definitely seems doable. As for the spline system, I am having quite a hard time finding any tutorials that don't entirely rely on blueprints for creating tracks. As far as I can tell, I won't be able to avoid using blueprints, no matter what I do. Still, I will do my best to minimise the number of blueprints I will be using. Sadly, I could not find anything useful in that regard on platforms like pluralsight, so I will have to continue looking.

## Week 4

I was finally able to find a suitable tutorial for the spline system! It still relies on using a spline blueprint as its basis, but it couldn't be helped. The train is also following the track, only, I need to figure out a way to make individual train segments link up to each other and move independently of each other. I will be preparing the algorithm for the track generation. That means doing some basic calculations to determine how the tracks will be rotated and placed. I belive the usage of a linked-list system is the best way to go about it, as it allows plenty of customisation for the final algorithm.

## Week 5

We started the week in a great way, with our group crit. The other team was also an Unreal-using team, so we were on equal footing, so to speak. Still, I believe that they were in an overall bettter place, as they already had plenty of gameplay features, as well as a very nice looking shader program - something I didn't even think about looking at. Overall, the feedback was what I had pretty much expected: we currently lack gameplay, but Byron assures me that the combat is coming along, so I am still confident in our ability to deliver the final product we pitched. However, the train customisation is looking less and less achievable. Lastly, we are in a small UI crisis, as we currently have no UI done. I would try to look at doing UI, but that implies both working in blueprints and shifting focus from my current tasks - track generation and refining the movement system - which I cannot do.

## Week 6

Studio practice week! This was by far one of the most productive weeks so far, and I am quite happy to say that we now have a combat track generation implemented! It is still somewhat rough around the edges, but it should do just fine... for now. I still need to get the combat trains to spawn, and then I will have to work on syncing them with the player train. This has also given me enough time to finish up my software engineering essay for next week.

## Week 7

This week was started by the presentations for our software engineering essays presentations. I, for one, will be tackling the application of Incremental Software Development practices and its consequences on the code base. I believe that our team project started off as purely Agile-based, but we ended up practicing something not very different from IDS and I noticed several issues with our code base as time moved on. Show and tell was quite the event, we had the chance to admire the wonderful games the 2nd and 3rd years have been putting their hearts into, and I was really impressed by their work! The entire event really lifted my spirits up and got me motivated, so now I feel that we might be able to finish up the project just fine. In other news, the final version of the combat track generation is done.

## Week 8

This week has mostly been filled with the addition of models, textures, tiles and, thanks to Matt, the player-following camera. At this stage I believe that most of my work is done, so I will be focusing on helping out with anything else that would need doing, such as the combat system. I am also starting to get things done in openGL for the game project, but progress is extremely slow.

## Week 9

The enemy train spawning is finally in, but I still need to work on the distance syncing between the enemy and the player. I was also able to add the station generation, which, although does *nothing* for now, I think will come in handy when we decide to finally get some gampleay implemented. We are also seeing some progress on the UI, which is nice to finally see. We ended the week on a high note, with a crit that made us realise in just what kind of situation we really are: we don't really have a game at this point, as we don't actually have any gameplay in. Me and Byron have been discussing adding something like a score based on distance or some sort of obstacles, so we will be taking it up with the team and see what ideas they have.

## Week 10

This week I was quite busy cleaning up some code and working on my other assignments, but mostly I feel like I need a small break from programming for a bit. I decided to focus on just making sure the PCG system is working well and on tweaking some small bits here and there. 

## Week 11

This is the final week before the deadline. We ended up rushing everything just before Demo Day, with me, Byron and Matt staying up all night getting 'everything' ready and a build done. In retrospective, I strongly believe that while we were unable to deliver the game we were hoping to, the scope of the project was adequate, but the sheer number of issues we encountered related to Unreal was simply overwhelming. However, I also believe that, were we to participate in a similar project again, we would be able to get things working much faster. Overall, I am satisfied with the outcome, be it as lacking as it may be. 

## Week 12

This week can only be descibed as: rushed. I had to stay up on several nights in order to finish up the controller and the report, all because of my poor organisational skills. I will definitely have to improve said skills if I am to develop a healthy working routine. Else, I can foresee myself getting burned out from just rushing projects before the deadlines. On the other hand, I think this may have been partly due to the fact that I overcomplicated myself by deciding to use OpenGL for my controller project, which ended up taking far more time that I had hoped, but I think it was well worth it. In conclusion, I think I definitely need to work on how I prioritise my tasks and how I scope my projects.
