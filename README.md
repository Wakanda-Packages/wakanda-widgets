# Wakanda-widgets

In this new repository, you can share your custom Wakanda widgets with the community.

## How to create a widget for [Wakanda](http://wakanda.org)

Please refer to the documentation on the Wakanda website : [http://doc.wakanda.org/](http://doc.wakanda.org/)

* [Creating a Custom Widget (v6)](http://doc.wakanda.org/Wakanda0.DevBranch/help/Title/en/page3849.html)
* [Creating a Custom Widget (v1-5)](http://doc.wakanda.org/WakandaStudio0/help/Title/en/page2040.html)

## How to request for your add-on repository to be added to this list

To have your add-on repository (widget, theme, extension or module) added to one of our lists, please follow the below steps:
#####ps. The procedure is the same for themes, extensions, modules and etc. 

1. Fork the Wakanda-Packages/{wakanda-widgets} to your personal repository (just once)
2. Clone the forked repository to your machine (just once)
3. ADD or UPDATE your add-on 
4. Commit and Push your work
5. Send a pull request

Below the details of each phase :

***

#### Fork it!

1. Using the github interface, fork the https://github.com/Wakanda-Packages/wakanda-widgets to your account. 

2. Clone the forked repository:

	git clone --recursive https://github.com/myUsername/wakanda-widgets.git


3. Sync your fork back to the remote:

	cd wakanda-widgets
	
	git remote add upstream https://github.com/Wakanda-Packages/wakanda-widgets.git

***

#### To ADD a widget 

1. Add your add-on widget as a submodule:

	git submodule add https://github.com/myUsername/myWidget.git myWidget

***

#### To UPDATE a widget 

1. First update and sync with the wakanda-widgets repository :

	git fetch upstream 

	git checkout master 

	git merge upstream/master
	

2. Update your submodule 

	git submodule update --remote myWidget

***


#### Commit and Push

1. Commit your changes to your local repository and push them to Github
	git commit -a
	git push origin master

***

#### Submit your add-on to the Wakanda directory

1. Go to https://github.com/myUsername/wakanda-widgets and create a new pull request with your latest additions. 

## It’s done !

***

We will review your widget before accepting it. To be accepted, your widget *MUST* include the following:

* a well-formed widget with its corresponding "package.json" file.
* a "readme.md" file with basic explanations about your widget.
* a "license" file associated with your widget.

## How to use a widget from this list in your project
To use a widget from this list in your project:

1. Download the corresponding submodule by cloning it in GIT or by using the "Download ZIP" button from the widget's repository. The branch name is attached to the name of the archive, so remove the "-master" from the widget's folder so that it is just the name of the widget.

2. To install the widget, refer to [Installing a Custom Widget](http://doc.wakanda.org/WakandaStudio0/help/Title/en/page3869.html#1027761).

3. Open Wakanda Studio.
The new widget will appear in the "Custom Widget" section of the "Widgets" tab in the GUI Designer.


## Legal Terms

By sending a "pull request" for the Directory and/or by using/downloading content available on the Directory, you agree to be bound by the following terms and conditions. 

###1. Grant of license

 By providing content and/or information for the Directory, you :

 * grant 4D and all the users of the Directory a worldwide, irrevocable, royalty-free, non-exclusive and unrestricted license to reproduce, edit, publish, translate, and distribute in any medium whatsoever. 
 * agree that 4D and all the users of the Directory can do all things in relation to your content and notably make a derivative work.
 * Agree that 4D can bundle your content in its Wakanda’s products.

###2. Warranties

 You represent and warrant that: (a) you are the author of such content and have the right to grant this license; (b) the content does not infringe any patent, copyright, trademark, trade secret or other proprietary right of any other party; and (c) no consent of any third party is necessary for exploiting your content as described above.

###3. Indemnification

 You shall indemnify, defend and hold harmless 4D and its subsidiaries from and against all liabilities, claims, demands, actions, costs, damages, or losses, including reasonable attorney's fees, initiated by or on behalf of third parties arising out of a claim that your content infringe such third party’s intellectual property rights. 

###4. Disclaimer 

 4D does not represent or endorse the accuracy or reliability of any of the information, content contained on, distributed through, or linked, downloaded or accessed from any of the services contained on this Directory nor the quality of any content or information displayed, or obtained by you. 

 The service, the content and the information herein are provided by 4D on an "as is" and “as available” basis, and 4D makes no warranty or representation (express or implied) of any kind, and 4d disclaims any and all other warranties, whether express or implied, including, without limitation, any implied warranties of merchantability, integration, satisfactory quality or fitness for a particular purpose.  Without limitation of the foregoing, 4d does not warrant that the content and/or information available on the Directory are free from bugs and/or errors and/or that the functions included in the Contents will meet user’s requirements. 

 The entire risk as to choice and use of the content and information available on this Directory is with the users of such contents.

 In no event shall 4D be liable for any direct, indirect, incidental, punitive, or consequential damages of any kind whatsoever with respect to the contents and the information available on this Directory.
