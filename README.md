# box_starter
boxstarter gist

First, install BoxStarter by opening up PowerShell with admin rights.

  . { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; get-boxstarter –Force

Second, run the script by using this command:

  Install-BoxstarterPackage -PackageName 'https://raw.githubusercontent.com/preston-griggs/box_starter/master/drake.txt'

It'll take a bit to install everything.
