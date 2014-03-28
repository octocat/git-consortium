# Git Consortium Website Product Backlog

### Profiles

* As a site member, I want to describe myself on my own page in a semi-structured way. That is, I can fill in predefined fields, but also have room for a free-text field or two.
  * It would be nice to let this free text be HTML or similar.
* As a site member, I can fill out an application to become a Practitioner.
* As a Practitioner, I want my profile page to include additional details about me.
  * i.e., some of the answers to my Practitioner application.
* As a site member, I can fill out an application to become a Trainer.
* As a Trainer, I want my profile page to include additional details about me.
  * i.e., some of the answers to my Trainer application.
* As a Practitioner or Trainer, when I provide content to the site I want a small graphic associated with the content indicating I'm a Practitioner or Trainer.
  * For example, Amazon's "Top 500 Reviewers" approach.
* As a trainer, I want my profile to list my upcoming classes and include a link to a detailed page about each.
* As a site member, I can view the profiles of other members.
* As a site member, I can search for profiles based on a few fields:
  * class attended
  * location
  * name
* As a site member, I can mark my profile as private in which case only my name will appear.
* As a site member, I can mark my email address as private even if the rest of my profile is not.
* As a site member, I can send an email to any member via a form.
* As a site administrator, I can read practicing or training applications and approve or reject them.
* As a site administrator, I can edit any site member profile.

### News

* As a site a site editor, I can set the following dates on a news item:
  * Start Publishing Date (the date an item becomes visible on the site (perhaps next Monday))
  * Old News Date (the date it stops appearing on the home page)
  * Stop Publishing Date (the date it is removed from the site, which may be never)
* As a site member, I can subscribe to an RSS feed of news (and events? Or are they separate?).
* As a site editor, I can assign priority numbers to news items. Items are displayed on the front page based on priority.

###  Courses and Events

* As a site visitor, I can see a list of all upcoming "Certification Courses." I can page through them if there are a lot.
* As a site visitor, I can see a list of all upcoming "Other Courses" (non-certification courses). I can page through them if necessary.
* As a site visitor, I can see a list of all upcoming "Events."
  * Events are things such as the Git Summit, conferences, free seminars, etc.
* As a trainer, I can create a new course or event. This includes the following information:
  * name
    * For a certification course the name of the class is a dropdown list
    * for others, it is free text.
  * description (HTML)
  * trainer names (multiple selection from a list)
  * start date
  * end date
  * venue name (HTML) and address
  * contact name
  * contact phone
  * contact email
  * a link for more information
  * a link to register
* As a trainer, when I create an Other Course or Event, I am charged a listing fee for that activity.
  * Note: We'll need this to tie into credit card processing.
* As a site administrator, I can create an Other Course (?) or Event that is not charged a listing fee. This is so that the Git Consortium doesn't charge itself for Git Summits that it puts on.
* As a site administrator, I can set the listing fee per Other Course or Event.
* As a trainer, I can update one of my existing courses or events.
* As a trainer, I can delete one of my courses or events.
* As a trainer, I can copy one of my courses or events so that I can create a new one. When copying it I am asked for the date(s) of the new course or event.
* As a site admin, I can delete any course or event.
* As a site editor, I can update any course or event.
* As a trainer, admin, or editor, I can turn a course into an event or an event into a course (in case it was entered in the wrong category).
  * Note: making something a Certification Course will probably require selecting the name of the course from the pre-approved list.
* As a site visitor, I have an advanced search option that lets me fill in a form of search criteria
  * country
  * state
  * trainer name
  * date range
  * word in description
* As a site visitor, when I'm viewing a course I can click on the trainer's name and be taken to the trainer's profile.
* As a site visitor, I can subscribe to an RSS feed of upcoming courses and events.

### FAQs

* As a site visitor, I can read FAQs.
* As a site editor, I can maintain an FAQ section.
* As a site member, I can do a full-text search of the FAQs. (Maybe we want this for any site visitor?)

### Resource

* As a site member, I can download the latest training material and methodology PDFs.
* As a visitor, I can download presentations, PDFs, etc. on Git that I can use.

### Jobs

