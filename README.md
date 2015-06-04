# Wakanda-widgets

In this repository, you can share your custom Wakanda widgets with the community.

## How to create a custom widget for [Wakanda](http://wakanda.org)

For information abour creating a custom widget, refer to the [Widgets v2 Creating a Widget](http://doc.wakanda.org/Wakanda0.DevBranch/help/Title/en/page3849.html) documentation.

## How to request your widget to be added to this list

To have your widget's repository added to the **wakanda-widgets** list:

1. Fork the **Wakanda-Packages/wakanda-widgets** repository to your personal account: {myUsername}/wakanda-widgets

2. Clone the **{myUsername}/wakanda-widgets** repository to your machine.

3. ADD or UPDATE your **{myUsername}/{myWidget}** into the **{myUsername}/wakanda-widgets** repository

4. Commit and Push your work.

5. Send a Pull request.


### Forking the Wakanda-Packages repository

To fork the **Wakanda-Packages** repository:

1. Go to [https://github.com/Wakanda-Packages/wakanda-widgets](https://github.com/Wakanda-Packages/wakanda-widgets) and fork this repository to your account. 

### Cloning the forked repository

To clone the forked repository to your machine:

1. Clone it to your machine:

		git clone --recursive https://github.com/{myUsername}/wakanda-widgets.git

_**Note**: myUsername and myWidget must be replaced by your username and your widget name._

2. Sync your fork back to the remote:

		cd wakanda-widgets
		git remote add upstream https://github.com/Wakanda-Packages/wakanda-widgets.git
		
### Adding a widget as a submodule to your repository

To add a widget as a submodule to your **{myUsername}/wakanda-widgets** repository:

1. Go to your **{myUsername}/wakanda-widgets** folder and add your widget as a submodule:

		cd wakanda-widgets
		git submodule add https://github.com/myUsername/myWidget.git 
		
2. Commit your changes to **{myUsername}/wakanda-widgets** repository and push them to Github:

		git add myWidget
		git commit -a
		git push origin master
		
### Updating a widget 

To update your widget:

1. First get the latest from the **Wakanda-Packages/wakanda-widgets** repository:

		cd wakanda-widgets
		git fetch upstream 
		git checkout master 
		git merge upstream/master
	
2. Pull your changes from the **{myUsername}/{myWidget}** to the  **{myUsername}/wakanda-widgets**:

		git pull myWidget origin master   
	
3. Commit your changes to **{myUsername}/wakanda-widgets** and push them to Github:

		git add myWidget
		git commit -a
		git push origin master

### Submitting your add-on to the Wakanda directory

First, go to **https://github.com/{myUsername}/wakanda-widgets** to see your changes. Then, create a new pull request with your latest modifications. 

### Reviewing process
We will review your widget before accepting it. To be accepted, your widget **MUST** include the following:

* a well-formed widget with its corresponding "package.json" file.
* a "readme.md" file with a basic explanation about your widget.
* a "license" file associated with your widget.

## How to use a widget from this list in your project
To use a widget from this list in your project:

1. Download the corresponding submodule by cloning it in GIT or by using the **Download ZIP** button from the widget's repository. You must remove the branch name, like "-master", from the widget's folder so that the folder is the name of the widget.

2. Open Wakanda Studio.

3. Install the widget in your project's **Widgets** folder. For more information, refer to the [Installing a Custom Widget](http://doc.wakanda.org/WakandaStudio0/help/Title/en/page3869.html#1056003) documentation.

3. Open a Page in the GUI Designer.
The newly installed widget appears in the **Widgets** tab depending on the section defined by the custom widget in the GUI Designer.


## Legal Terms

By sending a "pull request" for the Directory and/or by using/downloading content available on the Directory, you agree to be bound by the following terms and conditions. 

###1. Grant of license

By providing content and/or information for the Directory, you :

 * grant Wakanda and all the users of the Directory a worldwide, irrevocable, royalty-free, non-exclusive and unrestricted license to reproduce, edit, publish, translate, and distribute in any medium whatsoever. 
 * agree that Wakanda, its affiliates, and all the users of the Directory can do all things in relation to your content and notably make a derivative work.
 * Agree that Wakanda can bundle your content in its Wakanda’s products.

###2. Warranties

You represent and warrant that: (a) you are the author of such content and have the right to grant this license; (b) the content does not infringe any patent, copyright, trademark, trade secret or other proprietary right of any other party; and (c) no consent of any third party is necessary for exploiting your content as described above.

###3. Indemnification

You shall indemnify, defend and hold harmless Wakanda and its affiliates from and against all liabilities, claims, demands, actions, costs, damages, or losses, including reasonable attorney's fees, initiated by or on behalf of third parties arising out of a claim that your content infringe such third party’s intellectual property rights. 

###4. Disclaimer 

Wakanda does not represent or endorse the accuracy or reliability of any of the information, content contained on, distributed through, or linked, downloaded or accessed from any of the services contained on this Directory nor the quality of any content or information displayed, or obtained by you. 

The service, the content and the information herein are provided by Wakanda on an "as is" and “as available” basis, and Wakanda makes no warranty or representation (express or implied) of any kind, and Wakanda disclaims any and all other warranties, whether express or implied, including, without limitation, any implied warranties of merchantability, integration, satisfactory quality or fitness for a particular purpose.  Without limitation of the foregoing, Wakanda does not warrant that the content and/or information available on the Directory are free from bugs and/or errors and/or that the functions included in the Contents will meet user’s requirements. 

The entire risk as to choice and use of the content and information available on this Directory is with the users of such contents.

In no event shall Wakanda be liable for any direct, indirect, incidental, punitive, or consequential damages of any kind whatsoever with respect to the contents and the information available on this Directory.
