# Cross-Platform Home Assignment - Series Search

The task is to create a mobile application that allows users to search for information about TV series using the TV Maze API, which is public and free to use.

## Requirements
The requirements are quite open; however, the app must be completely responsive and work on any mobile device.

The app should consist of two views: one for detailed information about the series and one for the search and results.

The application can be developed using your preferred cross-platform framework and programming language. Whether you choose Flutter, React Native, Xamarin, or any other cross-platform solution is entirely up to you. The time you spend on this assignment is also at your discretion.

### Must-haves:
- A search screen where the user can enter a query for the [TV maze API].
- The search results should be presented in a RecyclerView or ScrollView (or equivalent in the chosen framework) with the show's name, a summary of a maximum of 2 lines, and the average score on a scale from 1-10 rounded to the closest half number.
- When tapping a result, you should navigate to a more detailed view where the same information is presented in a ScrollView (or equivalent), but without the limitation of 2 lines, and an image from the API.
- The app should resemble the [linked design].

### Nice-to-haves:
- The ability to add favorites, which should be saved locally.
- Search should be triggered when the user hasn't typed for 0.5 seconds to minimize unnecessary API requests.

## Delivery
Create a repository, and when you are done, you share it with us. 

The assignment will be assessed based on the code's readability, structure, and the ability to create a UI matching the design. We prefer clean, self-documenting code that is thoroughly tested. Feel free to reach out if you have any questions about the assignment.

[TV maze API]: https://www.tvmaze.com/api
[linked design]: https://www.figma.com/file/j2HHAOdso9rlz9rZrgqKDS/App-test-for-devs---Series-Search-iOS%2FAndroid?type=design&node-id=0%3A1&mode=design&t=9gVyGY6s6u85c1j3-1
