# Bountiful Children's Foundation Coordinator Storytelling

## Git workflow

_no forks will be used in the git repo!_
Your Team Leader will set up a Github organization for you to join. Each organization should have a SEPARATE REPOSITORY for each student's role (e.g. Landing Page (UX/UI), Frontend, Backend).

If you are working together with another Front End Architect you will both work on the same repo on separate branches.

Git workflow:
1. Clone the master branch of the repository.
   - In your terminal: `git clone [repo link]`
   - DO NOT FORK THE REPO
2. Make sure master is up to date: `git pull`
3. Create new branch: `git branch firstname-lastname`
4. Checkout branch: `git checkout firstname-lastname`
5. Add some features!
6. Make regular commits per usual.
   - `git add -A`
   - `git commit -m "a descriptive commit message"`
   - On first push to branch use: `git push -u origin [firstname-lastname]`
   - Subsequent pushes: `git push [firstname-lastname]`
7. When a feature is COMPLETE: checkout master branch: `git checkout master`
8. Make sure master is up to date `git pull`
9. Checkout branch: `git checkout firstname-lastname`
10. Merge the master `git merge master`
11. Resove any conflicts - let me know if you need any help with this!
12. Commit changes `git commit -m "message"`
13. push it!
14. On github, make a pull request to be approved by TL or PM.

Pitch: The Bountiful Children's Foundation needs a way to collect success stories from 15 different countries, rather than losing them through email, facebook messages, etc.

MVP Feature Breakdown: This app contains two user types. A coordinator and a donor.

Login/Sign up Pages: Coordinators can login to their account or sign up for an account using a Username and Password. Account should include name, country (choose from a drop down list: Bolivia, Brazil, Cambodia, Colombia, Ecuador, El Salvador, Ghana, Guatemala, Haiti, Honduras, Kiribati, Madagascar, Mongolia, Nicaragua, Paraguay, Peru, Philippines, Sierra Leone, Zimbabwe) their title within the organization, and e-mail and password.

Home Page (for a coordinator) If no profile is created, be sure to allow a coordinator to create a profile. In a list view, a coordinator can see their stories that they have saved. Story title, country, and short preview of the description

A user can create a story. A story must be able to have a title, country, description, and date.

A user can edit a story.

A user can delete a story.

Home Page (for a donor): Each story is laid out in a grid format, with the country name and story preview beneath it. Stories are ordered chronologically. Stories can also be filtered by country (Bolivia, Brazil, Cambodia, Colombia, Ecuador, El Salvador, Ghana, Guatemala, Haiti, Honduras, Kiribati, Madagascar, Mongolia, Nicaragua, Paraguay, Peru, Philippines, Sierra Leone, Zimbabwe).

Single story view page with a donate button at the bottom.

Stretch: Allows coordinators to upload photos and videos to the stories. Allow coordinators to upload a profile pic. Link to paypal to donate.
