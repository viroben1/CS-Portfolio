IT 230 – Module Eight Journal
Application Summary

The application I developed was designed to allow students to register for courses while enforcing business rules such as preventing duplicate registration and limiting total credit hours to nine credits. The goal of the project was to demonstrate my understanding of object-oriented programming, debugging techniques, event-driven programming, and user interface development using both Console and WPF applications.

The application addressed user needs by providing structured course selection, validating input, preventing errors, and displaying updated registration information clearly.

What I Did Well

I did particularly well in implementing validation logic and enforcing the credit limit rule. I ensured that users could not register for the same course twice and could not exceed the maximum allowed credit hours. I also successfully completed and integrated the Course class in the WPF project, overriding the ToString() method to properly display course names in UI controls.

Console vs. WPF Application Design

The Console version focused on logical flow and structured text-based interaction, guiding users step-by-step through course registration. The WPF version introduced a graphical interface with a ComboBox, ListBox, labels, and buttons to create a more user-friendly experience.

The WPF design improved usability by allowing users to select courses visually and receive immediate feedback through UI updates. By validating user selections and providing clear error messages, I ensured the design remained user-centered and intuitive.

Debugging and Coding Approach

I approached debugging by compiling frequently and carefully reviewing error messages in Visual Studio. I tested different scenarios, including invalid selections and exceeding credit limits, to ensure the application handled edge cases properly. I used incremental testing to verify that each section of logic functioned correctly before moving forward.

These strategies will be useful in future development because they reinforce structured problem-solving and attention to detail.

Innovation and Challenges

One challenge was implementing the business logic for enforcing maximum credit hours and preventing duplicate registrations. I overcame this by carefully organizing my conditional logic and maintaining a list of registered courses. I also had to complete missing class functionality and ensure proper interaction between the UI and backend logic.