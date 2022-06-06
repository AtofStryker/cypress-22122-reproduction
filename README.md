## Reproduce [Cypress #22122](https://github.com/cypress-io/cypress/issues/22122)


on `Windows 10` inside `git bash`, run

* `npm install`
* `npx cypress open --project ./path/to/project`
* Select E2E Testing -> Chrome -> Start E2E Testing in Chrome -> spec.cy.js
* Error appears when spec is run `http://localhost:53044/__/#/specs/runner?file=../../../test/spec.cy.js`

```
Error: EINVAL: invalid argument, mkdir 'C:\Users\<user>\AppData\Roaming\Cypress\cy\production\projects\project-ba1846e9920cd401248ac4281c24124c\bundles\C:\Users\<user>\Repositories\temp-project\test'
```