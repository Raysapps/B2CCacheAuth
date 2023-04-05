# B2CCacheAuth

This sample displays the claims in the MainLayout when the user has logged in successfully. The authstate field is initialized in the OnAuthenticationStateChanged handler in the MainLayout.

Please note the following observations:

When a user logs in by signing in the browser, OnAuthenticationStateChanged is triggered and the claims are displayed in the MainLayout.
After closing the browser and restarting the application, the application is still in the logged-in state, but the authstate is not initialized, and no claims are displayed on the MainLayout.
After closing the browser and restarting the application, the application is still in the logged-in state, but the authstate is not initialized, and no claims are displayed on the MainLayout.