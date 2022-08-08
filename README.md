# Real World Testing with Cypress - Course App

This application is for the [Testing your first application course](https://learn.cypress.io/testing-your-first-application) on [learn.cypress.io](https://learn.cypress.io/)

You can find the instructions for this course [here](https://learn.cypress.io/testing-your-first-application/course-app).

## Thoughts

- Removed @zeit/next-css not really necessary and it is a vulnerable package 
- Can always add it back if necessary - didn't notice any difference without it
- Might bump linkinator but have to investigate
- Custom Commands -> lots of typescript errors 
- getByData command works but still red in vscode - using 'any' causes the warning ? - mismatch with chainable ? chainable is not generic ?
- tradeoff: save typing longer selectors vs figuring how to get rid of difficult typescript errors
- using ts-ignore shouldn't be accepted fix 

## Useful Resources

- [Stack Overflow](https://stackoverflow.com/questions/41067550/what-is-apply-in-css) - what is apply in css
- [Next Docs](https://nextjs.org/docs/basic-features/built-in-css-support) - built in css support - removed @zeit/next-css
- [Blog](https://bobbyhadz.com/blog/typescript-cannot-be-compiled-under-isolatedmodules#:~:text=The%20error%20%22Cannot%20be%20compiled,make%20it%20an%20ES%20module.) - typescript cannot be compiled under isolatedmodules
- [Stack Overflow](https://stackoverflow.com/questions/69927966/argument-type-string-is-not-assignable-to-parameter-type-keyof-chainable-in-c) - chainable problems
- [Github](https://github.com/cypress-io/cypress-realworld-testing/discussions/153) - cypress realworld testing discussions