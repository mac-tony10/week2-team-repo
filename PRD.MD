PRODUCT REQUIREMENT DOCUMENT

PRODUCT NAME:FindBack

1.Product Overview
A campus/university platform that enables students
and staffs(teaching and non-teaching) to report
lost items, claim ownership of lost items and also
ensures the safe return of items back to its owner
within the university.

2.Problem Statement
Students and staffs find it hard to recover lost items
because they rely mostly on WhatsApp groups, status
updates, word of mouth and also notice boards to
report lost items and make it known. This kind of 
messages get ignored often in group chats because
most people wont bother because they aren't affected,
or another issue is that the post lacks clear description, 
because of this rightfulmay or may not find it at all and 
even if they get to discover the item, they may face
issues in verfying true ownership.

3.Discover and Research Insights
Participants:Interview with some students across campus

Frequency and Coping Methods:More than half of the students
interviewed reported they misplaced atleast one item 
on campus during the semester (such as ID cards,phone 
chargers etc.)and they relied mainly on posting on hostel,
departmental and other WhatsApp groups.

Gaps in existing solutions:Most of the students who had 
misplaced an item never recovered them, they also agreed 
that messages get buried quickly in group chats and also
finders don't have a proper means of verifying ownership
before handover.

4.Proposed solution
A central platform where registered students and staff
can post lost and found items,search and filter items by 
by category or campus location, and also verify or claim
ownership through questionnares and also keep track of the
recovery status.

5.Target Users
Losers(Students and Staff):Users who are searching for
their lost items or users who post their lost items.

Finders(Students and staff):Users who log in found items
and verifying claims before handover.

Campus Custodians/Administrators(Porters,Security and 
Moderators):
Staff who log items returned to them or the ones found
on campus.

6.MVP Features
Registration and Authentication:University Email sign up
and login with role-based access(Student/Staff vs Admin).

Lost and Found Listing Management:Create, view, and close 
item listing with title, category,location, date, description,
and optional image.

Item Browsing, Search and Filtering:Search by keyword and 
filter by status (Lost vs Found), category,date, and campus
location.

Ownership Verification and Claim Workflow:Claimants answer 
a finder-defined verification question before handover
contact details are unlocked.

In-App Notifications:Alerts when a claim is submitted, 
approved, or rejected.

Basic Listing MOderations:Admin ability to log physical drop
offs and remove spam or duplicate posts.

7.Functional Requirements, User Stories and Acceptance Criteria:
User Registration and Login
  User Story:As a student or staff i want to be able to login
  or register with my university email so only members of the 
  university can use it.

  Acceptance Criteria:
   .System accepts only university email
   .Each user can hold only one account
   .Unauthorised users cannot claim any missing item 

Create Lost and Found Listing
  User Story:As a finder or loser i want to be able to post an
  item with basic details and a verification question so the right
  owner can be identified.

  Acceptance Criteria:
  .Required Fields:Item title, Category, Campus Location, date
  and verification question/answer.
  .Optional Upload: Max of 1 image

Search and Filter Items
  User Story:As a loser i want to be able to search and filter 
  active listings so i can check if my item has been found.

  Acceptance Criteria:
  .Search returns only items matching the keyword, category,
  or location.
  .Results display up to 20 items per page, sorted by newest first.

Claim and verify ownership
  User Story:As a loser, i want to submit a claim so the finder can
  verify i own the item.

  Acceptance Criteria:
  .A user can submit at most 1 claim per listing.

Close Listing
  User Story:As a finder or admin,I want to close a listing after
  handover so it no longer appears in search results.

8.Success Metrics:
.Registered Users:Total verified students and staff signed up on the
platform.
.Active Listings: Number of active lost and found posts created per
week
.Active Losers and Finders: Number of users actively posting or
searching each week.
.Recovery Rate: Percentage of listings resulting in resolved(
successfully returned) items.
.Reported Suspicious Listings: Number of flagged spam posts or disputed
claims.    
