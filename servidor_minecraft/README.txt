###		Want a fast and reliable server?								###
###		Beyond Mines: Exopshere is available on Bisecthosting.com	###
###		Use code: LEONNICLASS 	for special discounts 			###






Official instructions and tutorials on:

https://beyondmines.net/play-together







Common questions:



	Powershell window closes right away?
		
		Here is an alternative guide:

		1. Unzip/extract the downloaded serverpack files and open the serverpack folder.

		2. Open Windows "Powershell" as an adminstrator.

		3. Drag and drop the "start.ps1"into the Powershell window.
		
		4. Copy and paste " -ExecutionPolicy Bypass" to the Powershell command prompt

			Command should look like that for example:
			"C:\Users\PC\Desktop\serverpack_folder\start.ps1 -ExecutionPolicy Bypass"

		5. Press Enter to run the commmand and start the server. Now proceed with step 3 of the original instruction.



	"user_jvm_args could not be found"?

		Try a system restart first, Java can be weird on Windows.
	
		Have you installed Java in the past?
		Remove these installations since Eclipse Temurin is an open source Java SE build based upon OpenJDK and
		nothing else is needed and can lead to such problems. Restart your System after each Java related change just to be safe.



	Why is the view distance set so low?

		Beyond Mines modpacks include the mod FarSight.
		FarSight caches server chunks on client side,
		allowing for a greater view distance on client side,
		without harming server performance.