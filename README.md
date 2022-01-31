# Project Proposal

## Team Members

Michael Zhou  
Chengyang Song  
Diana Zhao  
Charlie Cai  
Dana Sun

## Project title

CodeHunt (a coding calendar app)

## What and why?
<!-- What software system would you like to build this semester, and why?  Include a description of what problem the system would solve and why this is important. -->
We will build an information hub for people in computer science field. In today's world, the information overload slows people's productivity. For example, there are many events/contest happening on different cs online contest websites, such as Leetcode, Codeforces, Kaggle, etc. It's time-consuming to keep track of all events by jumping from website to website. So we want to build a webapp to collect and aggregate all the information so that users don't have to open dozens of pages. All they need to do is open our website and see what they are interested in and click the link. This will make the life much easier.

In the future, we will try to add more useful informations in cs field, like job or internship opportunities. And even more powerful features such as letting user self-define the information on any website they want to keep track of.

## For whom?
<!-- Who will this software be for?  These people are your end-users or customers.

Do not make software for imaginary users who do not exist - you must have real people as your initial end-users.  Tell us who they are.  For example, is it for a particular type of business, mass consumer, a campus office, a professor, or friends or family, or ... people just like you.

Understanding who your end-users are, and ideally speaking with some along the way, will help you refine your designs to be suitable for your audience, and understand whether you have succeeded at the end or not. -->
The end-users are NYU Computer Science students. Our plan is to provide limited service to CS department students. We will extend the service to any student seeking Software Engineering related job positions.

Given the intense competition within the computer science field as well as need for experience, CS students would benefit greatly from participating in coding contests and events. Some students don't know where to start looking for such contests, and even if they did, keeping up to date with the events and maintaining their schedule is inconvenient - as stated above. Aiming this specifically to NYU students will enable us to better design our app with what we are familiar with and have/have not learned.

If resources allowed, we will extend the service to the internet.

## How?
<!-- A description of what the system will do from an end-user's perspective.  Be as complete as necessary to fully explain the system, but do not worry about technical implementation - this will be developed in subsequent work. -->
For the information retrival process, we will be using web crawler or retrieval via API. For end-user consumption, we intent on building either a webapp or (maybe) a browser extension that will at the very least hold a list of events happening on the multiple platforms.

From an end user's perspective, this app will simply be a (customizable-to-a-certain-degree) catagorized list of coding events hosted by different websites/platforms/organizations. Once any event has been announced by any website we track, this app will display it with the details such as host, event name, time frame, requirements and rewards etc. Potentially these events can then be displayed by category or by host.

Additional potential features we would like to incorporate are listed below:
- user-specific settings to toggle which websites they want to be notified about
- ability to hide events that users are not interested in
- integration with calendar apps such as Google Calendar or Apple Calendar

## Scope

The general premise of the app is relatively simple, with the only challenge being how we will be able to retieve data (the solution to this may vary depending on the website). However, once we get the essential parts of the project finished, we have a lot of potential for refining quality-of-life, such as the additional features listed above. This, combined with the fact that the project idea is both practical and effective, leads us to believe that it is a good app to work on.
