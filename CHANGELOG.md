#Changelog

##TagSpaces 1.6.1528 / 2013.09.18
- [All] Redesigning the new version notification dialog
- [All] Hiding loading splashscreen after the layout initialization
- [All] Font size of alert dialogs changed
- [All] Corrected issue with jqueryeditinplace library
- [All] Correcting the sort order of the dates
- [All] Addded new mindmap visualization in the perspectiveGraph
- [All] Editing of HTML files is now possible
- [All] Added grouping by tag groups
- [All] The file list is refreshed after tag color change
- [All] Added some new vizualiazions to the perspectiveGraph
- [All] Implemented check for a disabled localStorage
- [All] Adding d3.js and underscore.js as a core libraries
- [All] CSV export function moved to the perspective manager
- [All] Better check for the similarity of the filepath implemented
- [All] Smart tags added
- [All] Changing perspective order now possible in the options
- [All] Added a class for disabling the text selection
- [All] Added custom scrollbars for webkit browsers
- [All] Default perspective renamed to list
- [All] Calendar perspective renamed to grid
- [All] Footer shows found files count
- [All] Set filter is now perspective specific
- [All] Implementing search funcitonality in the perspective thumb
- [All] Added grouping by day, month and year in the thumbPerspective
- [All] Added warning for chrome users if TagSpaces has no access to local file URLs
- [All] Tags are now colored in the fileopener
- [All] Filter in default perspective has now a red icon if it is not empty
- [All] New library fixing a bug preventing opening a directory selection dialog in linux on chrome
- [Firefox] Improving the firefox's toolbar button integration
- [Firefox] Issue in Firefox on OSX with renaming/taging of files now workarrounded
- [Chrome] TagSpaces opens automatically on first install in chrome
- [Chrome] New version of the npapi for chrome under windows integrated, supporting real file renaming and last modiefied date for files
- [Win32] Added win32 builder in the build.xml

##TagSpaces 1.5.1448 / 2013.08.11
- [All] Numerous UI Improvements
- [All] Added a new viewer for image files
- [All] Added a basic functionality for changing the colors of tags
- [All] The text in the search filter is now remembered accross the current session
- [All] The thumb image status, the size/path columns and the sort status are now remembered for the current session
- [All] It is now possible to change the position of the tag in the filename.
- [All] Improvements in the parsing and displaying of file titles
- [All] Improvements in displaying file sizes
- [All] Added additional column for the file extension in default perspective
- [All] A new created location is now automatically opened after its creation
- [All] A location name is extracted from the directory path as a suggestion
- [All] Enhancing tag suggestion with UI improvements and suggestions from the containing directory name
- [All] A new created file is now automatically opened after its creation
- [All] Adding the functionality to reload a opened file, which has been renamed/tagged
- [All] Adding add a tag button to the current file in the file viewer menu
- [All] Added reload current file functionality to the file viewer menu
- [All] Fixed reloading tagspaces on cklicking enter in dialogs
- [All] Added directory create functionality
- [All] A new text editor extension created based on codemirror
- [All] A new PDF viewer extension created for the node-webkit platform based on pdf.js
- [Chrome] Restricting renaming files larger than 5MB in chrome due a missing functionality in the API
- [Firefox] Added icon to firefox main menu
- [Firefox OSX] The firefox extension is currently not supporting OSX due a issue in the mozilla's XPCOM api preventing renaming of files. See [#11](https://github.com/uggrock/tagspaces/issues/11) for more details.   

##TagSpaces 1.4.1384 / 2013.06.16
- [All] A bug fixed causing reloading of the addon in a bootstrap modal
- [All] TagSpaces is not started anymore in firefox as pinned tab, due the possibility to have multiple instances of the addon simultaniously
- [Firefox] Startup/reloading issues in firefox resolved

