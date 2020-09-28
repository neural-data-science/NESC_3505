# Batch adding students to a Team

If you have a Windows computer, there is a way to import a CSV file, using [PowerShell command line tools](https://medium.com/@joaquin.guerrero/adding-bulk-users-from-a-csv-file-to-a-microsoft-teams-team-374414b9d8c9)

And there’s also info on Installing PowerShell on a Mac, but it requires several steps and you also have to [install MacPorts then openSSL](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-macos?view=powershell-6)

I hadn’t tried this though - my largest class is 21 people and I just entered them manually. Just for kicks I followed the instructions and it actually does work - I successfully added you and my TA to my “test team”. If you’re comfortable with the command line I’d say it’s definitely worth it - I will probably use this in the future even for 20 students.

One modification to the installation of MacPorts - after installing, before you can run the port command you need to run the following command in a Terminal window:

`echo 'export PATH=/opt/local/bin:/opt/local/sbin:$PATH' >> .zshrc`

Then open a new Terminal window for it to take effect.

One modifications to the instructions in the first link - in Step 6 the correct command is not just `Get-Team` but `Get-Team -User your_netID@dal.ca`  (Subbing in your own netID obviously)
