# Kickstarter Project 



- Author: Martin Schiling, Simon Günther
- Dataset: Kickstarter, 220k instances

# Our Business Case: Kickstart Boost!

Consulting for companies that want to raise money via Kickstarter

# Initial Research Questions

* What are the categories to look at?
* What about spotlight? starrable etc? staff_pick?
* Why is America so special? 
* We are looking for customers only in North America
* How did the market develop over time for our categories?
* What are the main cities? What are the worst Cities or States?
* One Example for a horrible business case (from Kansas)
* How can you optimize your financial goal?
* Is there a specific time of the year to end your campain?
* Is there a good day to end it?
* Who submitted the most projects?
* How high is our average pledge in this category? Who do we want to attack as potential investor? (rich, poor, etc.)
* Is it good to have a long description for your product?
* How long should your campain last?
* Does the period matter from time of creation to time of launch?
* Successful serial entrepreneur/s?
* What are our recommendation? What about the almost successful cases? Buckets: What makes cases very successful / successful / almost successful?
* Future Outlook: Expanding in the rest of the world

# Dataset

Description of each column:
- backers_count - number of people who contributed funds to the project
- blurb - short description of the project
- category - contains the category and sub-category of the project
- converted_pledged_amount - amount of money pledged, converted to the currency in the 'current_currency' column
- country - country the project creator is from
- created_at - date and time of when the project was initially created on Kickstarter
- creator - name of the project creator and other information about them, e.g. Kickstarter id number
- currency - original currency the project goal was denominated in
- currency_symbol - symbol of the original currency the project goal was denominated in
- currency_trailing_code - code of the original currency the project goal was denominated in
- current_currency - currency the project goal was converted to
- deadline - date and time of when the project will close for donations
- disable_communication - whether or not a project owner disabled communication with their backers
- friends - unclear (null or empty)
- fx_rate - foreign exchange rate between the original currency and the current_currency
- goal - funding goal
- id - id number of the project
- is_backing - unclear (null or false)
- is_starrable - whether or not a project can be starred (liked and saved) by users
- is_starred - whether or not a project has been starred (liked and saved) by users
- launched_at - date and time of when the project was launched for funding
- location - contains the town or city of the project creator
- name - name of the project
- permissions - unclear (null or empty)
- photo - contains a link and information to the project's photo/s
- pledged - amount pledged in the current_currency
- profile - details about the project's profile, including id number and various visual settings
- slug - name of the project with hyphens instead of spaces
- source_url - url for the project's category
- spotlight - after a project has been successful, it is spotlighted on the Kickstarter website
- staff_pick - whether a project was highlighted as a staff_pick when it was launched/live
- state - whether a project was successful, failed, canceled, suspending or still live
- state_changed_at - date and time of when a project's status was changed (same as the deadline for successful and failed projects)
- static_usd_rate - conversion rate between the original currency and USD
- urls - url to the project's page
- usd_pledged - amount pledged in USD
- usd_type - domestic or international

# Future Work

- Use NLP for analyzing blurps
- Create more sophisticated features
- Get more data for potential timeline analysis


```python

```
