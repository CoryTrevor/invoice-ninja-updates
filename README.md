<h3>Invoice Ninja Updates</h3>
A bash script for updates to avoid PHP timeouts without having to use GitHub + Composer <br><br>

<b>Disclaimer</b>  

The script has not been tested in different environments  
Always do a full backup of your installation before running any updates

<b>Notes</b>  

Before running the script, enter the variables for your installation in the 'Define Installation Variables' section.

The script backs up .env, the logo image and PDFs in /public/storage, /storage/logs and the snappdf/versions directory. Any other files that aren't included in the latest release will be removed from the installation directory so if you have anything else in there to keep make sure to add them in the script where it says # Uncomment and edit the line below to add any other folders or files that you'd like to keep. 

<b>Instructions</b>  

Upload the update.sh file to the Invoice Ninja installation's parent directory i.e. not the directory that contains the Invoice Ninja files, the directory above it.

To run: bash update.sh  
