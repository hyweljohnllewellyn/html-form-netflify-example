# html-form-netflify-example
Source for https://html-form-example.netlify.app that is used in a youtube tutorial at https://www.youtube.com/channel/UCcarUCJtw6qm_WOzMo4m6rg and https://www.hywel.me/sites/2021/11/15/website-page-with-contact-form-using-html-github-and-netlify.html

#Full website page with contact form using HTML GitHub and Netlify

Links
GitHub Repository with all code used in this how-to:
https://github.com/hyweljohnllewellyn/html-form-netflify-example

Script
This is a step—by-step example showing how to create and deploy a website page with a contact form - from start to finish.

I use the Netlify platform to host many static sites and landing pages and Netlify’s contact forms are great for these sites.

Netlify forms also includes free spam protection and a way to redirect to your own success page.

Git hub is great as a place to store your site code - not only as it does the usual version control , but the interface is relatively friendly and there is seamless integration to Netlify 

You can think of GitHub repositories as folders to keep files. 

If you are new to GitHub, register if you want to follow along. 

Step 1 - Create  a Repository for your website in GitHub
After logging in to GitHub, Click on New next to Repository, give it a name and click Create repository 

Step 2 - Create basic HTML page
Click add file, selecting Create new file, give it a name of index.html. 
This is important as this is a 1 page site, Netlify looks for index.html as default. 
I have a basic html page already coded.  You can refer you this basic page as a starting point.  The link to the GitHub repository with all the code is in the description.
Paste the code into the file and commit changes, in other words , save the file. 

Step 3 - Create Live Website hosted by Netlify
Log in to Netlify. 
If you don’t have an account then pause this video and sign up. I use my GitHub credentials for login. 

Select New site from Git* and then GitHub, where our source code is hosted
*https://en.wikipedia.org/wiki/Git	

Find the Repository created in step 2, select it and then scroll down and click Deploy site.

This is where Netlify finds the index.html in GitHub and creates a Website that is live to the internet.

Step 4 - Change Site Address
You can see the website address is not too friendly, so click on Site Setting and change site name. 
Note that it is possibly to use a custom domain, but I won’t cover that in this guide.
Click on the Website address and you can see the live html page in the browser.

Step 5 - Create a Contact Form using bootstrapformbuilder.com
Click Add a Text Field and change the Title to ‘name’
Repeat this for ‘email’, and check the ‘required’ option. This validates that any user has entered an email, else you cannot reply!
Add a Text Area so that a user can enter why they are contacting 
Copy the Code to Clipboard

Step 6 - Add Form to your page with the required Netlify attribute
Paste the form code to the website page,  commit the change, refresh your page in the browser to check the form is there.
Then add data=netlify=“true” to the form element so Netlify defects that there is a form and commit the change. 

Step 7 - Configure Netlify to send email Notifications for Form Submissions 
In the Netlify Dashboard for the site, click Forms then Settings and Usage.
Under Form notifications, Click  Add Notifications and Select Email Notifications.
Enter the email address that to be notified, usually the owner of the website and Save

Step 8 - Test the Form!
We are done. Refresh the page and enter a form submission.
You will receive an email to the address given in step 7.

Note that I went back to give the form a name =“contact” to more easily identify the source in the email notifications.
I also later added a recaptcha, for added spam protection.

All the code is available in the GitHub repository, link given in the description

Thank you for following along.

