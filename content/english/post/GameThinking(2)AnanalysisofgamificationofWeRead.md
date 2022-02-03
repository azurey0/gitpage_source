---
title: "Game Thinking (2)： An analysis of gamification of WeRead"
date: 2020-08-20T12:25:36+08:00
Description: "An analysis of gamification design of Wexin Reading based on the framework from previous post"
summary: "An analysis of gamification design of Wexin Reading based on the framework from previous post "
Tags: [Gamification,Product Thoughts]
Categories: [Product Thoughts]
DisableComments: false
---
&emsp;After reading *For the Win: How Game Thinking Can Revolutionize Your Business* By Kevin Werbach, I applied its framework to analyze an app I like very much: WeRead. By official description, it is 'an official reading application based on WeChat relationship chain'. Weread aims to build a perfect reading experience, recommend appropriate books, and allow users to interact with friends in reading. 
#### So how does Weread integrate game thinking?
&emsp;What's the core thought behind gamification of Weread? ——Make reading easy, comfortable and fun    
&emsp;What's the mechanism of Weread's gamification? ——Build a circle where firends can read together and even compete with each other; give extra bonus to encourage users' gaming actions, for example, extension of free-trial and reading tokens.   
&emsp;Is the game design successful？——Generally successful  
&emsp;How much does game design contribute to the success of the app？——Probably 50%, with the other 50% coming from great UI design   
&emsp;Can we migrate the same gamification to other apps in the future? ——Of course, but not in the sense of making more profit, as Weread doesn't neccesary to self-financing  


&emsp;Well, so do the gamification elements of Weread perfectly suits the app? To answer this question, we can think from following angles:  
#### Does Weread suits a gamification design? If so, how should we do that?   
&emsp;Needless to say, the core function of Weread is reading. So we can think of the relationship between reading and gaming as following:    
##### 1. Motivation
&emsp;According to Self-Determination Theory, there are three basic motivation needs of human, that is:  
&emsp;**Competence**：People need to be effective in dealing with environment. When reading, ideally people should feel they are capable to finish reading the material and understand it, even give their own thoughts about it.    
> In order to let users aware their competence, the app designed **underline, reading progress, comment and likes** functions.(Adds up from 2022: the recommendation is another crucial part, but it will be a long story)  

&emsp;**Relatedness**：People need to have close, affectionate relationships with others. People hope they are knowledgable and all their friends can tell.  
> Related functions involves **Ranking Board, share and bookshelf shown to others**. Weread is integrated with Wexin, the most popular social app in China in which everyone has a network. So these functions are empowered through the network. 

&emsp;**Autonomy**：People need to control the course of their lives. After reading the books, people want to feel they are step closer to their goals.  
> **Well, I don't see the relatedness to the current version of Weread**

##### 2. Can we set achievable and interesting goals for users?  
&emsp;For example, when people don't want to read, can Weread attracts their attention by sending push or something similar?    
&emsp;Personally I think no. Weread are not sending endless notifications and pushes to users, neither exists periodically 'events' as in online games. But think differently, do we really need to attract users when they are not here? Think about what do you feel when receiving not important pushes, it is not satisfactory. I think there's a parsimony in app design -- that is, not to disturb your users too much. This is a principle many apps forget when the designers are eargerly reaching out to users to fulfill their KPIs.  
##### 3.  Can we build a pattern on expected users' behavior?    
&emsp;Yes! There is a pattern in Weread that is simple and practical: when your reading time achieve certain level, you can exchange it with 'reading tokens' and extension of free trial. This is an important reason why many users stick with Weread.  
##### 4. Does game design cause conflict with current system?  
&emsp;Not applicable here, this problem occurs more in business organizations.    

&emsp;To summarize, Weread can apply game thinking in **motivation and pattern design**, and they are integrated well: **Through understanding of users' thoughts and appropriate bonus(reading tokens, free trial), the development team and users achieve the same goal of reading more**   
&emsp;P.S. One thing to address is that Weread might not be self-financing. As its parent company Tencent makes most profit from ads and mobile games.  So Weread does not have big problem of surviving.    
&emsp;Another game design that I feel good：
-  Give user feedback
Weread has a weekly reading dashboard showing reading data. It also encourages people when they view the reading dashboards. They all tell people "you are doing pretty good!"  
-  Don't do evil and be restrained
There is no force in using any of the game design elements or participating in game events, they receive bonus just because of they stay and read.  


&emsp;Here comes the detailed elements of game design:

#### Elements of Game Design
**Answers of the Day(每日一答)**  

