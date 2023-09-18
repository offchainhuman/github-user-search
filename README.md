### Objective

Clone this repo to your own profile, then using the UI framework of your choice, your task is to build a Github User Search Tool.

### Brief

In this challenge, your assignment is to build a Github User Search Tool using the [GitHub users API](https://docs.github.com/en/rest/reference/users#get-a-user). We are looking for a solution that is functionally complete, not pixel-perfect. The design system in the designs folder will give you more information about the various colors, fonts, and styles used in this project.

There is an already-created nextjs app under the `./nextjs` directory, which you can optionally use to develop the solution. It's a bare bones NextJS app with no customisation. To get started run the following commands:

```bash
cd ./nextjs
npm run dev
```

Alternatively, you can create a pure front-end solution that calls the Github API directly from the page.

### Tasks

Your users should be able to:

    - Search for GitHub users by their username
    - See relevant user information based on their search

Implement assignment using:

    - Language: JavaScript or TypeScript
    - Framework: React, Vue, Angular or other

### Expected Behaviour

- On the first load, show the profile information for Octocat (or your own Github username 😎).
- Display an error message if no user is found when a new search is made.
- If a GitHub user hasn't added their name, show their username where the name would be without the `@` symbol and again below with the `@` symbol.
- If a GitHub user's bio is empty, show the text "This profile has no bio" with transparency added. The lorem ipsum text in the designs shows how the bio should look when it is present.
- If any of the location, website, Twitter, or company properties are empty, show the text "Not Available" with transparency added
- Website, Twitter, and company information should all be links to those resources. For the company link, it should remove the `@` symbol and link to the company page on GitHub. For Octocat, with `@github` being returned for the company, this would lead to a URL of `https://github.com/github`.

### Evaluation Criteria

- JavaScript/TypeScript best practices
- Show us your work through your commit history
- We're looking for you to produce working code, with enough room to demonstrate how to structure components in a small program
- Completeness: Did you complete the features?
- Correctness: Does the functionality act in sensible, thought-out ways?
- Maintainability: Is it written in a clean, maintainable way?
- Testing: Is the system adequately tested?

### Submission

Please organise, design, test, and document your code as if it were going into production. After you have finished the assignment, please share a link to your cloned repo.

All the best and happy coding!
