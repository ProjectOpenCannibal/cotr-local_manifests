<pre> Cannibal Open Touch Recovery
==================================

Contained are local manifests for building Cannibal Open Touch Recovery.

<ul>
<li>See the following for information on which manifest is appropriate for your device.</li>
</ul>

	Gingerbread / Legacy devices          :    cotr-2.1.1.xml
	Gingerbread-Hybrid / Kindle Fire only :    cotr-2.1.2-hybrid.xml
	Jellybean / Last Gen                  :    cotr2.1.3-jb.xml
	Current Devices			      	:	   CarbonRecovery-LP511.xml

Once the correct manifest has been determined place it in .repo/local_manifests/ within the appropriate Android build tree.

<pre> Please note the following.
==================================

<ul>
<li>Only stable branch tags will be linked in these manifests.</li>
<li>There is a known issue with the 2.1.x touch code on Galaxy S devices. The recovery functionality works properly but buttons and touch do not register; if building for a SGS device a reboot will be required to get out of the calibration routine before hard buttons respond.</li>
<li>Carbon Recovery is a preview, and shall be treated as such. We claim no responsibility if your device causes World War III.</li>
</li>

<ul>
