FlowDynamicRedirect
===================

Flow Sample to show how to use an Apex Plug-in to format a US phone number.
The Apex Plug-in formats all phone numbers to the classic 10 digit number in the (area code) ###-#### format.
It trips out all non digits and formats to 10 digits if 10 long, otherwise returns original.

This is a sample Salesforce ANT package with the Apex Plug-in class and a sample Flow.

Instructions( When using Salesforce Ant)
-----------------------------------------
1. Get the package
2. Modify the build.properties file to point to your salesforce instance
3. run 'ant deployUnpackaged'
4. Run the flow


Instructions( When NOT using Salesforce Ant)
-----------------------------------------
1. Get the package
2. Use the IDE or any other MD API based tool to create the Flow includes in this package
3. Run the flow

