Bullhorn API CLI
================

Working fork. Added the new header requirements for the Auth session (i.e. faking a browser session which the API now seems to require), and couple of corrections to the logger.

Steps:
1. Log in to app.bullhornstaffing.com using the web GUI using your API user account
2. Run a basic Auth call in web browser to see and accept to the Terms of use, e.g. https://auth.bullhornstaffing.com/oauth/authorize?client_id=[YOUR CLIENT ID HERE]&response_type=code&action=Login
3. Accept the Terms of use
4. Now use the command line tools
