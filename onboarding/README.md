# Onboarding Guide

[[toc]]

## Intention

*The intention of this Onboarding Guide is to fulfil on the following user stories.*

Personas

* Onboardee = New Joiner
* Onboarder / Onboarding Manager = person setting up New Joiner

As an Onboardee I want a simple step by step process to get set up (that I can do largely on my own) so that I am ready to go (and know i am ready to go)

As the Onboarder I want to know what I need to do for and with the Onboardee and that I've done it all so that Onboardee is set up and supported and I don't miss things out

* Things i need to do before the Onboardee starts their onboarding (e.g. ensure they have a contract)
* Things to do during onboarding
* Things to do after onboarding

## Onboarder

*Note these steps need always be done in the order list. E.g. sometimes getting a formal contract completed may take some time and you can still set up their email and start onboarding*. 

1. **Contract**: Ensure they have a contract set up (and signed) - usually ops will take care of this
2. **GSuite Account and Email**: Create their email account e.g. first.last@domain.com on Google Apps and share the login details via email (part of email creation wizard in google apps)
3. **Onboarding email**: Send them onboarding email to their new org email cc'ing their personal email (if you have it)
4. **Create accounts**: on systems where they can't create themselves
   * Xero
   * Slack

Wait for them to get setup on Systems then ...

1. **Add them to teams**:
    * Trello: add to Org team
    * Gitter: add to relevant channels
    * Slack: add to relevant channels
    * Github: add as a member of the org, add to relevant teams
    * Gitlab: add as a member of the org, add to relevant teams
    * GSuite / Drive: add them to relevant team drives and google groups

### Welcome Email

Subject: Welcome to Viderum/Datopian - next steps in getting you set up

Hi {XXX},

Welcome to Datopian/Viderum.

In preparation for the onboarding call on Monday:

**1. Your Viderum Email**

We have created a Viderum email for you. You should have already received an email about this with details of how to sign in and set your password.

Please do that as soon as possible.

**2. Our onboarding call**

An onboarding call has been scheduled. An invite has been sent to your Viderum calendar and email!

If that time does not work please let us know.

**3. Start inducting yourself!**

We have designed the onboarding process to be largely self-service so you can set yourself up!

Please start working your way through the "Onboardee"  section of the Onboarding:

https://handbook.datopian.com/onboarding/#inductee

Best,

...


[handbook]: https://handbook.datopian.com/
[guide]: https://handbook.datopian.com/guide/

## Onboardee

*We want your feedback as new joiners! Be critical, tell us what does not work, what isn’t obvious!*

