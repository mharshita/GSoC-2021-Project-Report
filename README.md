# User Story - Improvements and New Features

![User Story](./assets/user_story.png)

## Project Summary

**User Story** is a **product management tool** which aims to design and present a scalable backend infrastructure that delivers a web interface allowing users to request new features and report bugs in an easy and intutive way. Users can simply use the request templates provided or write their own descriptions in which they are requested to breifly describe the feature request or bug report. Users can attach the files the files with the request to explain what they want. The admins can then resolve, close and revise these requests. Users can comment and vote for the existing requests to move them to priority. Users can simply share the stories to social media platforms (Twitter and LinkedIn) or copy the story link. This can also serve as an efficient feedback and response mechanism which is critical for any organization to improve and make progress. Thus, it potentially becomes another reusable open source project for EOS. Simply, its a **feedback cum feature request management system**.

## How it works

![workflow](./assets/user_story_workflow.png)

## My Contributions

- Added a feature to add mentions functionality for comments and comment replies.

![mentions](https://media.giphy.com/media/uANwumKIaL575o9azI/giphy.gif?cid=790b761182cdcf084342583e390d4be102fc1a06e35a6343&rid=giphy.gif&ct=g)

- Added a feature to share stories to social media platforms or copy story link.

![share](https://media.giphy.com/media/xskyYME7VFoKFLQd6J/giphy.gif?cid=790b7611407024c419d2777300ce6cd380c2c2720af9e63d&rid=giphy.gif&ct=g)

- Refactored graphql queries.
- Added attachments feature for comments.

![attachments](https://media.giphy.com/media/t5UxnysR87Ov9aT4VR/giphy.gif?cid=790b761187e4ff0fdf3f5073be7d8d767b2eef778749da09&rid=giphy.gif&ct=g)

- Updated tests.
- Added gallery feature that allows to show attached images in full screen mode and also provides a carousel if the number of images is more than one.

![gallery](https://media.giphy.com/media/DiXHwUZ1h8uzrsDCcM/giphy.gif?cid=790b7611bd8041edd6b519627fdebcfafb70bdf590bbe76b&rid=giphy.gif&ct=g)

- Priority labels and story creation date is now showing up on home page.
- Added filter that sorts stories based on priority.
- Revamped the Story Page.
- Integrated eos-icons-react library to User Story.
- Fixed some bugs.

## Weekly Check-ins and blogs

It's been a great journey with Python Software Foundation. Right from the very first beginning, I have written blogs and weekly check-ins on alternate weeks. All of them can be found [here](https://blogs.python-gsoc.org/en/mharshitas-blog).

## My Code Contributions

Here are all the Pull Requests that I have made during GSoC.

[Here is the link to all of my Pull Requests](https://github.com/EOS-uiux-Solutions/user-story/pulls?q=is%3Apr+author%3Amharshita).

### Some of my major contributions are :

| S No. |   Pull Request     |
|  ---  |       ---          |
| 1 |[Added Mentions Functionality](https://github.com/EOS-uiux-Solutions/user-story/pull/21)|
| 2 |[Added Feature to copy and share story link](https://github.com/EOS-uiux-Solutions/user-story/pull/26)|
| 3 |[Refactor GraphQL Queries](https://github.com/EOS-uiux-Solutions/user-story/pull/39)|
| 4 |[Refactor GraphQL Queries for Vote.js file](https://github.com/EOS-uiux-Solutions/user-story/pull/42)|
| 5 |[Adding Attachments feature for comments](https://github.com/EOS-uiux-Solutions/user-story/pull/48)|
| 6 |[Adding Gallery feature for Display of attachments](https://github.com/EOS-uiux-Solutions/user-story/pull/66)|
| 7 |[Revamped Story Page](https://github.com/EOS-uiux-Solutions/user-story/pull/76)|
| 8 |[Added Priority labels, story creation date and priority filter on Home Page](https://github.com/EOS-uiux-Solutions/user-story/pull/79)|
| 9 |[Integrated eos-icons-react Library](https://github.com/EOS-uiux-Solutions/user-story/pull/84)|

## Future Work

- Personalised e-mail notifications for users and admins.
- Quick chats and meetings for admins and users to plan and discuss ideas and stories.
- Migration to TypeScript to add static types.
- Enable admins to go live via platform to interact with users and understand their needs.
- Integration of User Story with tools in our existing workflow like Slack and GitHub.

## Acknowledgement

I am really thankful to my GSoC mentors for all the care, motivation and support. For guiding me and helping me whenever I got stuck. I got to learn a lot! Thanks for providing the best open source experience of my life :)