* As a site member (?), I can scroll through a listing of jobs. (There won't be enough at first to justify search fields.)
* As someone who wants to hire, I can post a "help wanted ad".
* As a site admin, I need to approve each help wanted ad before it gets to the site.
* As a site admin, I am emailed whenever a job is submitted (so that I am aware of it and can decide if I want to post it).
* As a site member, I can subscribe to an RSS feed of jobs available.
* As a site admin, I can edit and delete help wanted ads.
* As a site admin, I want jobs to stop publishing on the site 30 days after being posted.
  * Note: 30 days doesn't need to be configurable at this point. Hardcoding is fine for now.
* As someone who wants to hire, I want to be able to extend an ad for another 30 days (repeatedly) by visiting the site and updating the posting.
  * Note, I can't update it 10 times today and extend the posting 300 days today.
* As someone who has posted an ad that is about to expire, seven days before it expires I want to be emailed a reminder so that I can go extend the ad.
  * Note: This means the ad could have an expiration date 37 days into the future, which is fine.

### Articles

* As a site visitor, I want to read a new article on the front page about once a week.
* As the site editor, I can include a teaser with each article. The teaser shows up on the front page for all to read.
* As a site member who has read a teaser on the front page, I want to read the entire article.
  * Note: We want any site visitor to read articles for now.
* As the site editor, I can add an article to the site.
* As a site editor, I can set:
  * start publishing dates (when teaser appears on front page)
  * old article date (when it disappears from home page)
  * stop publishing dates (when it's removed from site, if ever) for articles.
* As a site editor, I want to be able to designate whether or not an article (or for that matter any piece of info) ever makes the home page... some things will not.
* As the site editor, I have pretty good control over how the article looks.
  * include images and captions, for example.
* As a site visitor, I want the link from the article teaser to take me directly to the body of the article.
  * not to another teaser setup.
* As a site editor, I want to be able to indicate whether an article is publicly available or for members only.
* As a site visitor, I want to be able to read some of your articles.
* As a site member, I want to have full access to all articles.
* As a site visitor, I can do a full-text search of article body, title, and author name.
* As a site visitor, I can subscribe to an RSS feed of articles. (Teasers only?)
* As a site visitor, I can post comments about articles so that others can read them.

### Home Page

* As a site editor, I want to have a prominent area on the home page where I can put special announcements, not necessarily news or articles.
* As a site editor, I'd like to have some flexibility as to where things appear to accommodate different types of content.
* As a site member, the upcoming courses are what I want visitors to notice.
* As a site visitor, I want to see new content when I come to the site.
* As a site visitor, I want to have articles that interest me and are easy to get to.
* As a site editor, I have ideas on how I want the home page to look and feel.
* As a site visitor, I need to know as soon as I visit what on earth Git is, and why it needs an consortium.
* As a site visitor, I want to know as I glance around the home page what on earth a CSM is and why I'd want to be one.
* As a site visitor, I want to be able to get back to the home page quickly and easily.

### Ratings

* As someone who successfully completed a Certification Course (becoming a Certified Git Leader or Certified Product Owner), I am emailed a link to a survey about the course and instructor.
* As a trainer, I want to be assured that no one can submit the same answers multiple time and skew my results.
* As a trainer, I am notified about the results of surveys about my classes. (Questions: After each survey? After a set period of time? Does the trainer get an email or just know to go to the site?)
* As a site admin, I can see the results for each trainer and averages for the class (for all trainers).
* As a site visitor who is considering attending a certification course, I want to see a trainer's rating (either for that course or for all of his or her certification courses combined).
* As a trainer, I want my rating to show up on my profile page.
* As a site visitor, I want to see a list of the most popular items on the site.
  * Note: Not everything has to be considered:
     * we don't need to know the most popular profile
     * it would be useful to a have a "most popular" box that listed the most popular articles, news items, or etc.

### What Is Git?

* As a site visitor, I want there to be a section of the website that teaches me the basics of what Git is.
* As a site editor, I can create the content of the What Is Git section.

### Registry

* As a site visitor, I can view lists on the site of all Certified Git Leaders, Practitioners, and Certified Product Owners.
  * The CSM list has over 5,000 names so a letter-based pagination approach is needed.
* As a CSM, Practitioner, or Certified Product Owner, I can have my name listed in the registry without becoming a member of the site.
  * For example, I take a certification class but never register or let my membership lapse.
* As a trainer who has finished teaching a Certification class, I can load an Excel file (first name, last name, email) into the site.
  * I am prompted for:
    * the trainer names (I may not have trained alone)
    * certification date
    * type of certification (i.e., CSM or CPO)
  * The names are loaded into a pending state and not yet added to the registry.
    * Note: We could have this charge $50 per person right then.
* As a site admin, I can view all classes in a pending state.
* As a site admin who has received proof of payment from a trainer, I can move people in his or her class from a pending state to the registry.
* As a new Certified Git Leader or Certified Product Owner, once my name has been loaded to the registry I am sent an email welcoming me to the Git Consortium and containing instructions on how to register / activate my membership.
* As a site editor, I can edit the content of the email automatically sent to new Certified Git Leaders and Product Owners.


### Membership

* As a company, I can join the Git Consortium by paying a corporate membership fee. This will include uploading items related to corporate membership
  * e.g. company description
  * e.g. a logo of size x by y.
* As a corporate sponsor, my logo is displayed on a "corporate sponsors" page just like at http://www.agileconsortium.org/portal_url/corporatemembers.
  * Note that the display order on that page is random.
* As a corporate sponsor I want my logo to randomly appear on the home page.
  * That is, it rotates among other corporate sponsors.
* As a CSM or CPO who has been approved for Practitioner status (by a site admin reading my submission), I am charged a fee.
* As someone about to become a trainer, I can pay an annual fee.
* As a site administrator, I can set the annual fees for members, Practitioners and Trainers.
* As someone whose membership (of any type) is about to expire, I am sent a reminder and a link through which I can renew.
  * Note: Think about overlapping memberships and prorating.
* As a member with short-term memory problems, I can have the system email me a new password or a password reminder, possibly my username (unless we use email for that), and so on.

### For Trainers Only

* As a trainer, I can read information of relevance only to trainers.
* As a site editor, I can post information in a trainers-only section.

---

This document is based on http://www.mountaingoatsoftware.com/agile/scrum/product-backlog/example/, used with the kind permission of Mike Cohn and Mountain Goat Software.
