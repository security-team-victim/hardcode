# Hardcode 2013 #
## Contents ##


## Overview ##
Hardcode is a contest aimed at promoting the importance of security throughout the software development lifecycle.  Contestants will develop open source applications on Google’s App Engine platform that meet a set of functional and security requirements. This competition is open to full-time middle school, high school and college students over the age of 13 around the world.

# Eligibility #
All entrants must currently be full-time middle school, high school or college students over the age of 13.  Participants are encouraged to work in teams with no more than 5 participants per team.  Work by more than 5 participants per team and work done by any anyone who is not a full-time student are not allowed and are grounds for team disqualification.  Other restrictions apply.  Please see the [Official Rules](https://code.google.com/p/hardcode/downloads/list?q=label%3AVersion-2013+label%3AType-Rules+-label%3ADeprecated) for details.

# Timeline #

| **Date / Time** | **Activity** | **Location** |
|:----------------|:-------------|:-------------|
| January 10, 2013 | Contest announcement | http://googleonlinesecurity.blogspot.com/2013/01/calling-student-coders-hardcode-secure.html |
| January 18, 2013 | Contest rules released | https://code.google.com/p/hardcode/wiki/Hardcode2013ContestDescription |
| January 18, 2013 | Competition begins after rules released | Teams work remotely / over Internet |
| February 22, 2013 11:59pm SST(UTC-11) | Deadline for submission of completed application (Round 1 deadline) | [Hardcode2013TeamSubmissionForm](Hardcode2013TeamSubmissionForm.md) and [Hardcode2013IndividualSubmissionForm](Hardcode2013IndividualSubmissionForm.md) |
| March 8, 2013 | Finalists announced | https://code.google.com/p/hardcode/ |
| April 23 - 25, 2013 | Finalists attend [SyScan](http://www.syscan.org/) for final round of competition. | [Syscan ‘13, Singapore](http://www.syscan.org/) |
| April 26, 2013 | Winners announced | [Syscan ‘13, Singapore](http://www.syscan.org/) |

# Prizes #
All finalists that will be invited to [SyScan 2013](http://www.syscan.org/) in Singapore for the final round will receive a cash prize.

| **Place** | **Prize** |
|:----------|:----------|
| First Place | [20,000 SGD](https://www.google.com/search?q=20000%20SGD) |
| Second Place | [15,000 SGD](https://www.google.com/search?q=15000%20SGD) |
| Third Place | [10,000 SGD](https://www.google.com/search?q=10000%20SGD) |
| Fourth Place | [5,000 SGD](https://www.google.com/search?q=5000%20SGD) |
| Fifth Place | [5,000 SGD](https://www.google.com/search?q=5000%20SGD) |

More details are available in the [Official Rules](https://code.google.com/p/hardcode/downloads/list?q=label%3AVersion-2013+label%3AType-Rules+-label%3ADeprecated).

# Contest Format #
Hardcode will consist of two rounds of competition.  Round 1 will be used to determine the finalists who will go on to the final round of competition.

## Round 1 ##
In Round 1, teams work on their applications remotely and submit source code for completed applications by the Round 1 deadline.  This round will start on January 18 with a February 22 deadline for application code submission (see the “Submitting Round 1 Entries” section below for information on how to submit code).  Applications should be developed based on functional requirements as described in the “Application Description and Requirements” section below. Source code for submitted applications will be made available to the public.  Projects will be ranked based 	on how many features have been implemented and how securely they are implemented (see FAQs below for more information).  The top 5 applications will be selected and finalist teams will be invited to compete in the Final round at [SyScan](http://www.syscan.org/) ‘13 in Singapore.  Note that one member of each finalist team must be physically present at [SyScan](http://www.syscan.org/) ‘13 to compete in the final round.

## Round 2 (Final) ##
The second and final round of competition will be held on-site at [SyScan ‘13](http://www.syscan.org/) in Singapore.  Finalists will be given 2 days to fix security bugs identified during Round 1 and incorporate additional functional requirements that will be announced at the event.  On the third day of Round 2, each finalist team will deliver a short presentation and demo about their completed application to a panel of judges.  Additional scoring will be performed based on the number of additional features added and the relative number of security bugs fixed and remaining.  Winners will be announced on the fourth day.

# Submitting Round 1 Entries #
Participating teams must submit a complete application to code.google.com by 11:59pm Samoa Standard Time (UTC-11) on February 22, 2013 (the Round 1 deadline).  Teams must use the the following submission form to submit their application.  Only one (1) submission form is needed for each team.
  * Hardcode2013TeamSubmissionForm

In addition, each individual must complete the following sign up form.  Each person must complete the form for himself / herself.  The sign up form can NOT be used for more than one individual each, and every individual must fill out the sign up form.
  * Hardcode2013IndividualSubmissionForm

**IMPORTANT:  Do NOT commit any code after the Round 1 deadline!  Any team that submits code after the deadline may be disqualified.**

# Round 1 Judging #
Only entries with complete source code that result in fully functional applications will be judged.  Accepted applications will undergo the following:

  * Functional testing based on the “Basic Functional Requirements” section of this document.
  * Functional testing based on the “Optional Functional Requirements” section of this document.
  * Manual penetration testing of the applications for security vulnerabilities and security logic bugs.

Finalists will be chosen based on their performance against multiple criteria.  The criteria in order from most to least significance are:

  1. The completeness and correctness of the application
  1. The security of the application
  1. The number of optional features implemented
  1. The creativity of the implementation

The top **5** teams will be invited to Singapore to take part in the finals.

# Round 2 Details #

Round 2 details such as entry submission, on-site procedures and the judging process will be provided to Finalists.

# FAQ #
Please visit [Hardcode2013FAQ](Hardcode2013FAQ.md) for more information.

# General Requirements #
The following general requirements must be followed.  See the [Official Rules](https://code.google.com/p/hardcode/downloads/list?q=label%3AVersion-2013+label%3AType-Rules+-label%3ADeprecated) for details on contest rules and restrictions.

## Subscription to the Hardcode Mailing List ##
Teams must subscribe to the [hardcode-2013 mailing list](https://groups.google.com/group/hardcode-2013/subscribe) to get updates on contest rules and progress.  Teams that fail to subscribe to this mailing list may miss important updates related to the contest.

## Application Rights and Licensing ##
All participants must agree to open source any application they submit to Hardcode.  code.google.com has requirements for licenses allowed.  In general, acceptable open source licenses include OSI-approved licenses (see http://opensource.org/licenses).

## Programming Languages and Platform ##
Applications must be developed in [Google App Engine](https://developers.google.com/appengine/) using either Python or Java.  Teams are free to use any API that are provided by the Google App Engine framework.  Usage of third party libraries is also allowed; however, it is very important to note that participants will be penalized for any security bugs inherited from such libraries and they will NOT get any points / credit for using existing third party code and/or any code that existed prior to the Hardcode competition.

### Technical details ###
  * The application should work if it is deployed on another Google App Engine application ID. This means that if we download your source code and we deploy in on a new application, it must still work without us having to do anything else.
  * The application must work without any dependencies on external infrastructure (for example, Amazon EC2, other such services), with the exception of those noted in the "Basic Functional Requirements" and the "Optional Functional Requirements" sections of this document.
  * The application should bootstrap from an empty data store with a backup of 250 or more items and 25 or more user accounts. Any email addresses are acceptable for the fake user accounts (eg. user1@example.com, user2@example.com, [...], user25@example.com).
  * All applications (including ones bootstrapped from an empty data store) should include a pair of test administrator accounts as hardcodetest1@gmail.com and hardcodetest2@gmail.com (see Application Description and Requirements for information on administrator accounts).
  * All applications should use the Google App Engine User Service for authentication (it can additionally support the OAuth service).

### Source Code Repository ###
All participants must create their own [google.com account](https://accounts.google.com/) and post their source code to https://code.google.com/p/.  If teams would like assistance in setting up a private workspace to store their source code on [code.google.com](https://code.google.com/p/), they can make a request by using [this form](Hardcode2013PrivateRepositoryForm.md) no later than January 25, 2013.  After that date, please use the normal code.google.com repsitory; however, please note that, in this case, you will be responsible for keeping your own code private from others.

# Application Description and Requirements #
## Application Description ##
Teams must develop a marketplace web application that allows people to organize bartering of academic goods or services in a school setting (e.g., selling used books, supplies, tutoring services).  The Application should support a general marketplace where any Seller can post an Item they want to sell and any Buyer can express interest in or bid on an item.  This Application does NOT include a payment transaction system; the Application connects potential Buyers with Sellers but does not perform actual payment transactions.

## Terms and Definitions ##

| **Term** |	**Definition** |
|:---------|:---------------|
| Application |	The web application as described in “Application Description” |
| Administrator |	A user of the Application who can perform administrative tasks such as deactivating user accounts, view application logs, etc. |
| Buyer |	A user who wants to buy an Item. |
| Item / Items |	An academic good or service (examples include books, lecture notes or tutoring in a particular subject). |
| Purchase |	An agreement between Buyer and Seller on the sale of an Item based on an agreed upon price. |
| Non-Registered User |	A user that does not have a login account on the Application. |
| Registered User |	A user that has a login account on the Application. |
| Registered User ID |	The Application user ID for the Registered User. |
| Seller |	A user who wants to sell an Item. |
| Transaction |	Actions involving both a Seller and a Buyer.  A Purchase is an example of a Transaction. |
| Item Collection |	A landing page where Sellers can group, organize, and display Items (this is an optional feature; see “Optional Functional Requirements”). |

## Functional Requirements Overview ##
Functional requirements are divided into two categories:
  * **Basic Functional Requirements** - include functional requirements all submitted applications should meet.  Teams strive to meet all basic functional requirements.
  * **Optional Functional Requirements** - include additional functional requirements that are NOT mandatory but will allow teams to gain additional points.  Teams can distinguish themselves from others by implementing as many optional functional requirements as possible while maintaining the overall security of their application.  By doing these, a team is more likely to be selected as a finalist.

## Basic Functional Requirements ##
Below are the basic functional requirements for the application.

**NOTE**:  Requirements are NOT ordered by significance.  That is, the order of the requirements does not indicate which requirement is “more important”.

<wiki:gadget url="http://hardcode.googlecode.com/git/iframe.xml" up\_url="https://docs.google.com/document/d/1B8jPlKO-QsMiUwWeWUrP6AKyed\_z1ot4qfhHVgD5P20/preview?rm=demo" width="100%" height="500px"/>

## Optional Functional Requirements ##
Below are the optional functional requirements for the application.

A team can choose to implement any of the optional requirements.  They do not need to be completed in order.  Teams do not need to complete all requirements within a given category (for example, you do not need to complete all requirements under “Item” to get credit); teams can pick and choose which requirement they would like to implement.  In general, implementing more optional requirements increases your chance of becoming a finalist.

**NOTE**:  Requirements are NOT ordered by significance.  That is, the order of the requirements do not indicate which requirement is “more important”.  If you have included additional features to your application that are not listed here, [let us know](https://code.google.com/p/hardcode/issues/entry?template=New+Feature) before the Round 1 deadline, and we will consider giving credit for these (and announce them to other participants). We recommend you to submit your features ideas as early as possible as we might not accept complex new features towards the end of the contest. We may consider partial implementations and determine if any points should be awarded on a case by case basis.

<wiki:gadget url="http://hardcode.googlecode.com/git/iframe.xml" up\_url="https://docs.google.com/document/d/1PPBbdMuznJs4jOfSofC-wgmYb3Yr0UVUKhyVPKnHOFo/preview?rm=demo" width="100%" height="500px"/>