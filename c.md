<table><tr><td> <em>Assignment: </em> IS601 Milestone1 Deliverable</td></tr>
<tr><td> <em>Student: </em> Shiva Sai Kobbaji (sk3524)</td></tr>
<tr><td> <em>Generated: </em> 4/17/2023 9:20:00 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-006-S23/is601-milestone1-deliverable/grade/sk3524" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Checkout Milestone1 branch</li><li>Create a milestone1.md file in your Project folder</li><li>Git add/commit/push this empty file to Milestone1 (you'll need the link later)</li><li>Ensure your images display correctly in the sample markdown at the bottom</li><ol><li>NOTE: You may want to try to capture as much checklist evidence in your screenshots as possible, you do not need individual screenshots and are recommended to combine things when possible. Also, some screenshots may be reused if applicable.</li></ol><li>Save the submission items</li><li>Copy/paste the markdown from the "Copy markdown to clipboard link" or via the download button</li><li>Paste the code into the milestone1.md file or overwrite the file</li><li>Git add/commit/push the md file to Milestone1</li><li>Double check the images load when viewing the markdown file (points will be lost for invalid/non-loading images)</li><li>Make a pull request from Milestone1 to dev and merge it (resolve any conflicts)<ol><li>Make sure everything looks ok on heroku dev</li></ol></li><li>Make a pull request from dev to prod (resolve any conflicts)<ol><li>Make sure everything looks ok on heroku prod</li></ol></li><li>Submit the direct link from github prod branch to the milestone1.md file (no other links will be accepted and will result in 0)</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Feature: User will be able to register a new account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232618253-07aed83a-c2fd-4c4b-98a6-1dbe5559d7fc.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing passwords not matching<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232618973-348e0b46-c596-41c5-bd7d-2bbad5a2f300.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the username is not avalibale<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232619323-0c5e6865-1e4c-4f3e-84b9-8ecd6668c34b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing invalid email entered<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232619554-062029d8-3e98-423c-98b7-c3546718117d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing invalid password entered<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232619736-a396a4e5-eac0-472a-9ec8-9c862ef39d5c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the chosen email cannot be taken<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232620144-b3017f28-6983-42c1-a63a-fe0932ca7274.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing valid data for form submission<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the Users table with data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232620319-f578af6f-0297-41e3-a759-7a44290fab3b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing added data in database.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <div><font color="#333333" face="Roboto, sans-serif"><span style="font-size: 16px; white-space: pre-line;">For generation and validation, we employ<br>WTforms.</span></font></div><div><font color="#333333" face="Roboto, sans-serif"><span style="font-size: 16px; white-space: pre-line;">1.)We use WTForm for Validator&nbsp; &nbsp;<br>2.) The authorized username is used for data validation in both the frontend<br>and the backend of Email authentication is carried out utilizing an email validator<br>and requires that the message minimum from couple to&nbsp; 30 characters long and<br>unread by any other users.</span></font></div><div><font color="#333333" face="Roboto, sans-serif"><span style="font-size: 16px; white-space: pre-line;">3. The<br>password and confirm password must be identical and 8 characters long. This is<br>verified using the wtform validator and is hashed using the bcrypt algorithm before<br>being put in the database.</span></font></div><div><font color="#333333" face="Roboto, sans-serif"><span style="font-size: 16px; white-space: pre-line;">4. The<br>user table stores the user's email, username, and hashed password.&nbsp;</span></font></div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Feature: User will be able to login to their account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232623641-2d0c4c90-ac2a-4a54-9cc5-0e1dd0624585.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing invalid password<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232623802-369340cb-b937-460a-b27e-7e37949ce4c3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing invalid user<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of successful login</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232624321-771c0d98-cd8a-4761-9a9d-f33264191e5f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing successful login<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <div>1)We will utilize the username or email field instead of the pwd confirmation<br>field, which is how the login form is handled by wtform.</div><div>2. If the<br>username or email field in the user interface is marked as being filled<br>in and if the field contains the character "@," the email validator will<br>be used; otherwise, the username format, length, and password entry status will be<br>checked.</div><div>By providing an email address and user name, we retrieve data from the<br>users table in the backend. If we receive anything, we compare the password<br>before determining whether the user has assigned the role.</div><div>3) In the back end,<br>we retrieve the password from the database based on the user name and<br>email address and then check to see whether the passwords match. whether they<br>do, we erase the password from that point in the program.</div><div>4.) We retrieve<br>username, email, and password from the users database by passing username and email,<br>and then we check to see if the passwords match, and then we<br>look to see if the user has any roles assigned from the user<br>roles tables and retrieve it.</div><div><br></div><div><br></div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Feat: Users will be able to logout </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the successful logout message</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232624681-9923e22c-65a2-409f-99e7-a04b640289af.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the account is locked out <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the logged out user can't access a login-protected page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232624808-5a384413-85ff-4d4b-959f-401a4184d416.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the logout user cant access the page <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <div>To handle and operate with user sessions, we use the flask_login package.&nbsp;</div><div><br></div><div>Styled as<br>"font-family: Arial;"We'll use LoginManager in our main.py; tspan style="font-size: small; font-family: Arial;"&gt;this manages<br>our user session and offers practical tools.<br></div><div>We'll define a variable for login_manager outside<br>of the app factory since we're using one, and then inside the factory<br>we'll utilize its init_app() method to link the app.</div><div>The user_loader decorator will then<br>be used inside the app factory to execute a process to lookup a<br>user by id.<br></div><div><br></div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Feature: Basic Security Rules Implemented / Basic Roles Implemented </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the logged out user can't access a login-protected page (may be the same as similar request)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232624808-5a384413-85ff-4d4b-959f-401a4184d416.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the authorized login<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing a user without an appropriate role can't access the role-protected page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232627834-fff9d001-14a0-4217-99a8-a6768708a25d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the logout person cannot access the admin page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the Roles table with valid data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232631663-d5d21b90-e392-4bad-bc91-c6e29d297d2f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the admin roles<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a screenshot of the UserRoles table with valid data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232631795-e16b074e-5c99-4de1-895f-bf777e854b66.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the user roles table data<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add the related pull request(s) for these features</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 6: </em> Explain briefly how the process/code works for login-protected pages</td></tr>
<tr><td> <em>Response:</em> <div>In order to associate the app with the factory because we're using one,<br>we'll define a variable for login_manager outside of the factory.&nbsp;</div><div>The @login_required function is<br>used to adorn views for login-protected sites. If the user is not logged<br>in, the function calls the span class="pre" style="hyphens: none;"&gt; tag.unauthorized function in LoginManager.<br></div><div><br></div><br></td></tr>
<tr><td> <em>Sub-Task 7: </em> Explain briefly how the process/code works for role-protected pages</td></tr>
<tr><td> <em>Response:</em> <p>Here, we use the @admin_permission_require function from the roles.permissions package, similar to the<br>login protected page. We raise a 403 exception and display a 403 html<br>page with the message &quot;Permission denied&quot; if the user is not an administrator.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Feature: Site should have basic styles/theme applied; everything should be styled </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots to show examples of your site's styles/theme</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232642716-65e3bccb-2d8a-49e7-b882-8e33f204e27e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Displaying the home page<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232642843-d1925cb4-77f6-4449-9609-011e0970baf7.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Displaying the roles page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain your CSS at a high level</td></tr>
<tr><td> <em>Response:</em> <p>Cascading Style Sheets is a language for creating style sheets that describe how<br>a document presented in a markup language, such HTML or XML. The World<br>Wide Web&#39;s foundational technologies, along with HTML and JavaScript, include CSS.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Feature: Any output messages/errors should be "user friendly" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of some examples of errors/messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232627834-fff9d001-14a0-4217-99a8-a6768708a25d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>1- Permission Denied error<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232624808-5a384413-85ff-4d4b-959f-401a4184d416.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>2-Unauthorized page error <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232619554-062029d8-3e98-423c-98b7-c3546718117d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>3-Showing the password error<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a related pull request</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you made messages user friendly</td></tr>
<tr><td> <em>Response:</em> <div>For 403 and 404 problems, we use flask error handler routines. In most<br>cases, we also look at what the backend code is doing and create<br>a flash message if a field is missing or something else is wrong.</div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> Feature: Users will be able to see their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232633596-63fb0373-039b-40d3-abd1-44ee8cc8662f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the Email and username should prefill properly<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Explain briefly how the process/code works (view only)</td></tr>
<tr><td> <em>Response:</em> <div>If a POST request is not sent when the profile page is accessed,<br>the email and username are retrieved from the users database using the user<br>id, and then they are rendered into the profile form.</div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> Feature: User will be able to edit their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page validation messages and success messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232634109-6ec69176-1364-45e1-8435-acd0c2ef9a6a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the  username validation message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232634235-b219a7f7-ab4d-4a1a-879e-c3fe4e69bf3a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the  email validation message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232634659-2f938b9c-1457-42c1-8d4b-e213e8b35a7a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the password validation message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232634832-c1c8af97-f59c-4567-834a-b0e965aec02c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Show password mismatch message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232635103-b4f5d542-24f8-457c-b267-0c0be8f96f78.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the email already in use message<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add before and after screenshots of the Users table when a user edits their profile</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232635183-90ff60c8-1cc5-4b64-80b6-989f5ceea445.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the database before edit<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123420725/232635308-6458017a-f234-4702-9438-b13aa9163d87.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Showing the database after edit<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/shivasai2125/IS601-006/pull/13">https://github.com/shivasai2125/IS601-006/pull/13</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works (edit only)</td></tr>
<tr><td> <em>Response:</em> <div>The code first determines whether the request is a POST; if it is,<br>it then determines whether current_password, password, and confirm are provided; if they are,<br>it then retrieves the password from the users table; finally, the current password<br>and the pwd from the database are compared to determine whether they are<br>the same or not; if they are, an invalid password flask is raised;<br>otherwise, the new password is hashed and updated in the database.</div><div>A flash message<br>stating "saved profile" is then displayed after the username and email have been<br>updated in the database.<br></div><div><br></div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe any issues and learnings throughout this milestone</td></tr>
<tr><td> <em>Response:</em> <p>This project as taught me about flask sample and html. Actually i was<br>down with flu so i had to rush the project to complete before<br>late .<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Prod Application Link to Login Page</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-sk3524-prod.herokuapp.com/login">https://is601-sk3524-prod.herokuapp.com/login</a> </td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-006-S23/is601-milestone1-deliverable/grade/sk3524" target="_blank">Grading</a></td></tr></table>
