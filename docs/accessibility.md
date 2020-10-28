---
title: "Accessibility"
permalink: /accessibility/
nav_order: 30
published: true
---

# Accessibility

In this section we will talk about accessibility. The main point of view will be from a web application perspective, but we will briefly look into accessibility from other viewpoints as well. The material consists of text, as well as links to other web sites, and videos, which will also open on external web sites.

Let's begin with a video about design. Even though the video is about kitchen gadgets and their functionality, it also works as a quite a nice introduction to accessibility. In the video, the designer tests the functionality and the usability of kitchen gadgets, to see if there is room for improvement. One of the methods he uses is for testing accessibility, and using the gadgets with his non-dominant hand, which is covered in oil. The reasoning behind this is explained in the video:  

[![Video link to a video where design expert reviews kitchen gadgets](http://i.ytimg.com/vi/w08XDXjJhsQ/maxresdefault.jpg)](https://youtu.be/w08XDXjJhsQ){:target="_blank"}

You do not have to watch the whole video to get the idea, but it's a quite fun video.

## Why is accessibility important?

There are several kinds of disabilities, and they are more common than most people might think. By estimate, 15 to 20 per cent of world's population have some kind of disability. As right to information is a human right, the software we design should also be accessible. For greater detail, watch this short video:

[![Video link to a video for Introduction to Web Accessibility and W3C Standards. Accessible version in the next link.](http://i.ytimg.com/vi/20SHvU2PKsM/maxresdefault.jpg)](https://youtu.be/20SHvU2PKsM){:target="_blank"}


From the following link you can find a more accessible version of the video:
[https://www.w3.org/WAI/videos/standards-and-benefits/](https://www.w3.org/WAI/videos/standards-and-benefits/){:target="_blank"}

You can notice there are quite a variety of accessible versions for one video. Of course, it would probably not be reasonable to have all the possible versions in all the websites in the world, but the link above shows how different versions could be implemented on a web site.

Accessibility is not only taking the disabilites into consideration. Accessible design means also considering the positioning of elements, readibility of fonts and good structure of the software, for example.

## Accessibility guidelines

There are multiple guidelines for accessibility available. We will look at two of them. The content of those guidelines will not be copied to this site, but opening the external links for them is required. 

The first guideline is the W3C Web Content Accessibility Guidelines, or WCAG. It contains very much, very detailed information. Going through all of the information on the page is not enough, but do open a few links on the site as well. Especially the resource link "How to Meet WCAG 2 (Quick Reference)" on the first page is quite interesting. 

You can find the WCAG from the following address: [https://www.w3.org/WAI/standards-guidelines/wcag/](https://www.w3.org/WAI/standards-guidelines/wcag/){:target="_blank"}.

Another important guideline is the Web Accessibility Directive for European Union. It is meant to provide people with disabilities with better access to the websites and mobile apps of public services. The directive is based on the WCAG standard.

The Directive

* covers websites and apps of public sector bodies, with a limited number of exceptions (e.g. broadcasters, live streaming);
* refers to specific standards to make websites and mobile apps more accessible. Such standards require for instance that there should be a text description for images, or that users are able to interact with a website without using a mouse, which can be difficult for some people with disabilities;
* requires the publication of an accessibility statement for each website and mobile app, describing the level of accessibility and indicating any content that is not accessible;
* calls for a feedback mechanism which the users can use to flag accessibility problems or to ask for the information contained in a non-accessible content;
* expects regular monitoring of public sector websites and apps by Member States, and that they report on the results of the monitoring. These reports have to be communicated to the Commission and to be made public for the first time by 23 December 2021.

A quick guide to the directive, from which the list above has been quoted, can be found from here: [https://ec.europa.eu/digital-single-market/en/web-accessibility](https://ec.europa.eu/digital-single-market/en/web-accessibility){:target="_blank"}

The directive is quite a long and hard read, but if you are interested in the legal side, you can find the full directive from the next link: [https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32016L2102&from=EN](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32016L2102&from=EN){:target="_blank"}


## Accessibility principles

To make your web page more accessible, there are a few principles you should follow. The headers of those principles are copied below, but you can find the complete list with details from here: [https://www.w3.org/WAI/fundamentals/accessibility-principles/](https://www.w3.org/WAI/fundamentals/accessibility-principles/){:target="_blank"}

* Perceivable information and user interface
  * Text alternatives for non-text content
  * Captions and other alternatives for multimedia
  * Content can be presented in different ways
  * Content is easier to see and hear
* Operable user interface and navigation
  * Functionality is available from a keyboard
  * Users have enough time to read and use the content
  * Content does not cause seizures and physical reactions
  * Users can easily navigate, find content, and determine where they are
  * Users can use different input modalities beyond keyboard
* Understandable information and user interface
  * Text is readable and understandable
  * Content appears and operates in predictable ways
  * Users are helped to avoid and correct mistakes
* Robust content and reliable interpretation
  * Content is compatible with current and future user tools

Following these principles, our software is more accessible for people with disabilities, but also more usable for everyone. Try to remember these the next time you make a web site. 

Beside these principles, there are tips and tricks in the internet which make the life easier. My favorite example at the moment is the fact about capitalizing hashtags. More info can be found behind this link: [https://www.boia.org/blog/make-your-hashtags-accessible](https://www.boia.org/blog/make-your-hashtags-accessible){:target="_blank"}.

## Accessibility tools

There are multiple tools to make a site more accessible, as there are multiple things to consider. 

### Color blindness

For example, if you page contains infographics, the contrast between different colors needs to be large enough, so that color blind among others can read the graph as well. There are probably multiple options on how to implement this, but I prefer the following tool, originally designed for cartography: [https://colorbrewer2.org/](https://colorbrewer2.org/){:target="_blank"}.

Accessibility for color blind can be tested with various tool for the whole website. One example of such a tool can be found from here: [https://www.toptal.com/designers/colorfilter/](https://www.toptal.com/designers/colorfilter/){:target="_blank"}

### Blindness

Screen readers are tools which are meant for reading out loud the text and the elements from the web site. For them to be able to use your site properly, the components of the HTML have to be well defined. For Android and iOS, as well as macOS and Windows, there are screen readers built in, and you can activate them like follows.
* For Android, follow these instructions: [https://support.google.com/accessibility/android/answer/6007100?hl=en](https://support.google.com/accessibility/android/answer/6007100?hl=en){:target="_blank"}
* For iOS, follow these instructions: [https://support.apple.com/en-gb/guide/iphone/iph3e2e415f/ios](https://support.apple.com/en-gb/guide/iphone/iph3e2e415f/ios){:target="_blank"}
* For macOS, follow these instructions: [https://support.apple.com/en-gb/guide/mac-help/mh40578/mac](https://support.apple.com/en-gb/guide/mac-help/mh40578/mac){:target="_blank"}
* For Windows, follow these instructions: [https://support.microsoft.com/en-us/windows/hear-text-read-aloud-with-narrator-040f16c1-4632-b64e-110a-da4a0ac56917](https://support.microsoft.com/en-us/windows/hear-text-read-aloud-with-narrator-040f16c1-4632-b64e-110a-da4a0ac56917){:target="_blank"}

We will not be demonstrating these tools or their functionality during the lesson, but you can test them out on your own time.

There are of course third party options as well. We will now be testing out one such option, which can be installed for Windows. You can find this tool from: [https://www.nvaccess.org/](https://www.nvaccess.org/){:target="_blank"}

You can find more screen readers and their information from example here: [https://usabilitygeek.com/10-free-screen-reader-blind-visually-impaired-users/](https://usabilitygeek.com/10-free-screen-reader-blind-visually-impaired-users/){:target="_blank"}

### Testing for accessibility

As mentioned earlier by the experts, blindness is not the only kind of accessibility issue we have to take into consideration. To make sure we do things properly, we can test our application for accessibility. There are many tools available for this. One example can be found from: [https://wave.webaim.org/](https://wave.webaim.org/){:target="_blank"}

Even though we try to make our applications as accessible as possible, there might still be some features we forget to take into consideration. Next let's practice this in action.

## Voluntary exercises

Open a screen reader of your choice on this web page. Can you use the page, only navigating with the screen reader. Now close your eyes and do it again. Can you still do it? 

Udacity offers a free short and awesome course about usability. Doing the exercises are voluntary, but I strongly recommend you do them at some point. You can find the course from this link: [https://www.udacity.com/course/web-accessibility--ud891](https://www.udacity.com/course/web-accessibility--ud891){:target="_blank"}


