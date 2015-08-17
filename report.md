#ElCurator - The developer's beginning guide

Just like software, this document will rot unless we take care of it. We encourage you to help us on that by giving us your feedbacks.

## What is this document for?

If you are reading this, you probably just arrived in the elCurator's developers team. First of all, welcome, and congratulation.

Because we are aware there is a lot of informations to absorb during your first days, we try to keep this document up to date in order to give you a point of reference concerning our team, our product and our methodologies. You also will get a good idea of what we think a good developer is.

This document is obviously targeting the developers, but we put all our efforts to make it understandable by everybody. If you are curious about what we are doing at elCurator, and even if you are not a developer, this document should still be interesting, and we hope it will statisfy your curiosity.

## An inner-enterprise

It is actually quite complex to explain what is our working environment. What is OCTO Technology and is it related to us? Are we an independant company or not? Who is investing in us? We will try to clarify these points in this chapter.

### What is OCTO Technology?

First of all, we should explain what is exactly **OCTO Technology**. You can find all the informations you need about this company on its [website](http://www.octo.com/en/who-we-are). Even though, we define OCTO Technology as an **IT consulting, design and implementation company**. Founded in 1998, OCTO is now employing 230 people in 5 coutries: France, Brazil, Switzerland, Morocco and Autralia. The OCTO community is mainly made up of IT consultants, and the main activity of OCTO is to guide and help realize its clients' projects.

![Key figures of OCTO Technology for 2014](./images/octo_2014_numbers.png)

There is a way of doing things at OCTO which pushes its employees to think about innovative concepts and develop them from inside the company. **That's how two products were born in the company**:

- [Appaloosa](https://www.appaloosa-store.com/?locale=en) which is a private mobile application store.
- [elCurator](https://www.elcurator.net/en) which is a collaborative curation platform, but we will explain what it is in the next parts of this document.

### From the one day hacking project, to the affiliated company

ElCurator is a product which was **initiated by two consultants of OCTO Technology** in 2012 during a particular day called the OCTO day. This event is happening once a year, and is aimed to let every employees work on whatever they want, as long as it is useful to the company.

That day, **Christopher Parola** - now CEO of the company - started the project with several workmates, and in one day of work, they tried to make a prototype. This was a failure since it wasn't working as expected, and Christopher continued to work on it on his free time. **Jeremy Venezia** - now CTO of the company - joined him several weeks after that, and helped him in his task. The product began to work, and a few consultants at OCTO started using it. With time, more and more people were using it, and Christopher and Jeremy decided to **deploy it to the whole company**. Maintaining the project was taking to much time, and the two consultants asked to be full-time working on it. That's how elCurator began to live, as a project funded by OCTO Technology. In June 2014, the project has been **publicly released** and OCTO Technology started to communicate on it in order to sell it to other companies (mainly to its own clients). In January 2015, the project has been **affiliated**, and it became a company named **elCurator SAS**.

We can say that elCurator SAS is not really a start-up, but more an inner-enterprise, because it really started from the inside of OCTO Technology, but has been directed by two consultants, to then become an affiliate. 

To juridically define it, we can say it is a **simplified limited liability company**, which is what *SAS* is actually meaning. It is an **affiliate** of OCTO Technology as well, since it owns more than 50% of the its capital.

To simplify, **we are developping, selling and delivering, a SAAS (software as a service) product**.

### Our legacy

As we just said, elCurator started living from the inside of OCTO Technology, thanks to its community. Its two creators are former consultants. We are all the time in relationship with other consultants of the company. This is actually a good thing since OCTO has a very resourceful community made of experts of a large range of topics (the [OCTO blog](http://blog.octo.com/) demonstrates it pretty well). This is obviously influencing our way of working together, our methologies, etc... It is like a legacy to us, which is very important and resourceful. We will talk about this in more details in the next parts of this document.

## The product

We talked about the company's situation, but we haven't explained the activity of elCurator. What are we actually doing here? As you must have understood, elCurator SAS is a software company developping and selling a product named elCurator. In this chapter, you will find the informations you need about the product to easily understand and start manipulating it. We think each members of our team should be capable of explaining the product, and talking about it outside our walls.

### The concept

ElCurator is a **collaborative [curation](https://en.wikipedia.org/wiki/Digital_curation) platform**. In other words, our mission is to encourage workmates to share high quality contents in their company, and highlight the best shared contents.

The concept is defined by 3 main steps:

1. **Select** the best contents.
2. **Add** a short description to justify why the content is relevant.
3. **Share** it to a community.

### Why our clients need us?

Since June 2014, when we publicly launched our product, we started recognizing our clients. Obviously, we are targetting medium and large businesses. Our strategy is mainly a B2B (business to business) strategy. Some functionalities are B2C (business to client) oriented, but the goal is always to be more relevant to large companies by being more famous on the market.

So far we identified that our product is a good fit for medium digital and consulting agencies, education organizations, and large banks. For each kind of client, we noticed several needs that we are able to fit:

* **Stop infobesity**. It is nowadays a fact that we receive too many informations by mail at work. If your workmates are sending you their curated content by mail, there are good chances that you ignore it because you have plenty of more important mails to treat. We believe there should be a time for treating mails, and a time for curation in a work day, and that's exactly what elCurator permits to do.
* **Identify and highlight experts**. It can be difficult for managers to see who is expert on what topic. Thanks to elCurator, it is very easy to identify them by checking what they are sharing.
* **Collective knowledge capitalization**. The content of the company is saved by the our platform. ElCurator
* **Continuous formation**. Every workmates can easily reach expert contents and quickly start developing new skills.

### The main features

If you need to work on elCurator, you need to know what are the main features, so you realize what are the main use cases of our product.

Elcurator is made of several tools:

- A **website**, which is the most used platform by our users so far.
- Two **web browser extension**; Chrome and Firefox.
- Two **mobile applications**; Android and iOS.

#### User story

Because features list wouldn't be very attractive to read, let's tell a user story.

Manu is a project manager. He knows its workmates are read plenty of articles on the we every day, but keep it for them. He is desperate because his team as a pretty high turnover, and each time someone is leaving, he knows that all his expertise is leaving with him.

Manu needs a solution. He needs to convince his workmates to share their knowledge alltogether. Most of all, he needs to store this knowledge, so the new recruits can take advantage of it when they arrive in the team.

Searching on the web, Manu types *best curation tool* on Google, and come to the elCurator landing page. It's said it's free for one organization made of less than 20 users. Eureka! Manu clicks on the *'create an account'*.

##### Create an account

![Create an account](images/user_story/elcurator_create_account.png)

There are 3 ways to of openning an account:

1. Using an existing Google account.
2. Using an existing Yammer account.
3. By filling a form.

Manu choose to create an account with Google.

##### First content

![First content](images/user_story/elcurator_first_content.png)

Manu then click on the *+* button to add his first content on the plateform.

![Add an article to read later](images/user_story/elcurator_personal_article_form.png)

On this form, Manu needs to:

1. Put the url of the content he wants to share.
2. Click on the *read later* button to validate and add its articles into the *read later list*

##### The read later list

The *read later list* is a place where Manu can store his personal articles.

![To read later list](images/user_story/to_read_later_list.png)

From here, he can:

1. See how many articles 
