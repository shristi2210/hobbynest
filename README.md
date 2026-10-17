# HobbyNest 🎨

### A platform to explore hobbies, learn new skills, and connect with educators

## About the Project

HobbyNest is a web-based learning platform that I worked on to make discovering and learning extracurricular skills easier. The idea was to create one place where people can explore different hobbies, find educators, join classes, track their progress, and connect with other people who share similar interests.

The platform has two types of users: learners and educators. Learners can explore classes and manage their learning journey, while educators can create courses, manage students, schedule sessions, and track class activity.

## What I Built

- **Explore Classes:** Browse classes by category, search for hobbies, and discover new skills.
- **Learner Dashboard:** Access enrolled classes, saved courses, schedules, and learning progress.
- **Educator Dashboard:** Create and manage classes, view students, track progress, and manage sessions.
- **Authentication:** Sign up, log in, verify email addresses, reset passwords, and manage accounts.
- **Recorded Lectures:** Educators can manage recorded lectures, while learners can access lessons available to them.
- **Progress Tracking:** Track completed lessons, overall progress, and learning streaks.
- **Nearby Meetups:** Discover activities based on location, host meetups, and join events.
- **Messaging:** Learners and educators can communicate through conversations and receive unread-message notifications.
- **Socials Feed:** Share posts, photos, likes, and comments with the community.
- **Nono Assistant:** An AI-assisted chatbot interface that helps users discover classes through conversational searches.
- **Profile Management:** Manage profiles, photos, preferences, and account settings.

## Technologies Used

- HTML for the structure of the application
- CSS for styling and responsive layouts
- JavaScript for application logic and interactive features
- jQuery and browser APIs for dynamic interactions where used
- Supabase Authentication for user authentication
- Supabase PostgreSQL for database management
- Row Level Security (RLS) for controlling access to data
- Supabase Storage for profile, course, and social-post images
- Supabase Edge Functions for optional server-side notifications and account-related operations
- Netlify for deployment

## How the Project Works

The frontend is built using HTML, CSS, and JavaScript without a separate build step. Supabase handles authentication and stores application data in a PostgreSQL database.

When a user signs up, they verify their email, choose a role, and complete onboarding. Based on whether they are a learner or educator, they are directed to the relevant dashboard.

Learners can discover classes, enroll in courses, watch available lectures, track progress, join meetups, and message educators. Educators can publish classes, manage enrolled students, organize lessons, and schedule sessions.

Database policies help enforce access rules so users can interact with the information and features they are authorized to use.

## What I Learned

Working on HobbyNest helped me understand how the frontend, backend services, authentication, and database fit together in a complete web application.

I gained experience working with database relationships, user roles, access control, dynamic interfaces, and features such as messaging, class management, and progress tracking.

I also learned that building a platform is not just about making the pages look good. It is equally important to handle user permissions, validation, data consistency, and the different situations users may encounter while using the application.

## How to Run the Project

1. Download or clone this repository.
2. Create a Supabase project.
3. Open the Supabase SQL Editor and run `database.sql` to set up the database and its security policies.
4. Open `src/js/supabase.js` and configure the Supabase project URL and publishable key.
5. Follow `SUPABASE-SETUP.txt` to configure authentication URLs and email verification.
6. Run the project using a local development server, such as VS Code Live Server.
7. Open `index.html` through the local server and follow the login or signup flow.

Optional demo content can be added using `seed-demo.sql`. Review the setup and testing instructions before deploying the project.

## Future Improvements

I would like to explore more advanced class recommendations, improve the analytics available to educators, and expand the platform's learning and community features.

## Conclusion

HobbyNest was a hands-on project that helped me explore full-stack web development while building something around learning, creativity, and community. It brought together several features that work as part of one platform rather than as separate standalone pages.
