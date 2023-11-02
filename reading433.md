# Reading Notes (401) Reading 33 - easleyjs

React Cookies

## Questions
**What is Role Based Access Control (RBAC)?**

A way to create roles which have certain permissions relevant to a job/access function that can be given to users, so that we don't have to grant unique permissions to each individual user.

**Share some an example of RBAC including all possible CRUD operations and correlating roles.**

Admin - Create, Read, Update, Delete
Maint - Update, Delete
User - Create, Read
Visitor - Read

**What are the Benefits of RBAC?**

They make it easy to us to separate access into buckets for various job roles, and eliminate the need for individual/unique access.

**Describe some react-cookie features.**

Gives you a CookieProvider so that you can use/set cookies in any of your child components. Can be used in server side rendering.

**Describe some react-cookies features.**

Allows you to bring in a cookie component for getting/setting cookies.

**Which library would you prefer would you prefer? Why?**

The react-cookie seems more generally useful since you could use the same cookie(s) across your app.
