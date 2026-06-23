This is used to automatically redirect various FNAL docdb URLs from "private" to "sso". 


1. Add the [Redirector](https://einaregilsson.com/redirector/) addon to your browser
2. Click the Redirector icon and select "Edit Redirects"
3. Select "Import" and upload the Redirector.json found in this repo


When Redirector is active, it will then always replace the "private" pattern with "sso". This means you won't be prompted to enter the docdb username/password (which for some reason I can never remember). Instead, you will be able to log on with your FNAL SSO credentials, and if you are already logged on you won't be asked again. 

If you want to prevent the redirection, select "Disable Redirector" to turn off the addon completely, or Disable the specific redirect after selecting "Edit Redirects".

If you have more URLs/Experiments you'd like me to add, open a PR
