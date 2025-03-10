---
title: BrainTool 1.0 User Guide
layout: default
tagline: The Topic Manager for your Online Life
description: BrainTool organizes and retrieves pages you want to remember, using notes and nested tags. It's a better way to control your browser.
audience: user
---

# User Guide
BrainTool is a 'Topic' Manager for your tabs. Topics are the basic unit of organization. The BrainTool Topic Manager sidepanel shows your topic hierarchy and provides tools for editing and curating your topics. The BrainTool Bookmarker lets you quickly assign a topic and note to any web page or browser resource that you want to keep track of.
<div class="row">
<div class="cell left">
<img src="./site/TopicManager10.png" alt="side-panel" style="border:solid; border-width:thin; width:80%">
</div>
<div class="cell right">
<img src="./site/Bookmarker.png" alt="popup" style="border:solid; border-width:thin; width: 80%">
</div>
</div>

A topic is a category or a tag or any way you want to group a set of web pages. Topics can be nested inside each other to any depth. All topics and saved pages have associated notes. By making it easy to quickly save a web page under a specific topic and drop in a text note, BrainTool allows you to build up your own topic map - a map of all of the information you want to keep track of.

Getting your links and notes into BT is easy, but once there they give you a unique ability to control your browser and navigate your online resources. From the Topic Manager you can open and close individual pages or open all pages for a topic into a tabgroup or new window, as well as see which pages are open and pop any one to the top. Everything is controllable via keyboard commands in addition to the mouse. This ability to navigate sites and tabs from the Topic Manager and control tabs, tabgroups and windows in the browser can greatly improve your browser workflow.

Finally, all of the above takes place in the browser. But BrainTool doesn't want to lock all this valuable information away! Underlying what you see on the screen is a plain text based representation. You can turn on a continuous sync to a local or Google Drive file or manually save versions of your topic map. Beyond just being a backup this allows you to share your topic map across browsers as well as access and edit your notes and links in any text editor.


## Installation
<div class="row">
<div class="cell left" style="text-align:justify">
Install BrainTool from the <a href="https://chrome.google.com/webstore/detail/braintool-beyond-bookmark/fialfmcgpibjgdoeodaondepigiiddio">Chrome</a> or <a href="https://microsoftedge.microsoft.com/addons/detail/braintool-beyond-bookma/igibjpnabjgljgnfajjpapocagidmeol">Edge</a> store. You will need to grant permissions for BT to see your browsing history and access your bookmarks. This puts a small extension inside your browser and adds the BT icon. The icon shows on your browser bar or under the generic extension 'puzzle-piece' icon. Pin the icon to your browser bar using the push-pin icon.
</div>
<div class="cell right">
<img src="./site/initialInstall.png" alt="Install" style="border:solid; border-width:thin; width:90%; margin-left:2rem;">
</div>
</div>
BrainTool is launched by clicking the icon, or using the Alt/Option-b keyboard accelerator. When first launched it will open the Topic Manager and walk through a brief introduction. The Topic Manager comes pre-populated with a small default set of topics. You can add your data into this structure or delete it and create your own. By default BrainTool (BT) launches in an independent sidepanel browser window. Position it wherever works best for you, the Topic Manager will re-open in the position it was last closed from.

## Assigning a Topic - the Bookmarker
<div class="row">
<div class="cell left" style="text-align:justify">
To save the current web page into BrainTool just hit the icon or keyboard accelerator. This will open the BT Bookmarker with the Topic field selected.
<br/><br/>
The topic selector shows an overview of your current topics in a navigable tree. You can select one with your mouse or just start typing. Auto-complete will show possible topic options. Hit enter to select. If BT has a good guess as to the topic it might be pre-populated. In this case either just hit enter to use it, or delete to clear out the suggestion. If you leave the topic blank the default '📝 Scratch' topic will be used.
</div>
<div class="cell right">
<img src="./site/SaverSuggestions10.png" alt="popup" style="border:solid; border-width:thin; width:110%; margin-left:2rem;">
</div>
</div>
If a topic name is not unique the auto-complete will show a colon:separated hierarchy. Typing in an unknown topic will create a new one at the top level. Entering an existing topic followed by a colon:subtopic creates a new subtopic under that parent topic (EG Projects:My new project). Topic names can have spaces.

