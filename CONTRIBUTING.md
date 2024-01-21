## Contributing

🎉 First off all, thank you for taking the time to contribute to ParamStorm! Let's build an API development, testing and documentation that is KISS! 🎉

### What can you do for ParamStorm Community?
Beside from direct contribution exampled below, it would be a great if you help spread the word, recommend this tool in your blog posts or videos! Or you can simply ⭐️ our repository! Anything is welcome!

- Make pull requests to implement new features or to fix bugs
- Help with the issue tickets
    - Help solve problems in issue tickets
    - Remind and discuss with the contributors to include demo, screenshots and any test necessary
- Add documents or Translate it
- And more...

This project adheres to the
[code of conduct](CODE_OF_CONDUCT.md). By participating, you are expected to
uphold this code. 

### Project Framework
This project is built on top of Laravel for backend and Vue.js for frontend.
If you like php, feel free to contribute to the backend system or if you prefer Vue.js, the frontend is there for you to show your craftsmanship.

### Windows Local Environment Setup
1. Install [PHP 8.1](https://windows.php.net/download#php-8.3).
2. Enable the following extension in your php.ini files
   ```

   ```
3. Install latest version of [Composer](https://getcomposer.org/download/)
4. Install [MariaDB 10.x](https://mariadb.org/download/?t=mariadb&o=true&p=mariadb&r=10.11.6&os=windows&cpu=x86_64&pkg=msi)

### Linux Local Environment Setup
> Please contribute

### Development Guide
#### Setting Up
1. Be sure to start by creating a fork of our github repository with this [Quick Fork Link](https://github.com/ParamStormLabs/ParamStorm-Community/fork).
2. Clone your forked repository to your local development environment and add upstream of the ParamStorm-Community to your cloned repository
   ```
   $ git clone git@github.com:<Your Github Username>/ParamStorm-Community.git
   $ cd ParamStorm-Community
   $ git remote add upstream https://github.com/ParamStormLabs/ParamStorm-Community.git
   ```
3. Make a `.env` file from `.env.example` and replace the correct values
4. Install composer packages and npm packages
   ```
   $ composer install
   $ npm install
   ```
5. Run migration
    ```
    $ php artisan migrate
    $ php artisan seed
    ```
6. Run the testing server
   ```
   $ php artisan serve
   ```
   ```
   $ npm run dev
   ```
   
#### Submitting Changes and Pull Requests
1. Create a new branch before you make any new feature or fix any issues
    ```
    $ git checkout -b <Your Branch Name>
    ```
    ⚠️ Please do not work on the main branch :(

2. Commit changes
    ```
    $ git add .
    $ git commit -m '<Your Commit Message>'
    ```
3. Update your local copy of upstream before pushing your updates
   ```
   $ git fetch upstream
   $ git rebase upstream/main
   ```
4. Push the branch
    ```
    $ git push origin <Your Branch Name>
    ```
    ⚠️ If you used to opened a pull request before, you will need to do force push with the `--force`.
5. Now go to your fork repository on your github account, and create Pull Request. After that please submit the changes for the project maintainers to review.

    It's alright if the maintainers requesting changes. It happens to almost everyone :) 

    Please follow the instructions of the maintainers to make the changes on your local branch and push the changes again. It will be automatically appeared in your pull request.


😺 Have fun contributing!
