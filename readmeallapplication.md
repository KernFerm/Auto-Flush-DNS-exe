`Right-click` on the .exe file:

Locate the downloaded .exe file on your computer.
`Right-click` on the .exe file to open the context menu.
Select `Properties`:

In the context menu, select `Properties` at the bottom. This will open the Properties window for the file.
Navigate to the Digital Signatures tab:

In the Properties window, navigate to the `Digital Signatures` tab at the top.
View Certificate:

Select the signature from the list of signatures and click on the `Details` button.
In the Digital Signature Details window, click on the `View Certificate` button. This will open the certificate details.
Install Certificate:

In the certificate details window, navigate to the `General` tab.
Click on the `Install Certificate...` button at the bottom. This will launch the Certificate Import Wizard.
Welcome to the Certificate Import Wizard:

The Certificate Import Wizard will open with a welcome screen. Click `Next` to continue.
Choose Certificate Store:

Select `Place all certificates in the following store`.
Click the `Browse` button to select the certificate store.
Select Certificate Store:

In the Select Certificate Store window, choose `Trusted Root Certification Authorities`.
Click `OK` to confirm the selection.
Complete Wizard:

Back in the Certificate Import Wizard, click `Next` to continue.
Review the information provided and click `Finish` to complete the wizard.
Confirmation:

If prompted, confirm that you want to install the certificate by clicking `Yes`.
Once the certificate is installed, you should see a confirmation message indicating that the import was successful.
Restart Applications:

Restart any applications that use SSL/TLS connections, including the application associated with the downloaded .exe file, to ensure that the changes take effect.