You can add a note or just hit Save. You can also edit the page title which is how the page will be identified in the topic tree.

The 'Save Tabgroup', 'Save Window' and 'Save Session' check-boxes allow you to save all open and unsaved pages in the tabgroup, browser window, or all windows. These operations will save multiple new rows into the Topic Manager and consequently don't capture a note or title. NB pinned tabs are not saved.

Hitting Save or Save and Close will save the page into your topic map and close the Bookmarker. You can choose to close the page(s) after saving or leave it open grouped with its peers of the same topic.

## The Topic Manager
The Topic Manager allows you to search, edit and change your topics and to control the browser. You can select it as you would any other browser window, or double click the icon or use the accelerator Alt/Option-b-b (ie hit b twice) to pop it into focus.

The Topic Manager shows your topic hierarchy in an expandable table. The small triangle next to topics allows you to expand or collapse the hierarchy. Pages that are open in a tabgroup are highlighted in that tabgroups color, ungrouped open tabs show in pale blue as do topics which have one or more of their pages open.

Hovering your mouse over a row in the table reveals a set of buttons that perform operations on that row. As shown below, right to left, the operations are as follows:

<img src="./site/rowButtons.png" alt="Row Buttons" style="width:80%; margin-left:5rem;">
- **More/Fewer Tools:** Expand to show the full set of tool buttons, or shrink to show the summary set.
- **Close:** Close an open tab or all open tabs for a topic.
- **Open Tab:** Open the page in a tab or all the topics pages in a set of tabs.
- **Open in Window:** Open in a new browser window. This can be useful to separate out groups of tabs.
- **Edit:** Show the Topic card associated with the entry. This allows you to change the topic's title or a pages label or url, as well as to edit the notes for the item.
- **Add Child:** Create a new child topic under this one and open its Topic card.
- **Promote:** Move the item up the topic hierarchy.
- **Move:** Allow the item to be dragged elsewhere in the hierarchy and dropped into a new position. If it's a topic node all its children will be moved along with it. Note, clicking and holding anywhere in the items row will initiate the drag operation.
- **TODO:** Each item in the table can be assigned as a TODO or DONE. This button toggles between the TODO states. Note also that adding :TODO after the Topic name in the Saver will mark the item as a TODO.
- **Delete:** Delete the row's page or topic. If it's a topic also delete all its children. In the latter case a confirmation warning will be shown.

Note not all tools apply to every item and so not all will be shown every time. All the tools can also be accessed using keyboard accelerators.

## Keyboard Accelerators
<div class="row">
<div class="cell left"><br/>
<img src="./site/Help10.png" alt="Key commands" style="border:solid; border-width:thin; width:90%; margin-right:2rem;">
</div>
<div class="cell right">
BrainTool is designed to allow you to work more efficiently in your browser. One way of speeding up your work is to use the keyboard accelerators. Accelerators can access all the tools described above, as well as navigating and searching through the tree. Hitting 'h' or '?' will show all the available keyboard commands. BrainTool uses the Alt (PC) or Option (Mac) key as a control key to avoid conflict with other browser keyboard shortcuts.
<br/><br/>
One thing to note here is that BT has the notion of a 'selection', which is the table row that is currently selected. This is the one on which keyboard commands will operate. It is shown in green in the tree.
</div>
</div>
## Search

S, or /, is the Search accelerator, or just click into the search box. As you type the next matching row will be selected and shown with matching text highlighted, searching downward from the current selected row (or the top row if there is no selection).

Hitting Alt/Option-s will select the next matching row. If search hits the bottom row without a match the search box will show in pale red. Hitting Opt-s again will loop the search around to the top row.

