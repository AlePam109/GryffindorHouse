# GryffindorHouse
CHOPS AppSec Learning Exercises
Meet with Albus Dumbledore (Hogwarts CEO & Acting CISO)
It is early spring and you have been called into an emergency meeting with the CEO and
acting CISO of Hogwarts, Albus Dumbledore. You remember a few months ago he
shared a memo to all the company expressing his frustration with how customer data was
being handled and shared internally, and how the new Magic & Mystics Regulations
(MMRs) going into effect force Hogwarts to significantly change business operations.
Mr. Dumbledore wastes no time sharing that Hogwarts has still not yet been cleared as
“fully compliant” with the new MMRs. This is unsettling news, because everyone also
knows that Hogwarts is preparing to host the Quidditch Olympic Festival next Spring and
expecting crowds in the tens of thousands to come! Mr. Dumbledore is very concerned
about ensuring Festival attendee data is safe & secure across the entire event landscape.
After all, no one wants a repeat of the Alohomora ransomware event that nearly took
down Gringotts in 2021 and left everyone Stupefied.
You lead the team that is responsible for the event mobile app that will be used during the
festival. Its purpose is to promote fan engagement before, during and shortly after the
festival. Users are expected to have this as their main trusted source of information for
scheduling, event access, announcements, news, tickets, check-in, VIP access and
payments. Dumbledore turns and asks the question you knew was coming: How are you
ensuring compliance with the MMRs - particularly the following aspects of it:

Consumers’ Right to Delete Personal Information
(a) A consumer shall have the right to request that a business delete any personal
information about the consumer which the business has collected from the consumer.
(b) A business that collects personal information about consumers shall disclose, the
consumer’s rights to request the deletion of the consumer’s personal information.
(c)(1) A business that receives a verifiable consumer request from a consumer to
delete the consumer’s personal information pursuant to subdivision (a) of this section
shall delete the consumer’s personal information from its records, notify any service
providers or contractors to delete the consumer’s personal information from their records,
and notify all third parties to whom the business has sold or shared the personal
information to delete the consumer’s personal information unless this proves impossible
or involves disproportionate effort.
  (2) The business may maintain a confidential record of deletion requests solely for the
purpose of preventing the personal information of a consumer who has submitted a
deletion request from being sold, for compliance with laws or for other purposes, solely
to the extent permissible under this title.
  (3) A service provider or contractor shall cooperate with the business in responding to a
verifiable consumer request, and at the direction of the business, shall delete, or enable
the business to delete and shall notify any of its own service providers or contractors to
delete personal information about the consumer collected, used, processed, or retained by
the service provider or the contractor. The service provider or contractor shall notify any
service providers, contractors, or third parties who may have accessed personal
information from or through the service provider or contractor, unless the information
was accessed at the direction of the business, to delete the consumer’s personal
information unless this proves impossible or involves disproportionate effort. A service
provider or contractor shall not be required to comply with a deletion request submitted
by the consumer directly to the service provider or contractor to the extent that the
service provider or contractor has collected, used, processed, or retained the consumer’s
personal information in its role as a service provider or contractor to the business.
You and your team need to convince Dumbledore (and eventually that nasty auditor
Voldemort) that your app is secure and customer data is safe. He does not want
Hogwarts to end up looking Riddikulus.
The team realizes a picture is worth 1000 spells so you decide a threat model may be the
best way to communicate your design and allow you to talk through your plans.

Your Task:
  1. Consider the entire event application. It includes things like a live schedule (that
updates as changes are made), a community aspect (so attendees can connect to one
another), general information on teams and basic biography information for athletes.
The ability to see availability, buy tickets, and check-in for specific events is a must. If
customers purchase VIP levels, these need to be accounted for as well. You also have
information on the various vendors that you will have as well as selected sponsor vendors
that paid to advertise to attendees through the app. Make a listing of all the various
parts of your application and how you believe they are connected to one another.
Remember to consider possible third-parties like payment systems and security agencies.
  2. Consider the minimum kinds of information you believe you NEED to collect from
attendees and how you might want to store and leverage it. Do you want it all in one
place? Who else should have access?
  3. Using what you have from 1 and 2 above, construct a basic threat model for your
event app that shows the various parts, connections and protections. Leverage what you
learned from previous CHOPS Modules for this. Bring this model to the workshop
Saturday.
