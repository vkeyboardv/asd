# mideterm

Q: Write the acceptance criteria for this user story, that User Story will be the Definition of Ready
A: 1) Once a photo is uploaded, the system must display a preview to the student before final submission.
2) The system must support common image file types, such as JPEG, PNG, and GIF.
3) The system should clearly specify the file size limit for the photo (4Mb).

Q: Between the user stories can be used only include and extends relationships
A: False

Q: Acceptance criteria detailed describe user story
A: True

Q: FR
Everything except FR will never be described + FR always has a quantifable

Q: Req engineering consist of 
False

Q: External stakeholders should..
True

Q: User Story and Use Case
False

Q: Between the use case and actor
False



# exam

Q: Func req correctly or incorrectly
A: 1) The system shall provide for the users to connect 24/7 to the system - Incorrect
2) The system shall for the user to add, remove and edit profile data - Incorrect
3) The system shall allow registering the user - Incorrect
4) As a guest, I would like to update my profile data - Incorrect
5) The system shall ensure the security of private data - Correct
6) The system generates a login code - Incorrect

Q: Rewrite the below FR according to the EARS
A: 

gpt
Upon receiving a new message, the system shall display a notification to the user.
While the user is logged in, if a new update is available, the system shall show a notification to the user.

Q: 4-6 aspects
A: 1) Conflict of Interest: Different stakeholders may have competing interests
2) Communication Barriers: External stakeholders may have different terminologies or levels of understanding of technical jargon
3) Diverse Perspectives and Needs: Stakeholders often have different priorities and perspectives, which can make it difficult to consolidate their needs into a unified set of requirements.
4) Changing Requirements: External stakeholders' needs may evolve over time, especially in dynamic business environments, making it hard to capture static requirements.

Q: Mistake in user story
Vagueness: "System information" is too vague. It's important to specify what kind of system information the user needs to add or edit.
Purpose of the action: "Validated data" could be more explicit about how the data validation process benefits users or contributes to the overall system.
Role specificity: "Registered user" is broad. Specifying the type of user can help tailor the functionality to the user's needs.

Q:2 different non func requirements:
A: The system shall be operable by users with no specialized training, achieving a 95% success rate in completing core tasks on the first attempt.
The system shall provide context-sensitive help documentation, enabling users to understand and resolve issues within two clicks from the problem area.

Q: NFR

NFR sentence: The app shall maintain user privacy by encrypting personal data both in transit and at rest.

Fit criterion: Data encryption must comply with AES-256 standards.
2nd fit criterion: The app should pass a security audit confirming encryption practices before release.
NFR sentence: The app shall be accessible, supporting screen readers and providing text alternatives for all images and voice prompts.

Fit criterion: The app must meet WCAG 2.1 Level AA accessibility standards.
2nd fit criterion: User testing with accessibility tools must show no critical issues.
NFR sentence: The app shall be available for use 99.9% of the time.

Fit criterion: Monthly uptime reports should confirm at least 99.9% availability.
2nd fit criterion: Downtime must not exceed 10 minutes in a month.
NFR sentence: The app shall respond to user inputs within 2 seconds under normal operating conditions.

Fit criterion: System testing must demonstrate response times of 2 seconds or less for 95% of transactions.
2nd fit criterion: User feedback should not indicate significant performance issues.

Q: 
Clarity: A requirement exhibits clarity when it is easily understandable and free from ambiguity. Each requirement should communicate an idea that is concise and clear to all stakeholders.

Non-compliance example: If a requirement states, "The system should have a fast response time," it lacks clarity because 'fast' is subjective.
Completeness: Completeness means that a requirement is fully stated with all necessary information provided. It includes all the details required for implementation.

Non-compliance example: A requirement that says, "The system should handle user login," without specifying what should happen in the event of a failed login attempt is incomplete.
Consistency: This criterion ensures that no part of a requirement conflicts with other requirements. Requirements should support one another without contradictions.

Non-compliance example: If one requirement states that the system should reject invalid entries while another requires the system to process all entries, there is inconsistency.
Traceability: Traceability allows each requirement to be traced back to its source, and forward to the system elements that satisfy it. It ensures that the origin of requirements is clear and that they are linked to their implementation and testing.

Non-compliance example: A requirement that emerges in the development phase without a clear link to initial project objectives or documentation lacks traceability.
Testability: Testability means that a requirement can be verified as implemented correctly through some form of testing. It should be possible to plan tests based on the requirement.

Non-compliance example: A requirement stating "The system should be user-friendly" is not testable because it lacks objective criteria.
Feasibility: Feasibility refers to whether a requirement can be realized within the project constraints, such as time, budget, and technology.

Non-compliance example: Requiring a small web application to handle the same amount of traffic as a large-scale social media platform may be unfeasible for a small team with limited resources.

Unambiguous: A requirement must be stated in such a way that its meaning is clear and can only be interpreted in one way.

Example of non-compliance: "The software should load quickly." ("Quickly" is subjective and can mean different things to different people.)
Testable: The requirement must be written in a way that can be verified by inspection, demonstration, test, or analysis.

Example of non-compliance: "The system should have a high performance." (Without a specific metric, "high performance" cannot be measured or tested.)
Feasible: The requirement should be possible to implement within the constraints of cost, time, existing technology, and regulations.

Example of non-compliance: "The mobile app should support all existing mobile platforms." (Supporting every existing mobile platform may not be feasible due to technological limitations or prohibitive cost.)
