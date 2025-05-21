1. In the recipe project development pipeline, I would fit the automated tests within a Github action that runs whenever code is pushed to ensure that the pipeline is triggered. Whenever a developer wants to commit a change and push a change, the pipeline triggers, the tests run, and only if the tests pass and they get approval, are they able to merge the pull request into the main branch. 

2. No, end-to-end is meant for the entire workflow from the user opening the page, but if you're doing a function, you would use unit tests.

3. The performance is a lot better on navigation mode according to the Lighthouse reports, which makes sense, it loads the page from scratch, and measures metrics like performance, SEO, best practices, and accessibility. Snapshot mode, liek the name, takes a single static snapshot, but it doesn't really analyze load speed, or JavaScript, it's just for static elements, the score is a lot lower on the Lighthouse report.

4. Although the report score is 99, which is very good, we cna improve the page by adhering to the software engineering principles, the -ilities that we learned in class. Improve accessibility by having alt text in images for visually impaired people, make sure the code is validated on the HTML, W3Schools validation to make sure it runs smoothly. 




