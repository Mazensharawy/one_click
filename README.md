Usage
Login Screen:
Enter email/password or use Google Sign-In to log in.
Click "Don’t have an account? Sign Up" to navigate to the sign-up screen.
Sign-Up Screen:
Enter email/password to create an account.
Click "Already have an account? Login" to return to the login screen.
Wallet Page:
Displayed after successful login or sign-up.
Dependencies
firebase_core: ^2.24.2
firebase_auth: ^4.16.0
google_sign_in: ^6.2.1
Troubleshooting
Google Sign-In Fails:
Ensure SHA-1 is correctly added to Firebase.
Verify google-services.json is in android/app/.
Firebase Not Initialized:
Check that await Firebase.initializeApp() is in main.dart.
Navigation Issues:
Confirm WalletPage is correctly defined in wallet.dart.
Contributing
Fork the repository.
Create a feature branch (git checkout -b feature/new-feature).
Commit changes (git commit -m "Add new feature").
Push to the branch (git push origin feature/new-feature).
Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For questions or feedback, reach out to:

GitHub: @<your-username>
Email: your-email@example.com