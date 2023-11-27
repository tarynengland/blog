---
layout: post
title: ERDs and Schemas
author: Taryn England
categories: misc
---

In the process of working on this assignment I made some mistakes along the way but learned quickly that maybe this concept is not as easy as I had thought it would be. I found it hard to get the schemas in a way that would make the most snese and not have so many things initially in one table that was representing an entity.

...

![Entity-Relationship]({{"/assets/images/Grocery Shopping Full Bckgnd.png"| relative_url}}) 

In the entity relationship I created shown above; I had a lot of attributes coming off the items initially because at first pass that made more sense to me to have all the things that would could pertain to the items entity be it's attribute.

![SQL-Schema]({{"/assets/images/Grocery_Shopping_SQL.png"| relative_url}}) 

However, when it came to making the schema I seperated some of those attributes and made them their own table to kind of simplify the items table itself with what was actually needing to be kept in itself and what might not fully be needed.

...

I find myself still not fully satisfied with the end result as I have a feeling that it could still be better and make more sense if it was done another way. I feel like that there could be many complications with how I currently have it set up becasue it could be confusing how some of the keys are being laid out arcoss. I thing some of the cardinality relationships are not right as that is something that I have trouble with still in knowing how that actually relates one side of the relationship to the other.
