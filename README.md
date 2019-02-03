# acnAgent
Travel Agent web app
===================================
Executions steps
===================================
1. Start database on your system.
2. Update the database details in /travel-backend/src/main/resources/application.properties file.
3. Go to front end code directory run node code using "nohup ng serve --port 8080 --host <hostname> &" command.
4. Build your backend spring boot project Run As -> Maven Project and create a jar.
5. Run jar using "nohup java -jar travel-backend-0.0.1-SNAPSHOT.jar >> logs.txt &" command.
6. Web app will be accessable at http://<hostname>:8080 port

===================================
USE CASE
===================================
The increase of machine-driven analytics and the gaining popularity of self-service behaviour, the agency business model is being increasingly threatened. The current and future generation are digital-savvy and comfortable performing research and complex transactions online by themselves, bypassing the agencies and diminishing their revenue. This is a prototype of a online travel agent to solve this problem which can integrate with insurance agency, banks or airlines in future.

===================================
Key Planned Features
===================================
1. The code is divided into 2 parts, front end code written in angular JS CLI 7 and back end code exposing services of travel agency written using java sping boot and hibernate.
2. Social Login(Facebook): Integrated as developer app
3. Register and login
4. Home screen to provide booking info.
5. Currency converter: UI implemented
6. Hosted the front end UI and back end services on AWS along with AWS RDB instance.

===================================
Future Scopes
===================================
1. Email notifications for upcomimg booked plans and upcoming deals.
2. User feeds to be sent to backend service to be saved for analytical purposes.
3. Chat bot.
4. Integrate insurance agents for travel insurance and bank for money conversion and payments.
5. Backend APIs can be integarted with Airlines for complete package deals or hotel bookings.
6. Enhance booking info to provide climatic conditions of the destination.
7. Reviews and blogs
8. Integarting self driven car web app on our app.

