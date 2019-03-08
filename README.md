# Bountiful Children's Foundation Coordinator Storytelling

## Git workflow

_no forks will be used in the git repo!_
You will all have your OWN Repo that will live in your Github Org that you will work from.

1. Clone the master branch of the repository.
   - `git clone [repo link]`
2. Checkout a new branch: `firstname-lastname`
   - All branches will merge back into master branch.

A good order could be:

1. Make sure master is up to date `git pull`
2. Create new branch `git branch firstname-lastname`
3. Checkout branch: `git checkout firstname-lastname`
4. Add some features!
5. Checkout master branch `git checkout master`
6. Make sure master is up to date `git pull`
7. Checkout branch: `git checkout firstname-lastname`
8. Merge the master `git merge master`
9. Resove any conflicts
10. Commit changes `git commit -m "message"`
11. `git push`

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
