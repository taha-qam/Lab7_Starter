
TAHA QAMAR

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   - Within a Github action that runs whenever code is pushed 
            True. Github action would run these tests making sure that good code is pushed, and the master/main
            is not modified with code that fails testing
   - Manually run them locally before pushing code
   - Run them all after all development is completed

2. End to end testing isn't the best way to check if a function is returning the correct output, since its main goal is to check 
    general capabilities of the app, not just to see one specific function

3. Navigation mode (default) loads the whole page, analyzing that singular load to see the initial load of the website. Snapshot
   is more focused on the specific state of the website (a form being filled out, wishlist being created, etc). Snapshot is more focused on specific parts of the website, whereas navigation mode is more broad 

4. Changes possible:
    - The largest text/image (Largest contentful paint element) is the fjallraven bag, which takes 1.2 seconds to show up. We could make the time to show be faster by using formats like webp for the images used rather than jpeg, which is the currently used format. Images could also be resized to fit the screen, saving time to load
    - Modify the html to have a <meta name="viewport"> so that, instead of the webpage being scaled down to mobile phones, causing it to take more time and look worse, the double-tap zoom feature is disabled in favor of double clicking faster, preventing a
    300 ms delay for mobile user input
    - Without specifying a language, screen readers might assume the page is in the default language of the reader, which might be a 
    problem if the default screen reader language for that person is not English



