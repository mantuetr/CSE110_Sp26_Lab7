# Lab7 - Lisa Tran and Hien Tran

1. Within a Github action that runs whenever code is pushed. Because it is an
   automated tests so it will test the code before merging. And, it can prevent
   the fail code to merge. If the code fails to pass the test, you cannot merge
   into the main branch. And, the team can all see the same tests.

2. No. Unit tests are good enough

3. Navigation mode audits the full page load from start to finish, it measures the performance and load times of the page. While snapshot mode analyzes the current state of the page without reloading it, this is useful for testing specific UI states like an open modal or a filtered view.

4. 
   1. Create an accessible names for button, link, and menuitem - this is to make the web page accessible to everyone even people with disability.
   2. Enable the zooming feature by `remove user-scalable=no` from the viewport meta tag, this allows users with low vision to see the content of the web page better.
   3. Keep ARIA IDs unique by making sure no two elements share the same id, because the system (screen readers) would not know which one to look up.
