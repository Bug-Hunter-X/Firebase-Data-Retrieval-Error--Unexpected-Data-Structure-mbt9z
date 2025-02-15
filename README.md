# Firebase Data Retrieval Error: Unexpected Data Structure

This repository demonstrates a common issue when working with Firebase Firestore: errors arising from unexpected data structures or security rules.  The provided code examples showcase how to handle potential data inconsistencies and improve error management. The primary issue highlighted is accessing nested data that may not always be present, leading to client-side errors. The solution implements thorough data validation and error handling to prevent unexpected application behavior.

## How to Reproduce

1. Clone the repository.
2. Set up a Firebase project and configure the necessary authentication and Firestore rules.
3. Run `npm install` to install dependencies.
4. Execute `bug.js` to observe the error condition. The error is dependent upon the structure of the data in your firebase instance, ensuring the path `users/${userId}/profile/address/street` does not exist will result in the error.
5. Execute `bugSolution.js` to see the implemented solution.
