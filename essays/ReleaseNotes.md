---
layout: essay
type: essay
draft: false
title: CS Release Notes
date: 2017-01-15
labels:
  - Release Notes
  - Collaborotaive Study
  - Software Development
---

In the fall semester of 2016, I took ICS 314 - Introduction to Software Development. Within that class, the final project was to create some sort of prototype of a web application students of the University of Hawaii to use. I was assigned a group and we created an app called CS (Collaborative Study). This app allows Computer Science students to connect with their classmates and set up study dates. Our submitted app was great for our first prototype but we still have a long way to go. So now in this current semester, Spring 2017, my team will continue making the app be the best app it can be!

Check out our app: <a href="http://cs.chadmorita.com:3000">CS</a>
Check out our homepage: <a href="https://collaborativestudy.github.io/">Collaborative Study Homepage</a>

# As of right now!

## May 1

It is the final week of instruction for Spring 2017 semester. What our group focused on these couple of weeks is to touch up the CS app and to update our Collaborative Study homepage. We have decided to halt any new additions we have been working on like the new chat ui interface. We are trying to prepare for any public relation for the app. If anyone is interested in the app they can check out our homepage and our Github repository then contact us for a presentation or delivery. Personally, the app has come together very nicely and I believe I learned a lot from this experience. I hope that people who uses our app and looks at our teams homepage will see how much time and effort we have put into this. I am glad I was able to work on this app, it has been one of the biggest projects I have worked on. Maybe one day I will see this app being used by the department, and that will truly push this project into reality.

Check out this milestone: <a href="https://github.com/CollaborativeStudy/CS/projects/10"><i class="large github icon "></i>Project 11</a>

## April 15

As the semester goes on, our group is slowing down in our production and focusing more on testing. Personally, I am still improving chat interfaces to make it more aesthetically pleasing. I find it more harder to improve the user interface than to improve a functionality. That is because with a functionality I know whether or not it is working properly. With interfaces it is hard to find out what people like within a website or an app. People are so fickle and have different types of preferences. So far I have a chat interface that I enjoy looking at but I will continue to ask others to figure out what kind of things they like within an app. As a group, all of us are focusing a lot on testing our product and reaching out to other students. The testing has been going well. I would see uncommon bugs where something stops working for a while, but at other times it will work. For example, when making a group session some people were able to make it from the calendar but others weren't. Also, when creating group sessions, it will create it but it will not show up on the calendars. We will continue to fix these bugs and do more usability tests in order to find as much bugs as possible.

Check out this milestone: <a href="https://github.com/CollaborativeStudy/CS/projects/10"><i class="large github icon "></i>Project 10</a>

## April 1

This week as been filled with some pretty exciting things. Personally, during this week I just fixed minor bugs within the features I have created. However, one of our contributors was able to host our app on his very own server! Now that we have a public domain we can now start testing the usability of the app. As the semester is coming towards an end, it seems like there are fewer things to add to our project. Right now, we are fixing minor bugs we see as we use the app and try to improve it as much as possible. There should only be one more functionality that we plan to add to the app. Once we do the usability test, we will know for sure if there are any big changes we need to make for our app.

- Now live on a server!
- Fixed user profiles
- Fixed posting in chronological order

Check out this milestone: <a href="https://github.com/CollaborativeStudy/CS/projects/9"><i class="large github icon "></i>Project 9</a>

## March 15

Recently our group has started planning out how we are going to test CS. In our first week's meeting we met up and decided to create a usability test. This test will see how easy our app is to use and to learn. We decided how exactly we will conduct our test; how much people we should test at once, how many times we should test someone, if there should be data already on the client and etc. After that, we focused on what we needed to fix on our app in order to start tests. We were only waiting on me to finish up the Reviews feature. I had to make it so the user cannot post a review about themselves on there own profile. However, in order to do that I needed to recreate the schema for Reviews. Before, the schema was way to simple and did not have any authors attached to them. Naturally, when I changed the schema I had to change everything else using it. So that task took longer than expected but it was for the better. Reviews are now organized very well for each user. My team mates worked on other features while I tried to perfect reviews so check out all the new features below!

- Review visibility
- Star ratings rounded down
- Clean up calendar
- Searching by other options

Check out this milestone: <a href="https://github.com/CollaborativeStudy/CS/projects/8"><i class="large github icon "></i>Project 8</a>

## March 1

Within these last 2 weeks, I have made a significant amount of progress compared to the last session. As I said on February 15, I took a break from fixing posting in group pages and decided to focus on other features. First of all, I changed the My Groups page to only show the users groups. Before, My Groups would actually show every single group made by a user. So now you can only see groups that you are a member of. Second, I added leaders to groups and gave them privelages over regular members. Leaders of groups can delete the entire group and kick any negative members. Also, regular members can leave the group. After I added these features I went back to group posting. Lastly, I am proud to say that I have finally gotten posts to work! I felt so much relief when I overcame this task and I feel like I learned a lot through my endless debugging journey. So the new features are listed below.

- Private group visibility
- Group leaders were added
- Privelages for group leaders were added
  - Whoever creates the group is the leader
  - Leaders can delete the group
  - Leaders can kick members
- Post in your groups page to make announcements

Check out this milestone: <a href="https://github.com/CollaborativeStudy/CS/projects/7"><i class="large github icon "></i>Project 7</a>

## February 15

Ever since February 1, unfortunately I was not able to make much progress with my issues. I have been running in circles with fixing internal issues with posting in a group page. I would fix one problem but another problem will pop up. As I try to fix that problem, the same problem from before will reappear! This dilemma has stopped me in my tracks and I have decided to take a break from it. No, I am not quitting. I am just going to start on other issues as I try to figure out the problem for group posts. Next time, I will not make this type of problem hinder me for so long but I will be more productive or ask my team for assistance. Despite all of this below is a list of what we have accomplished so far as a group.

- Profile picture is fixed and now shows up
- Courses can be sorted on My Page
- Editing groups do not delete posts and members
- Tutorial toggle is now an icon instead of a drop down menu
- Duplicate sessions are now restricted to reduce data build up

Check out this milestone: <a href="https://github.com/CollaborativeStudy/CS/projects/6"><i class="large github icon "></i>Project 6</a>

## February 1

As you all know, we are still in early stages of development. We have been working to fix the bugs we had at the end of the Fall semester. The more bugs we started fixing the more features we wanted to add. So going down the list you will se these changes are seem very little but they are actually really big! So far the beginning weeks of our second phase have been productive. I was able to fix the bug to add members to groups now. The member must have an account on CS in order to be added too. My team mate, Mariah, was able to create group sessions right on the group session page. Below is the overall progress Collaborative Study has made.

- Members can now be added to groups and deleted from groups! Before this feature was disabled but now you can actually make groups.
- Groups can now create study sessions for that group. This will help organize your study groups with the friends you have made.
- Sessions are now searchable cards by class or by title. So if you are in desperate need of a study session, just search one up and get in there.
- Courses on your profile page can be edited and deleted. This way users can properly show their proficiency in each class.

Check out this milestone: <a href="https://github.com/CollaborativeStudy/CS/projects/5"><i class="large github icon "></i>Project 5</a>
