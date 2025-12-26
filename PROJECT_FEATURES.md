# Implemented Features
## T-1: Implement Admin/User Signup Page
This feature includes a signup form with logo, name, email, password, confirm password, and user type (Admin/User). Validation is handled for unique email, password strength, matching passwords, and required fields. On successful signup, user data is saved, a confirmation email is sent, and the user is redirected to the dashboard.

## T-2: Implement Admin/User Signin Page
This feature includes a login form with email, password, remember me checkbox, Signin button, Signup link, and Forgot Password link. Validation is handled for correct email/password, empty fields, and email format. On successful login, the user is redirected to the dashboard. The system also supports 'remember me' functionality to keep the user logged in for future visits.

## T-3: Implement Admin/User Forgot Password Page
This feature includes a form with email, Send Code button, verification code field, new password, confirm password, and Submit button. Validation is handled for email existence, code verification, password rules, and matching passwords. On successful reset, the password is updated in the database, and a confirmation message is shown.

## T-4: Implement User Dashboard Menu
This feature includes a dashboard overview with menu items: Coin balance, Selling history, Donation history, Purchase history, Wish-list, Notifications, Edit profile, and Change password. Each menu item navigates to its corresponding page, ensuring a smooth user experience and no broken links.

## T-5: Implement Sell / Donate Book Feature
This feature includes a form with book title, author, category, condition, price (if selling), image upload, and option to choose Sell or Donate. Users can submit the form to either sell or donate a book. Uploaded books appear in the marketplace or are processed for donation, and users earn coins for approved donations.

## T-6: Implement Library Upload Feature
This feature allows a verified library to upload books with book title, stock, price, optional discount, images, and a Save button. Uploaded books are displayed in the Library Store, and the library can manage stock and view earnings on the dashboard.

##T-7: Implement Search Books Feature
This feature includes a search bar with price filter, category filter, and sort options. Users can search and filter books by category, price, author, and condition to quickly find the books they want.

## T-8: Implement Buy Book Feature
This feature includes Add to Cart, Apply Coins, Checkout, and Confirm Order functionality. Users can purchase books using either coins or real money. Order details are saved, and delivery tracking is available.

## T-9: Implement Payments Feature
This feature allows users to pay using card, mobile banking, or coins. It includes transaction history and ensures secure processing, receipts, and refund handling.

## T-10: Implement Admin Panel Feature
This feature allows admins to approve/reject book listings, verify libraries, manage users, handle complaints, and view analytics. Admins can monitor system activity to ensure the platform is safe, organized, and high-quality.


