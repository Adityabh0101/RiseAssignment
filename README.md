Responsive Design:
I used CSS Grid Layout to make sure the dashboard adjusts to different screen sizes (desktop, tablet, mobile).
I added media queries to ensure the layout changes smoothly for different screen widths.

Form Validation:
I made sure that users can't submit empty forms and that the data entered is correct.

Modular Components:
I broke the dashboard into reusable parts like Navbar, Sidebar, MainArea, Phase, and Timeline. This makes the code cleaner and easier to manage.

Data Structure Optimization:
I organized the Sidebar and Timeline data into arrays, which helps in rendering elements more efficiently and improves performance.

Technologies Used:
React.js for building the frontend.
Tailwind CSS for styling (with a bit of custom CSS).
FontAwesome for icons.
React Dropzone for handling file uploads.
React-Hook-Form for form validation.

Approach and Structure

App Component:
The main component that holds the entire dashboard layout, including the Navbar, Sidebar, MainArea, and Timeline.

Navbar:

A navigation bar with icons for notifications and user profile. It also shows the logo and title.
Sidebar:

A vertical menu with links like Dashboard, MyCases, and Activities. I used an array to store the sidebar links for better performance.
Main Area:

This section shows dynamic content, like the Timeline and Claimbox, which tracks the progress of current claims.

Timeline:
A step-by-step tracker that shows progress. Each phase is styled based on its completion.

Steps Taken:

Ensuring Responsiveness:
Making the dashboard look good on all devices was a challenge, but I used CSS Grid and media queries to make the layout adjust to different screen sizes.

Form Validation:
I spent some time making sure file uploads worked properly. I used React Dropzone to handle file drops and validated that the files were the right type and size.

Dynamic Content Rendering:
By storing the Sidebar and Timeline data in arrays, I was able to render the content dynamically, which helped improve performance.

Desktop Screenshots
![Screenshot 2024-12-21 000112](https://github.com/user-attachments/assets/57883178-4e83-465f-be54-7a40c7dfef61)
![Screenshot 2024-12-21 000256](https://github.com/user-attachments/assets/65c4ce25-88ad-4264-86f4-a311c4f3fa26)

Phone ScreenShots
![Screenshot 2024-12-21 000140](https://github.com/user-attachments/assets/c7b13fdc-fad2-46d8-bb42-c7a56b18b5f5)
![Screenshot 2024-12-21 000150](https://github.com/user-attachments/assets/4f726778-a710-4b00-823e-2bb007e1d866)

Ipad Screenshots
![Screenshot 2024-12-21 000215](https://github.com/user-attachments/assets/2ec3e454-8e17-4936-bdb0-9d5d854a6322)
