# Bookmarker
- Chrome extension that stores website and tabs which can be accessed in future.
- Chrome Extension: "Bookmarker"
   -Developed a user-friendly Chrome extension to assist users in bookmarking their favorite websites.
   -Implemented using Chrome's Manifest V3 for enhanced security and performance.
- Manifest Configuration (manifest.json)
  - Configured the popup action to trigger a user-friendly interface for bookmark interactions.
  - Utilized Chrome's tabs permission to gain access to the user's active tab information.
- User Interface (popup.html)
 - Designed an interactive popup window for users to manually input website URLs or save their current tab's URL.
 - Incorporated options for users to either save their input, save the current tab's URL, or delete all saved bookmarks.
 - Ensured the user interface was intuitive and straightforward, displaying all saved bookmarks in a list format.
- Styling and Presentation (style.css)
  - Adopted a clean and modern design with a predominant color scheme of green (#5f9341) to ensure a pleasing user experience.
  - Implemented responsive design features ensuring consistent appearance across different window sizes.
  - Enhanced the usability by distinguishing the "Delete All" button visually.
- Functionality and Logic (index.js)
 - Leveraged the localStorage to store and retrieve the user's bookmarks, ensuring persistence across browser sessions.
 - Integrated the Chrome tabs API to access and save the URL of the user's currently active tab.
 - Implemented an efficient rendering function to display saved bookmarks, allowing users to click and navigate to the respective websites.
 - Enabled a double-click event listener on the "Delete All" button to clear all bookmarks, providing an extra layer of protection against accidental data deletion.
 - Ensured the extension does not store empty URLs by incorporating data validation checks.
 - Remember, the goal of these bullet points is to convey the value and functionality of your extension in a concise manner. Adjustments can be made based on the specific audience or position you are applying for.
- Single click save tab to store the tab you are currently on.

![Screenshot from 2023-04-26 15-11-44](https://user-images.githubusercontent.com/95877070/234545481-98badb17-404e-4e04-8fb9-4cb08462b500.png)

Type website in input box and click on save website to store data given as input.

![Screenshot from 2023-09-04 17-43-03](https://github.com/Atharv-a/Bookmarker/assets/95877070/958982ac-65fd-45d8-bcaf-fab89e6afd72)

Double click delete all button to delete all stored data.

![Screenshot from 2023-09-04 17-43-28](https://github.com/Atharv-a/Bookmarker/assets/95877070/76ad41a0-75e6-4845-8a05-7c581693729f)
