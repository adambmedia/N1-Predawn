# N1 Predawn UI theme
### A dark-ui theme for the [Nylas N1](https://www.nylas.com/n1) email client.

### Extensively based on the excellent Sublime/Atom dark-ui theme [Predawn](https://github.com/jamiewilson/predawn) by [Jamie Wilson](https://github.com/jamiewilson).

![Screenshot](./N1-Predawn-Screen.png?raw=true)

# Installing
1. Download the [Nylas N1](https://www.nylas.com/n1) email client.
2. Grab the latest release of N1-Predawn
3. Open `N1>Preferences>General>Select theme` and select `Install new theme...` from the dropdown.

You want to install the theme from the package (first option) and not the source (second and third options). As of this release, N1 looks at the folder name to set up the directory. Github's `source-code` links add the version number to the folder name and will break the absolute icon references.

4. Impress your friends with your snazzy dark-ui email client.

# Folder Hierarchy
This theme overrides classes found in N1's `internal_packages` directory, `static` directory, and the more typical `ui-variables.less` file.  The folder hierarchy is set up to roughly point to where the original classes can be found to aid the developer to further extend the theme.

# Todo
1. fix cursor to get rid of white outline as [here](https://discuss.atom.io/t/mouse-cursor-of-editing-status-in-dark-theme/10694)
2. consider lighter color for email display to gel with incoming richtext on many many emails
3. consider relevance of soda or monokai theme elements or whether, without code, they are unneccesary
4. figure out something more elegant for inverse thread-list icons and all the white, gray hover stuff
5. figure out something more elegant for mulit-select in thread-list
6. messed up scrollbar in email composition templates popup
7. horizontal scrollbars