##TagSpaces 1.4.1363 / 2013.06.04
- [All] De/Selecting files functionality
- [All] Added functionality for configuration of filetypes and perspectives
- [All] Added options dialog with ability to change options like showing hidden files or checkign for new version
- [All] Extension tag button added to the file opener toolbar
- [All] Considering hidden directories in the directories navigator
- [All] Directories look&feel enhanced
- [All] Standard perspective loaded at first by default
- [All] Welcoming font-awesome in the project
- [All] Added follow on twitter button
- [All] About and Setting buttons shifted to the options dropdown menu
- [All] Added menu item for reporting issue in github
- [All] Added menu item for contacting the developers per email
- [All] Additional file actions shifted to a separate dropdown in file opener
- [All] Taggroup position can be changed up and down
- [All] Tags can now be moved with drag & drop between taggroups
- [All] UI migrated to Bootstrap
- [All] Added edit in place for the title of a opened file
- [All] Standard perspective added, replacing basic and search perspectives
- [All] Added thumbnail zooming functionality in the standard perspective
- [All] Max dimension of thumbs changed to 100px
- [All] Adding support of thumbnails in the standard perspective 
- [All] Adding buttons in the standard perspective for toogling the tags and filedetails columns 
- [All] Fixed a bug for reopening a file after applying some changes on it
- [All] Added buttons in the file opener for getting the next and previous file in a perspective
- [All] Added file details area in the file opener
- [All] Added a button for toggling the file details
- [All] Now is possible to create directories starting with digits
- [All] Added a functionality for creating of taggroups
- [All] Duplicating tagsgroup functionality disabled
- [All] Added a functionality for checking if new version is available
- [Firefox] bugfix for listing directories with wrond enconding

##TagSpaces 1.3.1284 / 2013.03.29
- [All] Added GTD as a default taggroup
- [All] New welcome hint shown if new favorite directories exist.
- [All] Add support for dropping of tags over the search entries
- [All] Allowing adding multiple tags to multipe files
- [All] Tag button created in files view
- [All] Removing the focus from the edit button, after clicking on it
- [All] Bug fixed in search view preventing from renaming and opening files from the context menu
- [All] Tag suggestion working again.
- [All] Fixed issue with no possible dropping of tags on a file with no tags
- [All] Enabling drag&drop of files in tag & search views
- [All] Closing a opened files after it is moved to a other directory
- [All] Issue [#5](https://github.com/uggrock/tagspaces/issues/5) fixed (Opening of files in file view was broken)
- [All] Information shown in the browser title improved
 
##TagSpaces 1.3.1235 / 2013.02.16
- [All] File tagging now possible with drag & drop
- [All] Search results visualization redesigned
- [All] Resets the search filter by view change
- [All] Added start here hint/tooltip
- [All] Context menu for files and file titles unified
- [All] Drag&Drop for moving files in directories implemented
- [All] Added separate context menu for file extension
- [Firefox] Adding creatingDirectoryTree to the mozilla io API
- [All] Functionality for upgrading of the settings implemented
- [All] Loading Animation now works while creating directory indexes
- [All] Name of the current favorite folder shown in title of the tab/applicaition

##TagSpaces 1.2.1200 / 2013.01.11
- [Chrome] Fixed bug preventing saving of text files in chrome
- [All] Dynatree library removed from the project
- [All] About.html updated
- [Chrome] Allowing to load local files in chrome
- [All] Property for persisting of the extensionPath added to the default settings
- [All] ViewerBrowser extension integrated in the core of the application
- [Firefox] TagSpaces icon/button is added on installation time automatically to the firefox's navigation bar
- [Firefox] Opening of a directory from the context menu implemented
- [All] New algorithm for the directory browsing implemented
- [Firefox] Extensions folder could now be located outside the add-on's folder.
- [All] Buttons for switching the views are now aligned left.
- [All] Icon of the toggleLeftPanel changed
- [All] Loading animation now disappears (visibility: hidden instead of display: none)
- [All] Directory sorting improved
- [All] A new concept for directory navigation implemented
- [All] All TagGroup are now opened by default
- [All] First run detection implemented
- [All] Added support for SVG files in the settings
- [All] Tag visualization realization exchanged with modified jqueryui accordion
- [All] Adding datepicker for editing date tags
- [All] Setting white as a background color for fullscreen mode
- [All] Tag suggestion functionality now splits the filename with space, comma, plus, underscore and score delimiters
- [All] Integration of the jquery.dropdown library for context menus
- [All] Fullscreen button implemented properly
- [All] Added auto complete functionality to the add tag dialog.
- [All] Displaying the build number as a label over the application version
- [All] Added getAllTags function for extracting all plain tags from the settings

##TagSpaces 1.1.1181 / 2012.12.23
- [All] Optimizations in the loading mechanism
- [All] jquery layout version exchanged
- [Fireofox] Exporting undate.rdf to the release folder of tagspaces.org repository
- [All] Added custom css for MD-files rendering
- [All] jquery-ui-custom library exchanged with the the developers version of it
- [Firefox] Extension will be automatically unzipped during the installation
- [All] LICENSE file linked in the about box
- [Firefox] Added UI fuctionality for opening the parent folder of a file
- [Firefox] Added functionality for opening a directory, selecting a file and a directory from the file system