What's the Object Repository?

The Object Repository is a collection of UI elements which we can use inside and across automation projects. This allows us to reuse the elements in different projects, provided they all have the same libraries installed.

Why exactly is the Object Repository useful? First, reusability allows for global use. Secondly, it makes for an easier automation development process, as we don't have to open the applications we automate while designing the workflow. We can simply drag and drop the UI elements on top of the Designer panel or activity, for faster configuration.

These elements are organized in libraries: groups of UI elements that can be installed just like any other activity package. RPA Developers create these libraries and then make them available for other users within a company or publicly.

How can I install a library?

For already added libraries: In the Manage Packages window, identify the feed where the library is or search for it in the search bar, then install it to your project. The contents of the library will then appear in the Object Repository panel.
Installation from scratch: In the Manage Packages window, go to Settings, then click on the "+" sign, enter the name, paste the folder path to the library in the Source field, click on Add, then go to the library feed and install it to the project. The contents of the library will appear in the Object Repository panel.
For visual guidance, check out the video demo!

In developing the automation you'll use the following input files, websites, and applications:

The Double UI App - this is the dummy bank teller app we'll be using to get the transaction numbers.
UI Automation - Input File - this is the spreadsheet we'll be working with, containing information about the transactions and needing to be filled in with the transactions' numbers.
The DoubleUI NuGet package - this contains the UI elements for this workflow, which will be available in the Object Repository upon installation.