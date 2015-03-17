# Hardcode 2013 FAQ #




&lt;hr/&gt;



## How do we register for this competition? ##
You need to subscribe to the [contest mailing list](https://groups.google.com/group/hardcode-2013/subscribe), in which we will send announcements and information regarding the contest and you will need to see the basic and optional requirements of the application.

Also, every team member must sign up here, as early as possible in the competition:
  * Hardcode2013IndividualSubmissionForm

And finally, we ask each team to submit to us their application details and implemented features. We recommend you to submit a first draft as early as possible in the competition and edit your responses later on.
  * Hardcode2013TeamSubmissionForm

We will close the signup forms the day the competition finishes. We'll de-duplicate and merge team submissions and score based on that.

## How can I prevent my code from being copied by other teams? ##
You can request a private repository via the following form:
  * Hardcode2013PrivateRepositoryForm

You should be aware that the repository will be made public as specified in the contest description.

## What if our application includes most, but not all of the Round 1 basic functional requirements? ##
We do hope that finished applications will have all of the basic functional requirements and some of the optional functional requirements, but we have no idea how far contestants will actually get; so, you should still go ahead and submit your application!

## Will others know that I participated in Hardcode?  Will my name be made public if I participate? ##
We will only publish the names of finalists.

## Is it better for teams to just build an application with the basic requirements and make sure it’s secure rather than trying to do additional, optional requirements with the risk of missing security bugs or introducing new ones? ##
Security vulnerabilities are only going to subtract points from the features they are in.  In other words, having a vulnerable optional feature is better than having no feature at all.

## Who can we contact if we have questions about the functional requirements or run into other issues during the competition? ##
You can contact us and ask questions [here](Hardcode2013Issues.md).

## Are finalists going to have travel arranged to Singapore? ##
Only one member of each finalist team has to go to Singapore. All finalist teams will be given at least [5 000 SGD](https://www.google.com/search?q=5000+SGD) which can be used to reimburse travel and other expenses. Please note that you might require a Visa to travel to Singapore, visit the [Singapore's government website](http://www.ica.gov.sg/page.aspx?pageid=96) for more information. We will contact finalist teams at the end of Round 1 and work with them directly. Read more about it in the [Official Rules](https://code.google.com/p/hardcode/downloads/list?q=label%3AVersion-2013+label%3AType-Rules+-label%3ADeprecated).

## Why is the prize in Singapore Dollars? ##
The contest will be held in Singapore during the [SyScan 2013 conference](http://www.syscan.org/), and the check prizes will be distributed in Singapore.

## Can I use other open source libraries and web frameworks? ##
You must take into consideration that we will only give credit for code written by your team for the contest.

Please take a look at the basic requirements and see if the open source library or framework you want to use implements any of the features required by the contest. If it does, you should re-implement them yourself.

All Services provided by default by App Engine are OK, meaning that you are free to use the Users Service for authentication, the Data Store for storage, and so on.

Some of the features in the Optional Functional Requirements require the use of third party libraries and services. It's up to you to figure out the details on how to implement and integrate them safely into your application.

Before deciding to use a third party library verify it's license allows you to use it, allows you to open source it, and allows the organizers of the contest to deploy another version of your application for testing.

In general, web frameworks such as webapp2, and django should be acceptable, as well as libraries like angular, jquery, swfobject, and so on.

[Official Rules](https://code.google.com/p/hardcode/downloads/list?q=label%3AVersion-2013+label%3AType-Rules+-label%3ADeprecated).

## What if I don't have a team now? Can I join one later on? ##
Feel free to create a team with only yourself and join a team later on.

When the Round 1 finishes, whichever team you are registered as a participant on the [contest registration site](https://hardcode-2013.appspot.com/), will be the one you'll be officially subscribed to.

## How do I register the members of my team? ##
Go to the [contest registration site](https://hardcode-2013.appspot.com/), and add them using the web interface.

## Can I change teams? ##
You can switch and leave teams any time you want by deleting the membership of the team you are currently participating on (just click "Delete" next to your email in the [contest registration site](https://hardcode-2013.appspot.com/)).

## What if I delete myself from my team? ##
If you accidentally click delete, you can ask someone from your team to add you back.

If you were the only member of the team you can recover the team by going to https://hardcode-2013.appspot.com/new and creating it again if you use the exact same name, as long as you were the original creator of the team.

Be aware that whichever team you are a member of at the end of Round 1 will be the one we'll consider you officially a member of.

## Which browsers should our application support? ##

We will prioritize feature set over browser compatibility, as long as you support one of the major browsers (i.e., Chrome, Firefox, IE, Opera, Safari).

You should keep in mind our ability to view and test your application and how well it will support users on different systems; therefore, a browser that is easily available and supported on multiple platforms (i.e., Chrome, Firefox, Opera) is preferred over one that is generally tied to a specific platform.

It's worth noting that in order for us to perform testing, for optional mobile features, your application should support the latest version of Android and iOS.

## Can Google Cloud SQL be used? ##

Remember we will test your application by deploying your source code on a new application, which you won't know in advance. If it doesn't work, it just won't work.

If you can find a way to setup Cloud SQL in a safe way that will work without us having to create a project, and without us having to tell you the application then that's fine, but we must warn you this is not a straight forward task, and you probably should use your time implementing the features we'll score on.