R is Reverse search, it works like search but searches upward from the selection (or from the bottom row). At any point you can use alt-s or -r to find the next or previous match.

Hitting Enter exits search leaving you with the selected row, which you can then operate on (eg open in a browser window by hitting enter again, or edit by typing 'e').

Note that search will find matches in the link title, link url and your notes, in open as well as hidden rows. The url, which is usually not displayed, will be shown if it contains the only match in the row.

In addition to the key commands, buttons for Up, Down and eXit are shown next to the search box and can be used when search is active.

There's also a brief demo video on [this blog post]({% post_url 2021-10-06-Control-Your-Browser-with-the-Keyboard%}) (using an older version of the UI).

## Settings and Actions
Settings control the configuration of your BrainTool. Actions are system-wide operations. The settings and actions panels can be accessed from the relevant buttons in the top right of the Topic Manager.
<div class="row">
<div class="cell left">
<img src="./site/CollatoralMaterial/Settings.png" alt="side-panel" style="border:solid; border-width:thin; width:80%">
</div>
<div class="cell right">
<img src="./site/Actions.png" alt="popup" style="border:solid; border-width:thin; width: 80%">
</div>
</div>

### Actions
There are a number of Import and Export tools. You can import from browser bookmarks, an org-mode text file or an exported file from the TabsOutliner extension. You can export your topic hierarchy back out to browser bookmarks or to a local org-mode format text file. If org-mode and TabsOutliner are not familiar to you don't worry about it, they are not important! (Note that importing can take some time if you have a lot of data.)

If file syncing is enabled (see below) Actions also shows a button allowing a file refresh and another to turn syncing off.

### Settings
Via the 'Topic Manager Location:' selector you can change the default location of the Topic Manager such that it opens in a standard browser tab rather than the standalone side panel. To effect the change, toggle the setting and then close and re-open BrainTool.

A controllable option on the panel determines whether BT tabs are grouped by tab groups or opened as individual tabs wherever the browser puts them. The default, Tab Groups, uses the tabgroup functionality in Chrome and Edge (as well as Brave and some other Chromium-based browsers) to give a visual indication in the browser of which tabs are associated with the same topic. Tabgroups can be named and colored by right clicking on the tab group indicator in the browser. The tabgroup will show the corresponding topics name. Dragging tabs into, or out of, the tabgroup will add or remove them from the associated BT Topic.

There is the option to sync your personal braintool topic map to a file on your local machine, or associated with a Google Drive account. If you have a Google account you can walk through an authorization step to allow BT to write all your data into a file you can access via Drive (in addition to saving it in browser storage). Alternatively you can sync to a local file which can then subsequently also be saved to DropBox, github or some other cloud storage.

Note that you can only sync to one external file source. With GDrive Google will automatically keep incremental versions of your BrainTool file which can help with recovery if you overwrite or delete your data, whereas the local file will be changed on each update. In either case you should consider periodically exporting your data (via Actions) to save a backup copy.

Note also that GDrive syncing requires walking through Googles authorization process to give BrainTool access to read and write the files. Unfortunately this process requires popups and cookies, two browser features that Google is actively trying to restrict! Make sure your browser allows cookies from accounts.google.com and popups from both accounts.google.com and braintool.org. Even more unfortunately a recent update on Googles part means that a browser-based tool like BT, which is just code that runs in your browser with no database or back end logic, only gets a cookie valid for an hour. BT will notify you that the cookie has expired whenever the Topic Manager gets focus and you can choose to refresh then or the next time its needed to save the file. Refreshing may or may not force you to walk through the authorization process again.

If you edit the file externally BT will warn you that your data is out of date the next time the Topic Manager gets focus and will offer to refresh from the external version.  You can also use the 'Refresh from File' button in the Actions panel at any point. If you use multiple browsers or machines with the same Google account or with access to the same local file you can share your braintool topics across them (again with a sync to import changes made elsewhere).

