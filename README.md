# Practice with DOM manipulation

1. Fork this repository
2. Go to **Settings** in your repository and select **Actions > General**
3. Select the **Allow all actions and reusable workflows** option and click **Save**
4. Go to the **Actions** tab and click the green button if actions are not yet enabled

The folder under _exercises/_ contains an HTML file and a JavaScript file called _index.js_. Start a web server (using `npx http-server`), open the HTML file (which will be at http://127.0.0.1:8080/exercises/part1-selectors-and-events/) in your browser, and work through the exercises as instructed in the JavaScript file. The .js file gives instructions for what you should see in the console if you're on the right track. You should also see "Success!" five times on the page.

When the tests are all successful, your page should look something like this:
![Successful runs](images/dom-success-screencast.gif)

To run all the tests, open one terminal and start a web server:

```bash
npx http-server
```

Then, from another terminal, run the tests:

```bash
npm test
```

You can also lint your code with the following command:

```bash
npx eslint .
```

When you push your code to GitHub, GitHub _should_ also run the same set of tests and lints.