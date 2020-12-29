# firefox-css
Minimalist and materialistic design of Firefox interface and creates dark mode for multiple sites.
Plan to make CSS code more efficient (especially CSS for sites). Many attributes don't seem to work without <!important>.

### Can very easily change properties such as color and font in custom.css

Inspired by the old versions ![Minimal Functional Firefox](https://github.com/mut-ex/minimal-functional-fox), so creds to him.

Mozilla seems to want to remove some CSS such as -moz; will update then. 

Works on Firefox 76 (latest stable version).

### To-Do
- [ ] Booksmarks bar
- [ ] Findbar
- [ ] Simple transition animations
- [ ] More CSS files for sites (focusing on popular Google sites)
- [ ] Custom homepage (may not do, Firefox keeps breaking .xml and .js with userContent.css; same reason why I do not do custom scrollbars, although changing scrollbar width and color is fine right now, anymore than that is a pain)


### Sample (in /images)
- firefox changed default PDF viewer to dark so pdfViewer2.png (from custom css) looks similar to the native one
- Google Calendar Dark Mode (there are some unknown unicode don't worry about that, that is just my font choice from settings, not from the CSS)
![alt text](https://github.com/harrisonchiu/firefox-css/blob/main/images/googleCalendarDarkMode2.png)
- Main UI
### yes i am aware the color scheme looks ugly, i chose it to show how you can customize many parts of the browser from custom.css file. in particular, you can change the color for all three states of tabs, make it a gradient, round tabs, big (or smaller) font size/family
![alt text](https://github.com/harrisonchiu/firefox-css/blob/main/images/mainUI.png)

- Sidebar (removed visual noise from default)
![alt text](https://github.com/harrisonchiu/firefox-css/blob/main/images/Sidebar.png)

### Changelog

#### Firefox v75+
- Fixed visual bugs for changed v75 UI
- Absolute massive file organization and CSS code overhaul
- Code reorganized, refers to multiple seperate files for better organization
- Removed many useless and outdated code (some were which Firefox did not support anymore)
- Most variables are easily changed in a seperate file with reference to what will be changed (much easier to customize and personlize your Firefox)
  - Changing CSS which do not have a variable may mess things up

#### Firefox v72
- Uploaded


