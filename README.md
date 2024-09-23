 Login Screen Implementation in Swift Custom Carousel View

This project involves creating a login screen for an iOS application using UIKit in Swift. The login screen contains a variety of UI elements such as a carousel, a phone number input field, a "Continue" button, and social login buttons. It ensures user-friendly interaction and appropriate handling of events, including keyboard appearance and validation.

Core Components
Logo Image:
A centrally positioned UIImageView that displays a logo.
ContentMode set to .scaleAspectFit for a proportional display.

CarouselView:
A custom view (CarouselView) is used to display images in a horizontally scrolling view.
The page control shows the current index in the carousel.
Images are dynamically updated using the viewModel.

Phone Number Input Field:
A UITextField configured for numeric input with a country flag icon and code (+91).
It includes validation logic to ensure that the phone number is correctly formatted.

Continue Button:
The "Continue" button is disabled by default and becomes active when a valid phone number is entered.
A function is bound to the button to validate and proceed with the login.

Social Login Buttons:
Social media login buttons (Google, Apple, and Email) are arranged in a UIStackView.
Buttons are designed with shadow and corner effects for a smooth UI experience.

Hyperlink Label:
A label displaying terms and conditions with clickable hyperlinks to the respective pages.
Utilizes NSAttributedString for underlined links.

Key Features
Dynamic Layout:
Constraints adjust based on the screen size, ensuring a responsive design across different iPhone models.

Keyboard Handling:
Adjusts the position of the input fields when the keyboard is presented, providing a seamless user experience.
The keyboard hide/show events are managed by NSNotificationCenter.
Validation & Interaction

Phone Number Validation:
The phone number is checked for validity when the user attempts to proceed.
Displays an alert for invalid input.

Gradient Blur Effect:
A blur view with a gradient is shown above the input field when the keyboard appears.
Code Example: Carousel and Phone Input
The carousel view is defined with a page control and dynamically updates based on the viewModel

Conclusion
This login screen implements an elegant, responsive design with thoughtful user interaction. Handling keyboard events, validating input fields, and providing easy social logins all contribute to a smooth user experience. The structured approach to defining UI components ensures that the screen adapts to various devices seamlessly.