1. **Login in to your email account** and read your onboarding email (if you haven't already)

2. **Read the [Handbook main guide][guide]. Note ALL questions that arise in a google doc

2. **Setup accounts on the systems we use**. See below.

3. Add contact details to [Team Phonebook][phonebook] (TODO: work out where we store headshots -- maybe we link)

4. Email the Onboarder that you have accounts set up and details in team phonebook. They will now go and add you to relevant systems ...

5. Wait until you get a response to let you know you are added to relevant systems

6. Read about your work processes for the job you do

5. Go through work “processes” in more detail; This depends on the accountability the Onboardee will assume;
E.g.

    * Work sprints
    * Trello management 
    * Practice on trello (acceptance criteria, checklist, closing issues…)
    * How to take meeting notes on operation meeting notes

7. Do the onboarding quiz

[phonebook]: https://docs.google.com/spreadsheets/d/1hFw3jFHq_TF4m_Z76n0uzBz85UB9Yht4P2IZAPicBOI/edit#gid=129072431

### Systems we use

Create an account on each of these. Please make sure you set up Gravatar first. For items marked with a `*` please add your account id to the phone book.

* Gravatar - https://gravatar.com. We set this up so that your profile picture will show up automatically on your profile on other systems. Add *all* the email(s) you will use on other accounts. For example, if you plan to sign up to Trello with your personal email rather than your organization email then also add that email address to your gravatar.
* Github - https://www.github.com 
* Gitlab - https://gitlab.com/
* Gitter - https://gitter.im/ (we recommend signing in with your github account as it helps in permissions management)
* Trello - https://trello.com/

### Setting up Google Drive

4. Step 6: Practice: Find documents in the google drive 
More practice...

#### Style Guide

Set up google docs to use our default styles: [Handbook Style Guide section][styleguide]

[styleguide]: /guide/#style-guide

### How we communicate

See section in team handbook XXX

https://handbook.datopian.com/guide/#communications

Exercises

* [ ] Say hi on Gitter

### Using the Calendar

You have been given access to create, edit and share in Art Earth Tech Team calendar.

### Tracking time

TODO

### Submitting your invoices and getting paid

* Set up an invoice in Xero
* Setup and invoice with an expense in Xero

### Stand up

* Everyday Standup at 10 am French time in appear.in/artearthtech
* If not meeting, do the Standup in Gitter
* Add ‘+ Standup’ at the end of your Standup so that it’s recorded in the Drive automatically;

### Trello

* [ ] Create a task in trello for practice ...


## Tech Team Onboarding

*Training new Jedis!*

3 parts:

1. Processes and tools
2. Using DataHub
3. Packaging data

### Step I: Processes and tools

Intention: Onboardee is familiar with our work environment and has relevant tooling installed

* [ ] Check: know gitter channel to use by default, know we use team rarely, know how to get bot help, know key bot commands
* [ ] Check: key github orgs: datopian (pretty empty) and datahub stuff which datahq, datasets org for storing datasets
* [ ] Check: can do a standup (do in bot channel and then delete)
* [ ] Check: have they read team guide in detail, have they read about scrum and user stories.
	* Check: have them create a user story ...
* [ ] Coding standards: https://github.com/okfn/coding-standards
* [ ] Have python, node, git etc installed

In addition, we learn about what we can improve in our documentation of processes.

#### Agenda

* Setting up access
  * gitter channels (datahub, dev, team, frictionlessdata, datahubio)
  * github repo and org (datahq for now)
* Processes
  * Do a standup
  * Do a user story
* Small introduction about workflow: boards, issues, milestones, sprint planning
* Relevant tooling: git, python, node, ...
* Coding standards: https://github.com/okfn/coding-standards

### Part II: DataHub

Intention: you can publish data to the DataHub

* have published a sample dataset to your account
* provided feedback on the experience

:::tip
Onboarder: Watch them via screen share (as they download) and have them take notes on this experience (what worked, what didn't)
:::

Agenda:

* Sign up to datahub and follow instructiions
* Command line tool: data-cli - only provide documentation and then have them push sample dataset or file
	* https://datahub.io/docs/getting-started/publishing-data
* data-desktop - only provide documentation (blog post re alpha release)
	* push sample dataset or file

### Part III: Packaging Data

Intention: you are able to curate a new (core) dataset and publish it to DataHub

*This is a task the Onboardee will go away and do on their own once they are briefed*

Agenda

* Introduction about Data Package https://frictionless.io/
  * Specifications https://specs.frictionlessdata.io/
* Know about core data and data curation: http://datahub.io/docs/core-data/curators
* Introduction to automated curation and publishing: Data Package + DataFlows + Github + Travis
	* DataFlows - https://github.com/datahq/dataflows
	* Travis
* **Practice task**: Curate a new dataset (look through registry and select one)
	* Select a dataset e.g. (check these still need doing)
		* Global house prices: https://github.com/datasets/registry/issues/55
		* Exchange rates: https://github.com/datasets/registry/issues/15
  * Check: they know what their task is for next 24h (i.e. package a dataset). What would "done" look like?
  
## Operations Induction Guide

## CRM
We have a group email: office@datopian.com where all emails in regards to Art Earth Tech should be Bcc’d. 
Please note that all previously sent emails will need to be re-forwarded to office@datopian.com to be stored. 
This is a group which you have access to enter; however you will not get notified if someone message to this email (saves you space in your inbox)

## How to store a conversation?
BCC all admin emails to office@datopian.com

## How to find a conversation?
Log in to groups.google.com with your Datopian account 
Click on My Groups -> datopian.com
Search for a conversation by writing name/subject etc in Search Field

## Finances
### Team invoicing
Team must submit their invoices by 7th each month and will be paid by the 11th latest.  For those who haven’t submitted their invoices on time will simply be paid the following month. 

Step 1: Log in Xero with your AET email address and password
Step 2: Click on ‘Dashboard’
Step 3: Scroll down to ‘New Bill’ and click on the button
Step 4: Fill out ‘New Bill’ : 
From  - Your name
Due date - 7th of each month
Reference - Start with 001, following month 002 and so on..
Item - Leave it empty
Description - What are you working on? Could be Admin/Communication/Writing/ or the project you are working on i.e Datahub/Cybergreen/iMed.. 
Account - Could be
322 - Contractor - Project Management
323 -  Contractor - Operations and Administration
324 -  Contractor - Researcher
325 -  Contractor - Construction
326 -  Contractor - Communications
Unit Price - Your total amount paid
Project - Scroll down to the one specific project you have been working on (Please always remember to add project)
Double check you get the correct currency
Add ‘Tax Inclusive’ in the Amounts Are column
Step 5: Click ‘Submit’

## Company Expenses Reimbursement
If you had any company expenses to be reimbursed for
Step 1: Attach a copy of the receipt (expense) by clicking on the A4 paper next to Reference. (Make sure amount, date, merchant are readable)

Step 2: Repeat above procedure but in Description you clearly specify what the expense was for and for what purpose. 

When travelling for work: If  you have expenses in different currencies for that month, convert the expense in XE.com into the currency you are paid in. Add a new line for separate currencies. EG. a bus ticket, two metro tickets and lunch in GBP can be on one line but make a new line for bus ticket and train in euros converted to GBP. 

If you are based in UK, please remember to specify in the ‘Tax Rate’ box; No VAT (we are all self-employed).


