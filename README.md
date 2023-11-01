cleaner.bat discontinued

Prisma PS Injector (DLL INJECTOR) (WORK IN PROGRESS, REWRITING) Usage:
This project is a PowerShell script that creates a simple GUI for injecting DLL files into processes. It uses the Windows Forms framework and the CreateRemoteThread function to inject DLLs.

Open PowerShell with administrative privileges: Click on the Start menu, search for "PowerShell," right-click on "Windows PowerShell," and select "Run as administrator." This will open a powershell window.

Check the current execution policy: In the PowerShell window, type the following command and press Enter: Get-ExecutionPolicy The current execution policy will be displayed, which can be one of the following values:

Restricted: No scripts are allowed to run. AllSigned: Only scripts signed by a trusted publisher can run. RemoteSigned: Downloaded scripts need to be signed by a trusted publisher. Local scripts can run without a signature. Unrestricted: All scripts can run, regardless of their origin or signature. Bypass: No execution policy is enforced. Set the execution policy to Unrestricted: To allow the execution of any PowerShell script, type the following command and press Enter: Set-ExecutionPolicy Unrestricted You will be prompted to confirm the change. Type "Y" and press Enter to proceed.

You have now successfully set your execution policy to unrestricted and can now run this DLL Injector.

To run this, right click the powershell file and click "Run with Powershell". Now select any DLL file and click inject to inject it into the current process.

Restart.vbs (OPEN-SOURCE):
Just like it says in the name, it restarts your computer when you open the file. In my opinion, this is way quicker than a shortcut as it needs to open CMD and then it shuts down. This is also faster for low-end computers.
