# Challenge 1

This week, your Challenge is an on-the-job ticket, which means you'll begin with starter code that you need to modify. This week's Challenge involves a very important aspect of web development: accessibility.

One of the most common tasks for front-end and junior developers is to take existing code and refactor it (recall that to refactor code is to improve it without changing what it does) to meet a certain set of standards or implement a new technology. In this Challenge, a marketing agency has hired you to refactor an existing site to make it more accessible.

Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.

Even though accessibility is a broad topic that can include complex requirements, your tech lead has given you a small list of specific criteria to satisfy the project. These criteria are documented below in the Acceptance Criteria.

## Modification

I modify div elements to improve accessibility standards for users.
### Changes in index.html
```bash
<div> --> <header> <nav> <aside> <footer>
```
### Changes in css
```bash
div --> nav 
.header div --> header nav
.header div ul --> .header nav ul 
.header div ul li --> .header nav ul li
```

## Usage

![alt text](assets/images/screenshot.png)

## Contributing
Proposed changes are welcome

## License
[MIT](https://choosealicense.com/licenses/mit/)