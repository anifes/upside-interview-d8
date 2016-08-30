# Upside Interview Project - Michael Adams
### Overview
The purpose of this project is to give you an introduction on what we do on a day to day basis here at Upside and to also
see how you handle a task you are unfamiliar with, you may not necessarily complete this entire project but give it your best
and we are really looking for what progress you made as well as how you completed what you've done.

### The Task
You job is to create a single page based off a mockup of a webpage in Drupal 8. We are looking to test your HTML, CSS, JS and problem solving skills since we know this is a system you are not familiar with.

#### Step 1. The setup
You will need to do the following to get up and running:

1. Go to github and fork this project https://github.com/anifes/upside-interview-d8
2. Pull down the repository to a location that you can serve Drupal site from. (Note: Drupal 8 requirements: https://www.drupal.org/docs/7/system-requirements/overview)
3. Configure apache to serve the website.
4. Run the mysql database dump `dbdump.sql` in the root into your database.

To get Drupal setup you will need to do the following:

1. Go to `sites/default/settings.php` and modify the database information to match your local database.
2. Make sure file permissions are read/writable for the `sites/default` folder.

After you've completed the above steps navigate to your local site then go to `/user` from there log in with user 'admin' password 'michael', if you're still having problems let one of us devs know.

#### Step 2. The Design

The mockup and design files are located in `design-files` folder for you to use. For now if you need something from photoshop please ask one of our developers or designers to help you out.

I have set up a base theme already for you to use in `themes/asap` for this project, this is where you will do all your theming.


#### Step 3. Commit

Please commit your changes to the git repository as you go, so we can see the progress you've made incrementally. It's often best to commit when you've completed a chunk of your task.

##### IMPORTANT REMEMBER TO DUMP AND COMMIT YOUR DATABASE TOO BEFORE YOU LEAVE/FINISH

#### Finally!

Please remember, we are just looking for progress, technique and problem solving skills with the emphasis on problem solving. Drupal is a fairly advanced piece of OOS and it's not something you learn in a day.

Also, feel free to ask as many questions as you need to keep moving forward.

