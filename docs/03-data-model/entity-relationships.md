# docs/03-data-model/entity-relationships.md

# Entity Relationships

## People Relationships

Person belongs to Household.

Person can be:

- Member
- Visitor
- Staff
- Volunteer
- Donor
- Parent/Guardian
- Student
- Child

## Organization Relationships

Organization has many Campuses.

Campus has many:

- Departments
- Ministries
- Events
- Facilities
- Staff
- Volunteers
- Cost Centers

## Financial Relationships

Organization has one Chart of Accounts.

Campus can have many Cost Centers.

Ministry can have a Budget.

Purchase Requests connect to:

- Ministry
- Cost Center
- Vendor
- Budget
- Purchase Order
- Accounts Payable

Donations connect to:

- Donor
- Fund
- Campaign
- General Ledger

## Ministry Relationships

Member can join Small Groups.

Member can enter Discipleship Pathways.

Volunteer can serve in Ministry Teams.

Sermons connect to Services, Media, Scripture Tags, and Series.

Events connect to Facilities, Registrations, Payments, Volunteers, and Communications.