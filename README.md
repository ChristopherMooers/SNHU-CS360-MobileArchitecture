# SNHU CS360 – Mobile Architecture and Programming

Android application project demonstrating:

- Secure login authentication
- SQLite database integration
- Full CRUD functionality
- Runtime SMS permission handling
- Zero-inventory notification alerts

## Project Focus
Pharmacy-oriented inventory management application tracking fast-moving inhalation medications.

## Technologies Used
- Java
- Android Studio
- SQLite
- Android SDK

## Reflection
## Application Requirements and User Needs

The primary goal of this application was to design and develop a functional mobile inventory management system that supports secure authentication, database integration, and real-time inventory tracking. The application was designed to address the need for an efficient way to monitor fast-moving pharmacy inventory, reduce manual errors, and provide immediate alerts when stock levels reach zero. By integrating secure login and structured data storage, the app supports both usability and data integrity.

## Screens, Features, and User-Centered Design

To meet user needs, the app includes a login screen, an inventory management screen, and SMS notification functionality. The inventory screen allows users to add, update, and delete items using a clear and consistent layout. UI elements were intentionally spaced and labeled to reduce cognitive load and ensure clarity. The design focused on simplicity and task efficiency, allowing users to quickly assess inventory levels and perform updates without unnecessary navigation steps. This approach supports a user-centered experience by prioritizing accessibility and ease of use.

## Development Approach and Coding Strategies

During development, I applied modular design principles by separating responsibilities across activities and organizing logic clearly within each component. Incremental development allowed me to test features as they were implemented, which reduced debugging complexity. I also implemented runtime permission handling for SMS functionality and ensured proper validation when interacting with the SQLite database. These strategies promote scalability and maintainability and will be valuable in future mobile development projects.

## Testing and Validation

Testing was performed using the Android emulator to validate login authentication, CRUD database operations, and SMS permission handling. I verified that zero-inventory conditions triggered appropriate notifications and ensured the application handled invalid input gracefully. Testing is critical because it confirms that the application behaves correctly in real-world scenarios, not just that it compiles successfully. This process revealed minor layout and permission-handling adjustments that were corrected before finalization.

## Challenges and Innovation

One challenge encountered during development involved configuring runtime permissions and resolving emulator-related issues. Troubleshooting these challenges required reviewing Android lifecycle behavior and refining permission request logic. Additionally, layout constraint adjustments were necessary to ensure consistent UI presentation across screen sizes. Overcoming these issues strengthened my understanding of Android Studio’s development environment.

## Demonstrated Skills and Strengths

The strongest component of this project was integrating authentication, database functionality, and notification handling into a cohesive application. Successfully combining secure login, SQLite integration, full CRUD operations, and SMS permissions demonstrates my ability to apply both technical implementation skills and user-centered design principles in mobile application development.
