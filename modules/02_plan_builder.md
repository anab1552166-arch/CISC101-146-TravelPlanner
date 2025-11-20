
Module 2 - Plan builder (options/days)

Change log: 2025-11-20 - updated module 2 to include more standardized fields, fallback rules, thresholds, indoor/outdoor bias, and duplication prevention.

Purpose:
This part makes a list of possible activities and then builds each day's plan in a simple way:
> Morning: something close to where you're staying
> Midday: another nearby spot
> Afternoon: A different type of activity
> Evening: A restaurant or maybe even an event if you want.

Activity details: 
Each activity should include:
> Name (what is it)
> Type (museum, park, restaurant, etc)
> Theme (food, culture, nature, nightlife, shopping, etc)
> Duration (how long it takes in hours)
> Cost range (like $10-30 or "free")
> travel time (mins from hotel/lodging)
> Indoor or outdoor
> Accessible (wheelchairs, etc)
> Opening hours
> Ticket required (yes or no)
If some info is missing, use simple defaults:
> Time = 1.5 hours
> cost = mid-range
> travel = 15mins

Picking activities:
For each day:
> Morning: choose something within 15 mins of hotel
> Midday: pick a spot within 20 mins of the morning activity
> Afternoon: choose something with a different theme than morning/midday
> Evening: normally a restaurant but can switch to an event if user wants an event instead
Fixes:
> if no nearby option exists, stretch the travel time a little bit (15 to 20 to 25 mins)
> don't repeat the same activity unless it's a favorite
> Try not to have more than two of the same theme in one day
> Match meals to the budget style (cheap, mid-range, luxury)
> If the season is bad (rain, cold) then prioritize indoor choices over outdoor ones

Loop:
> 1. Look at how many days the trip has.
> 2. For each day:
	> pick a morning activity near the hotel
	> pick midday activity close by
	> pick afternoon activity with a different theme
	> pick evening restaurant or event
> 3. Save the choices and make sure that they don't repeat too much.
