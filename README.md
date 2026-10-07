Using MERN Stack Travel Memory .env file to work with the backend after creating a database in mongodb:
MONGO_URI='ENTER_YOUR_URL' PORT=3001 Data format to be added:
{ "tripName": "Incredible India", "startDateOfJourney": "19-03-2022", "endDateOfJourney": "27-03-2022", "nameOfHotels":"Hotel Namaste, Backpackers Club", "placesVisited":"Delhi, Kolkata, Chennai, Mumbai", "totalCost": 800000, "tripType": "leisure", "experience": "Lorem Ipsum, Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum, ", "image": "https://t3.ftcdn.net/jpg/03/04/85/26/360_F_304852693_nSOn9KvUgafgvZ6wM0CNaULYUa7xXBkA.jpg", "shortDescription":"India is a wonderful country with rich culture and good people.", "featured": true } For frontend, you need to create .env file and put the following content (remember to change it based on your requirements):
REACT_APP_BACKEND_URL=http://localhost:3000 How to run BE Note: Make sure you have the .env file already added
cd backend npm install node index.js How to run FE Note: Make sure you have the .env file already added
cd frontend npm install npm start

From <https://github.com/arjunes101/TravelMemory/blob/main/README.md> 
<img width="734" height="424" alt="image" src="https://github.com/user-attachments/assets/74ee50ad-d4f4-446d-af1c-60cbbbe4e14a" />
