FoodBank - Annam
Zero Waste, Zero Hunger

This Pandemic has taught us a lot. 

1. Food Providers like Restaurants/Events submit their food surplus with quantity
2. App invokes the API Hosted on Cloud
3. API processes the message and puts an event in Streams
4. This event is picked by a functions which processes the event
5. Processed event performs operation, which it updates the FoodBank DB.
6. Every updated event has to be also communicated to user hence its written back to stream on different topic
7. API processes this topic for messages
8. Invokes the notification to Provider or Consumer accordingly
9. Notification is delivered to App
10. Food Consumers can initiate claims once its available in App
 
