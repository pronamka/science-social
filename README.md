# Science Social

*A showcase Flask project demonstrating user authentication, file processing, social features, interest-based search, and an admin review workflow.*

---

## About This Project

This is a personal pet project built to demonstrate backend and full-stack development skills using Python and Flask.
It is not intended to be installed or deployed as-is.
Instead, the repository serves as a code sample showing my ability to design and implement:

* User systems with email verification
* Article uploading and processing
* PDF/DOCX handling with automatic conversion
* Personalized content search
* Social interactions (likes, follows, comments)
* Analytics for authors
* Admin moderation workflows

---

## Feature Overview

### User Accounts & Email Verification

* Register with email + password
* Receive a confirmation email
* Access user features after email verification

### Article Submission & Review

* Upload articles as PDF or DOCX
* DOCX files are automatically converted to PDF
* Articles enter an admin review queue
* Admins approve or reject articles before publication

### Article Feed

* Main page lists all published articles
* Newest uploads appear first
* Open and read articles directly in the app

### User Interests & Personalized Search

* Users define their areas of scientific interest
* Search results become more relevant

###  Social Features

* Like and dislike articles
* Comment on articles
* Subscribe to other authors

### Author Analytics

Authors can view statistics for each article:

* Total views
* Likes & dislikes
* Number of comments

---

## Tech Stack

* Python + Flask
* Flask-Mail for email confirmations
* Flask-Admin for admin moderation workflow
* PyPDF2 & docx2pdf for PDF conversion
* HTML/CSS/JS for frontend
