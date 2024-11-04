### Job 1: Simple User Profile Fetcher
 
##  Description: Create an Android application that fetches and displays a user profile from a mock API. This app will use a simple API to get a user's basic profile information.API Integration:

    Use Retrofit to fetch user profile data from a sample API, such as https://jsonplaceholder.typicode.com/users/1.
    The response should include:
    User's name
    Username
    Email
    Phone number
    Address (street and city)

##  UI for User Profile:

    Design a simple screen that displays the fetched user information.
    Display each piece of user data (name, username, email, phone, address) in a TextView.
    Error Handling:
    Show a basic error message if the data fails to load.

## UI Requirements:

    Use ViewModel and LiveData to manage data fetching and updates.
    Apply the MVVM pattern to keep the data handling separate from the UI.
    Basic data binding can be used to bind TextViews with LiveData from ViewModel.
