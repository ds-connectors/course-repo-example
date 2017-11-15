# Sample Course Repository

This repository is one example of how you may want to structure your course repository. Below are some key features of this structure.

## Repository Structure 

1. All content is on the `gh-pages` branch. 
    * By putting content on the `gh-pages` branch (as opposed to the `master`) branch, GitHub will automatically create a site for your 
    repository. You can view the site for this repo at 
    [https://gunjanbaid.github.io/course-repo-example](https://gunjanbaid.github.io/course-repo-example).
    * All markdown (`.md`) files that have a heading (lines starting with hashes) will be published.
    * Markdown files without headings will not be published.

1. Separate folders for each semester
    * This allows you to save content from each semester.
    * Clean URL structure for course sites. For example: [https://gunjanbaid.github.io/course-repo-example/fa17](https://gunjanbaid.github.io/course-repo-example/sp18) 
    and [https://gunjanbaid.github.io/course-repo-example/sp18](https://gunjanbaid.github.io/course-repo-example/sp18).
    
1. Separate folders for `hw`, `labs`, `lec`, `proj` in each semester's folder.

1. Separate `index.md` files in each semester's folder.
    * There is an `index.md` file in the [`fa17` folder](https://github.com/gunjanbaid/course-repo-example/tree/master/fa17) and 
    in the [`sp18` folder](https://github.com/gunjanbaid/course-repo-example/tree/master/sp18). 
    * The `index.md` file in the [root directory](https://github.com/gunjanbaid/course-repo-example/tree/master) redirects to the
    `index.md` file for the current semester. Currently, it redirects to `fa17`. Thus, if you go to 
    [https://gunjanbaid.github.io/course-repo-example](https://gunjanbaid.github.io/course-repo-example), you will be redirected to 
    [https://gunjanbaid.github.io/course-repo-example/fa17](https://gunjanbaid.github.io/course-repo-example).
    
## Other Features

1. You can find examples of how to set up OK in the [hw02](https://github.com/gunjanbaid/course-repo-example/tree/gh-pages/fa17/hw/hw02) and [lab02](https://github.com/gunjanbaid/course-repo-example/tree/gh-pages/fa17/lab/lab02) folders. 
Specifically, there are examples of how to set up student-side autograding and submission.

1. You do not have to use the `gh-pages` to publish content. You can also use the `master` branch. 
To do so, select the desired branch as the GitHub Pages source under your repository's settings (shown below).

1. The theme for the site can be changed very easily through the repository's settings tab. First, click on the settings tab. Then, scroll to the GitHub pages section. You may update the site theme by clicking on `Choose Theme`.

![image](https://user-images.githubusercontent.com/8205702/32854106-68c96dba-c9f2-11e7-8550-ce92ecd57495.png)
![image](https://user-images.githubusercontent.com/8205702/32854062-48de0f38-c9f2-11e7-893c-0308db455b74.png)