&emsp;Entrance：Homepage, homepage scorlling down  
&emsp;Description: it opens a mini-program where users answer knowledgable questions, just like strike combos in games. They receive tokens after each level, which can be used to exchange for free reading time, books, etc.  
&emsp;There are 2 modes:  

**a) Answers of the Day 每日一答**  
&emsp;You answer 12 questions generates by the program. The questions are usually challenging and bonus are given only 12 questions are completed, and tokens can exchange for books and free reading time     
- Game elements：points are used for bonus   
- Game mechanism：challenges
When people fail, they can use the following method to 'reborn' and continue the game, which encourages them to spend more money
{{< figure src="/images/weread_1.jpg" >}}
**b) PK**  
Users pk with real persons or friends, they gain points for ranks.    
- Game elements：points, ranking board, which are used to symbolize the winner and achievements.    
- Game mechanism：competition  
{{< figure src="/images/weread_2.png" >}}

**Flop  翻一翻**
{{< figure src="/images/weread_3.jpg">}}  

&emsp;Entrance: click to enter, flop 2 of 9 cards to get gift books, another 2 flops are given if shared the app with friends.  

{{< figure src="/images/weread_4.jpg" >}}

- Game mechanism：opportunities，random factors  
- Game elements：collect  

&emsp;The cost of click a card and flop is very low for user, and they can get a book they possibly like. Then why not?     

&emsp;These 2 game design are of less 'social' elements.    
&emsp;The following 2 design are more related with social elements, which is more alike virus marketing.  
  

**Team up for Free trial Cards 组队抽取无限卡**  
&emsp;Description: a user invite 4 people, each of them will get a free trial card when they join. The team exists for a week, so the following week a user will set up a new team with at least 1 person not from the previous team.  

{{< figure src="/images/weread_5.jpg">}}

**Collect 'likes' for Free trial Cards 集赞获取无限卡**  

&emsp;Description: user share their card and get 'likes' from friends, every 2 likes can be exchanged for 2 days' free reading, with maximum of 12 days' free reading.  

{{< figure src="/images/weread_6.jpg" >}}


**Game design on reading**  
&emsp;In other reading apps, buy books-read-mark books-comment-mark complete has become a common process. On the basis of that, Weread adds more social elements where to build a book club online, encouraging people to read more. For example:      
- **I can see what my friends are reading**  

{{< figure src="/images/weread_7.jpg">}}

&emsp;The target customers of this product are basically people wants to improve themselves. From the motivation perspective, they are pursuing competence and autonomy when they use the app.   
&emsp;So when I see what my friends are reading, I will be curious about what they learnt. Specially, I care more about someone I know(which is my Wechat friend) compared with some randome people.    
&emsp;From this point, Weread has the advantage of being related to Wechat circle. It grew up from a plugin, or mini-program in Wechat and became an mobile application successfully, because its huge user base.  
  

- **I am not alone when I read**  

&emsp;When reading a book, Weread allows users to see others' public underlines and discussion. Users can also see how many people are reading this book today. Compared to reading a difficult book alone, it is better to be accompanied by someone. It's also easier to focus on important points when seeing underlines by others.  
{{< figure src="/images/weread_8.jpg" >}}  

&emsp;Users can also see others' reading progress, which encourage them to catch up. It's like a ranking board design.       
{{< figure src="/images/weread_9.jpg">}}  

&emsp;'Likes' are elements to applaud for others and it is effective to encourage difficult actions. For example the applauds for atheletes. This design also shows up in an training and sports app called 'Keep'.   
&emsp;But there are many robots here, see the figure above. Is it possible to add some extra bonus or a 'Like' button at the end of books?   
- **Reading time ranking board**  

&emsp;Ranking board is a good design that encourages people to catch up, but it also has problem: I am a lazy one, so when I see there's a very long way to catch up, I just give up.    
&emsp;So the smart Weread team adds a button to hide the ranking board.     

#### Conclusion
- Weread brought game elements from its parent company, the successful mobile game company, like **PBL, flip cards, UI elements**, but the team redesigned to make the elements match the style of Weread, a parsimony, professional and connected reading application.  
- Another reason for the success of Weread is it has the blood of Wechat, where people can read books together with their circle.  
- One thing to mention: the **UI** design is very elegent and smart, I found a very good post analyzing it: http://www.qidianlife.com/Singular/index.php?m=App&c=EveryDay&a=index&id=40
- Last, there's not much surviving pressure on Weread, which is an important element for reading applications. Only under this situations can the team spend more time on game design, UI themes and contents, not to yield to making profit.
