# Golden Buddies: Bridging Generations, Cultures, and Friendships

## Requirements

- Python 3.x
- Flask
- Flask-RESTful
- Flask-PyMongo
- Flask-JWT-Extended
- pymongo

## Installation

1. Install the required Python packages:

    ```bash
    pip install Flask Flask-RESTful Flask-PyMongo Flask-JWT-Extended pymongo
    ```

2. Update the MongoDB URI and JWT secret key in `server.py`:

    ```python
    app.config['MONGO_URI'] = "your-mongodb-uri"
    app.config['JWT_SECRET_KEY'] = 'your-secret-key'
    ```

## Usage

1. Run the Flask app:

    ```bash
      python server.py
    ```

2. Access the API at `/`.

## API Endpoints

- `/update-user/<string:username>` (PUT): Update user profile.
- `/get-all-users` (GET): Retrieve information about all users.
- `/get-matched-users/<string:username>` (GET): Get users who have accepted match requests.
- `/get-recommendations` (GET): Get users with matching interests.
- `/register` (POST): Register a new user.
- `/login` (POST): User login.
- `/event/<string:event_id>` (GET, PUT): Get or update a specific event.
- `/events` (GET, POST): Get all events or create a new one.
- `/delete-event/<string:event_id>` (DELETE): Delete a specific event.

## Notes

- Ensure that MongoDB is running and accessible.
- This is a basic implementation; consider adding security features and error handling for production.
- 
# Inspiration

In a fast-paced world where generational gaps can sometimes lead to a lack of understanding, **Golden Buddies** draws inspiration from the profound value of intergenerational connections. We believe that everyone has a unique story to tell, and through the sharing of cultures and experiences, we can foster meaningful relationships that transcend age boundaries.

# What it does

**Golden Buddies** is an innovative app designed to bring people from different generations together. It goes beyond the conventional social networking apps by focusing on the cultural exchange between users who may be separated by age but share a common desire to learn and teach about their backgrounds. The app provides a platform for users to connect, share stories, and find companionship in a way that enriches their lives.

# How we built it

Our team passionately crafted **Golden Buddies** using cutting-edge technologies and thoughtful design. The app incorporates intuitive user interfaces to ensure a seamless experience for both younger and older users. We leveraged robust backend infrastructure, including MongoDB for data storage and Flask as the RESTful API framework. The front end was carefully designed using modern web development principles to create a visually appealing and user-friendly interface.

# Challenges we ran into

Building an app that caters to users from various age groups presented unique challenges. Striking the right balance between simplicity and functionality was crucial to ensure accessibility for users of all tech proficiency levels. Additionally, addressing privacy concerns and creating a secure environment for users were paramount challenges that required meticulous planning and implementation.

# Accomplishments that we're proud of

Despite the challenges, **Golden Buddies** stands as a testament to our commitment to fostering connections and breaking down barriers. We are proud to have developed an app that not only brings people together but also promotes the exchange of cultural knowledge and personal stories. The positive feedback from our beta testers reinforces our belief in the app's potential impact on creating lasting intergenerational friendships.

# What we learned

The development of **Golden Buddies** has been a learning journey for our team. We gained insights into the nuances of designing for diverse user demographics and discovered the importance of creating inclusive features. Understanding the unique needs and preferences of both younger and older users enriched our development process and shaped the app into a truly versatile platform.

# What's next for Golden Buddies

As we look ahead, the future of **Golden Buddies** is filled with exciting possibilities. We plan to refine and expand the app based on user feedback, adding features that enhance the overall experience. Additionally, we aim to collaborate with community organizations to further amplify the impact of intergenerational connections. **Golden Buddies** is not just an app; it's a movement toward a more connected and understanding world.

Join **Golden Buddies** today and embark on a journey of cultural exchange, friendship, and shared experiences!
