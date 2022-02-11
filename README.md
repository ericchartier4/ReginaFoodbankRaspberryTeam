

# ENSE 271 Team Raspberries Project Document

## Team Members
Team Raspberries is comprised of:
- Dinesh Dalip [200401946]
- Eric Chartier [200402250]
- Mikayla Peterson [200425538]

## Project Background
The Regina Food Bank has seen a dramatic rise in users of their service, providing made-to-order food hampers, since the beginning of the pandemic. The Food Bank’s current ordering process involves the user calling to arrange a food hamper. Combined with long queue times, this poses a problem where users drop the calls; the client suggests that most of their users hang up after being on hold for around two minutes. According to the client, the number of dropped calls has risen since the pandemic started. Due to the large volume of calls, the Food Bank is unable to handle all the phone calls in a timely manner. The Food Bank also allows for support agencies to batch order food hampers for people, but doing so is not easy, according to the client. Currently, the Food Bank is using Link2Feed as a CRM and booking software. In the current order to delivery flow, there is a chance for information to be duplicated.  

## Business Need/Opportunity
* Opportunity to provide fast and constant engagement for the user to order a food hamper, and arrange pick up and delivery that aligns with their schedule 
* Opportunity to provide easy batch ordering for support agencies 
Automated deduplication 

## Northstar & Carryover Customers
* Northstar Customer: individual Food Bank users, who are deemed to want ease of access to the Food Bank's service and confirmation of their orders
* Carryover Customers: other Canadian or North American Foodbanks who can find utility in our design that would help them give ease of access to their customers

## Project Assumptions
* Most of our users should have internet connectivity; the client pointed out most users have mobile phones that can connect via wifi
* Clients can be able to use our product at any time, and modify their order
Front-end implementation using Wordpress

## Project Constraints
* Connectivity concerns: any product that we create will have to have connectivity with the Food Bank's current online systems. This may prove to be a constraint as we may be limited in what info we can get or send to the other system components. Some examples of these components are:
  * Real-time inventory 
  * User information 
  * Call in hamper order numbers (to synchronize with online hampers)
* Limit to the number of hampers a user can request in a specific time-frame
* The number of hampers that can be prepared for delivery in a specific time-frame
* Lack of Food Bank user testing: we are getting feedback about our designs from the client, who is the CEO of the Regina Food Bank and not primary users which may or may not be biased 
* Wordpress plug in constraint : we are limited by the technology of wordpress, more limitations arise if we consider not to use paid for plug ins
