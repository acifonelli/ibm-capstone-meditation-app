# Meditation User Stories

## Login/Registration Page
### User 1
**Create a new account:**
As a user, I want to register by entering my username, email, and password, so that I can create an account.

**Acceptance Criteria:**    
1. Users can enter valid details and click “Sign Up” to create an account.
2. An error message is shown if any input is invalid or missing.

**Story Points:** 1/10

### User 2
**Login to the application:**
As a user, I want to log in using my email and password, so that I can access my account.

**Acceptance Criteria:**
1. Users can log in with correct credentials and are redirected to their dashboard.
2. An error message is displayed for incorrect credentials.

**Story Points:** 1/10

### User 3
**Raise error on incomplete form:**
As a user, I want to receive feedback when I attempt to sign up or log in without entering details, so that I can fix the errors.

**Acceptance Criteria:**
1. Error messages are displayed for missing fields on sign-up or login attempts.

**Story Points:** 1/10

### User 4
**Store preferences:**
As a user, I want my details to be stored in local storage, so that my data persists between sessions.

**Acceptance Criteria:**
1. User details are saved in local storage after registration and used for authentication during login.

**Story Points:** 1/10

## Home Page
### User 1
**Personalized greeting:** As a user, I want a personalized greeting with my name and a title, so that I feel welcomed and encouraged to meditate.

**Acceptance Criteria:**
1. Display “Hello, <username>” followed by the title “Find your perfect meditation.”

**Story Points:** 1/10

### User 2
**Popular meditations:** As a user, I want to see popular meditation cards, so that I can explore options based on my preferences.

**Acceptance Criteria:**
1. Display cards with images, titles, descriptions, categories such as calmness, relaxation, and durations such as 10 or 15 minutes.

**Story Points:** 3/10

### User 3
**Daily meditations:** As a user, I want a daily featured meditation, so that I can quickly access a recommended session.

**Acceptance Criteria:**
1. Showcase one meditation with an image, title, category, and duration in a dedicated section.

**Story Points:** 3/10

### User 4
**Easy navigation:** As a user, I want intuitive navigation icons, so that I can easily move around the app.

**Acceptance Criteria:**
1. Display a logo in the top-left corner and a settings icon in the top-right corner for navigation.

**Story Points:** 1/10

## Meditation Details Page
### User 1
**Meditation description:** As a user, I want an “About” section for each exercise, so that I can understand its benefits and purpose.

**Acceptance Criteria:**
1. Display a brief description of the exercise, explaining its focus and stress-reducing benefits.

**Story Points:** 2/10

### User 2
**Meditation instruction:** As a user, I want an “Instructions” section for each exercise, so that I can perform it correctly.

**Acceptance Criteria:**
1. Provide step-by-step guidance on posture and breathing techniques for the exercise.

**Story Points:** 2/10

### User 3
**Add to favorites:** As a user, I want an “Add to Favorites” button, so that I can easily save an exercise for future practice.

**Acceptance Criteria:**
1. Include a prominent “Add to Favorites” button at the bottom of the page.

**Story Points:** 2/10

### User 4
**Nagigation and Share:** As a user, I want navigation icons for sharing and going back, so that I can easily manage the exercise page.

**Acceptance Criteria:**
1. Display a back icon and a share icon at the top of the page for easy navigation.

## Favorites Page
### User 1
**Favorite button:** As a user, I want to add an item to my Favorites, so that I can save activities or articles I like for quick access later.

**Acceptance Criteria:**
1. A heart icon with the text “Add to Favorites” is displayed next to each item.
2. The outlined heart indicates the item is not in Favorites.
3. Tapping the button adds the item to the Favorites list, updates the button text to “Remove from Favorites,” and changes the heart icon to filled.

**Story Points:** 2/10

### User 2
**Remove an item from favorites:** As a user, I want to remove an item from my Favorites, so that I can manage my saved content.

**Acceptance Criteria:**
1. The “Remove from Favorites” button with a filled heart is displayed for items already in Favorites.
2. Tapping the button removes the item from the Favorites list and reverts the heart icon to outlined.
3. Users can add or remove items anytime, and the button text updates accordingly.

**Story Points:** 2/10

### User 3
**Favorites screen:** As a user, I want a “My Favorites” screen, so that I can view and manage all my saved items in one place.

**Acceptance Criteria:**
1. The “My Favorites” screen displays a list of saved items with their title, category, and duration.
2. Users can tap any item to view details or start the activity.
3. The Favorites list remains organized for easy browsing and quick access.

**Story Points:** 2/10

## Remainders Page
### User 1
**Set remainder:** As a user, I want to view the calendar for the current month and navigate between months, so that I can easily select dates for reminders.

**Acceptance Criteria:**
1. Display the current month with all the days visible.
2. Provide navigation arrows to move between months.

**Story Points:** 4/10

### User 2
**Set date and time for remainder:** As a user, I want to select a date and time for a reminder, so that I can schedule it properly.

**Acceptance Criteria:**
1. Display a default text “Selected Date: None” and “Selected Time: 20:44” to indicate no date has been selected but a time is chosen.
2. Allow users to select a specific time and date.

**Story Points:** 4/10

### User 3
**Future or recurring remainders:** As a user, I want to add a reminder after selecting a time, so that I can schedule it for a future date and time.

**Acceptance Criteria:**
1. After selecting a time, users can click the “Add Reminder” button to schedule the reminder.

**Story Points:** 6/10

### User 4
**Manage remainders:** As a user, I want to see a list of all my reminders, so that I can manage them easily.

**Acceptance Criteria:**
1. Display a list of all reminders with the selected date and time.
2. Provide an option to delete a reminder by clicking the red “Delete” button next to it.

**Story Points:** 3/10

## Share Page
### User 1
**Share exercise:** As a user, I want to easily share recommended exercises with friends or family, so that I can help others discover helpful activities.

**Acceptance Criteria:**
1. Provide a clear share button/icon on the exercise detail page for easy sharing.
2. Allow users to share exercises via multiple platforms (e.g., social media, email, or messaging apps).

**Story Points:** 3/10

## Logout Page
### User 1
**Logout:** As a user, I want a clear and visible logout button, so that I can easily log out of my account when I’m done using the app.

**Acceptance Criteria:**
1. Display a clear and visible “Logout” button in the app.
2. Tapping the button logs the user out and redirects them to the login page.
3. User session data is cleared upon logout to ensure secure access.

**Story Points:** 2/10

## Settings Page
### User 1
**Switch theme:** As a user, I want to switch between light and dark themes, so that I can reduce eye strain and customize the app’s visual experience.

**Acceptance Criteria:**
1. Provide a “Theme” toggle or switch in the settings section for light and dark mode options.
2. Allow the user to switch between light and dark mode seamlessly.
3. The theme should change immediately without needing to refresh or restart the app.

**Story Points:** 1/10
