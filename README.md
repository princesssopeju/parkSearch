
## ParkSearch
ParkSearch is a full-stack web application that helps users find parks near their location using the Google Maps API. This project was developed to provide real-time, location-based park recommendations, enhancing the user's ability to explore and discover green spaces nearby.

## Features
**Real-Time Location Search:** Utilizes the Google Maps API to fetch and display nearby parks based on the user's current or specified location.
**Responsive Design:** Built with Bootstrap and JavaScript, ensuring a seamless experience across desktop and mobile devices.
Efficient API Integration: Effectively manages API keys and handles CORS issues, ensuring smooth and secure communication with the Google Maps API.
**Deployed on Heroku:** The application is live and accessible on Heroku, demonstrating a successful end-to-end deployment process.

## Technologies Used
**Back-End:** Node.js, Express.js
**Front-End:** HTML, CSS, Bootstrap, JavaScript
**APIs:** Google Maps API (Geocoding and Places)
**Deployment:** Heroku
**Environment Management:** dotenv for secure management of API keys

## Screenshot


![Screenshot 2024-08-13 062926](https://github.com/user-attachments/assets/e7e19340-0fa5-463e-b371-ca62d81f97ff) ![Screenshot 2024-08-13 062942](https://github.com/user-attachments/assets/3f6996cb-ca47-4f1e-b283-52559a7fa8b8)



## Demo




## How it works

**Search Functionality:** Users can enter their location or allow the application to detect it automatically. The app then uses the Google Maps Geocoding API to convert the location into geographic coordinates.
**Park Recommendations:** The coordinates are sent to the Google Maps Places API, which returns a list of nearby parks. The app processes this data and displays it to the user, including park names, addresses, ratings, and photos.
**Mobile and Desktop Compatibility:** The responsive design ensures that the application is fully functional and visually appealing on both desktop and mobile devices.

