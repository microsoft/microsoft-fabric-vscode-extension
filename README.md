# Microsoft Fabric for Visual Studio Code

[Microsoft Fabric](https://learn.microsoft.com/fabric/) support for Visual Studio Code is provided through a rich set of extensions that make it easy to discover and interact with the Fabric items and workspaces.

Sign up for [Free Microsoft Fabric Trial capacity](https://learn.microsoft.com/fabric/get-started/fabric-trial#start-the-fabric-capacity-trial) and get Microsoft Fabric is provided free of charge.  It icludes access to the Fabric product workloads and the resources to create and host Fabric items. 

## Data engineeering
Data engineering in Microsoft Fabric enables users to design, build, and maintain infrastructures and systems that enable their organizations to collect, store, process, and analyze large volumes of data. With this extension , you can now develop in VS Code for data engineering needs. 

## Get started with Fabric 
Once you have a Free trial capacity, follow these steps to create a workspace  

1. Sign in to [Microsoft Fabric](https://app.fabric.microsoft.com)
2. Open any Microsoft Fabric experience.
3. Select Workspaces > New workspace.
4. Give the workspace a unique name (mandatory).
5. Provide a description of the workspace (optional).
6. Assign the workspace to a domain (optional).
7. Click on **Advanced** settings to define admins, setup you license for the workspace. If using Trial capacity , use Trial License. 

## Create items in a workspace 
Select new item in your workspace and choose from all available fabric items types such as Lakehouse, Warehouse, Notebooks and more. See [how to create items](https://learn.microsoft.com/fabric/get-started/create-items-in-workspaces).

## Features of Microsoft Fabric extension 

1. Sign in and manage login to Fabric account with VS Code accounts.
2. Creating and open workspaces in you Fabric account.
2. View the items in your workspace and open in Fabric, rename and edit items. You can group them by item type or view then as list. 
3. Open and edit notebooks 
4. Configure a working directory to save workspace items locally.

## Installation

Intalling the Fabric extension will install all of the extensions that you need to work with Fabric. Currently, we support Notebooks, but will be adding support for more workloads in Fabric.

## Sign In

To sign in to your Fabric account,  is simple , simply press `F1` and type in `Fabric: Sign in` (or click on the `Sign in to Fabric...` node in the Explorer).


> Note: You may be prompted for access to your computer's secure credential storage service  so you don't need to sign in every time you start VS Code.

Once signed in, `Select a Workspace` and then view the list of items in the Fabric explorer.

## Open a notebook
You can open a notebook from Fabric explorer by right-clicking the notebook and selecting **Open in Synapse VS Code**. This will open the extension in Synapse extension for VS Code. You need to select the same workspace and open your notebook in Synapse extension. 


## Command Palette

You can access almost all Azure Services provided by these extensions through the Command Palette. Simply press `F1`, then type in `Fabric` to find the available commands.


## Have feedback
You can report issues or provide feedback, using either of these options 
1. [Report issues](https://github.com/microsoft/microsoft-fabric-vscode-extension/issues) directly in our Github repository. 
2. Use the `Feedback` section within the extension

## Telemetry 
Read our privacy statement to learn more. If you don't wish to send usage data to Microsoft, you can set the telemetry.enableTelemetry setting to false. Learn more in our FAQ.

## License

[MIT](LICENSE)