The 'Sticky Tabs' setting controls whether or not a tab 'sticks' to the saved item in the tree that it was opened from. When set to be not sticky BT uses a strict matching between the url in a tabs address bar and the item initially saved. This means a server side redirect or a navigation (inside a web app say) which changes the url will move the tab out of its associated tabgroup and unselect its row in the topic tree. When it's set to be on, a tab opened from the topic manager (or saved into the topic manager) will stay marked as open in the tree and associated with the BT item until the tab is closed or clearly being re-used for a different purpose (recognized by the user manually entering a url in the address bar or clicking a bookmark item etc). User research has shown that this notion of having tabs tied to a specific purpose or work item improves overall workflow. If a 'stuck' tab has been navigated to a different url that you want to save separately in the tree invoking the Bookmarker on the tab will let you do so.

The next few Setting control various BT display customizations:
- Use the Dark Mode theme
- Show favicons for saved pages
- Use the new Dense Mode to fit more on the screen
- Toggle the notes column
- Use a larger font size.

<div class="row">
<div class="cell left">
Finally you have the option to upgrade to a 'Supporter' version of BrainTool based on a monthly or annual subscription or one-time purchase.<br/>
After the 30 day trial period the display customization settings are locked for non supporters and a friendly solicitation  message is shown on startup. See the <a href="../pricing">Pricing</a> page for details.
</div>
<div class="cell right">
<img src="./site/CollatoralMaterial/trialExpired.png" alt="side-panel" style="border:solid; border-width:thin; width:90%">
</div>
</div>

# Warnings, Messages and Tips
The BT Message pane is shown each time the Topic Manager is opened. It shows a Warning if there is a file version mismatch, a Message if there's something new to bring to your attention or else a random tip on the use of BT. The pane can be closed using the button the left. Messages and tips can be cycled through using the More ('>>') button on the right.

Here are all the tips for reference. Send suggestions for inclusion to braintool.extension@gmail.com and maybe they'll end up in the app!

- Add ':' at the end of a topic in the Bookmarker to create a new subtopic.
- Double click on a table row to go to it's tab or tabgroup, if it's open.
- Type ':TODO' after a topic in the Bookmarker to make the item a TODO in the BT tree.
- Create topics like ToRead or ToWatch to keep track of pages you want to come back to.
- You'll need to Refresh if you've been editing the BrainTool.org file directly.
- Option/Alt-b is the BrainTool accelerator key. You can change that in the browsers extension settings
- You can save individual gmails or google docs into the BT tree.
- Save LinkedIn pages under specific topics to keep track of your contacts in context.
- Use the TODO (star) button on a row to toggle between TODO, DONE and none.
- See BrainTool.org for the BrainTool blog and other info.
- Follow <a target='_blank' href='https://twitter.com/ABraintool'>@ABrainTool</a> on Twitter!
- Check out the Bookmark import/export functions under Actions
- You can click on the topics shown in the Bookmarker instead of typing out the name.
- Use the forward (>>) button on the right to cycle through tips
- Double tap Alt/Opt-b, or double click the toolbar icon, to surface the Topic Manager.
- When you have an Edit card open, the Alt/Opt-up/down arrows will open the next/previous card.
- Click on a row to select it then use keyboard commands. 'h' for a list of them.
- You can also store local files and folders in BrainTool. <br/>Enter something like 'file:///users/tconfrey/Documents/' in the browser address bar.
- Try hitting '1','2','3' etc to collapse the tree to that level.
- Import public topic trees and useful links from braintool.org/topicTrees.
- Try the new DARK theme. It's under Settings.
- If you make the Topic Manager window narrow enough it will hide the notes and switch to a single column view
- &#128512; You can use emojis to &#127774; brighten up your topic names. &#128079; &#128736;


For more information see the [FAQ and How-to page](../support) or reach out on the [BrainTool discussion group](https://groups.google.com/u/0/g/braintool-discussion).
