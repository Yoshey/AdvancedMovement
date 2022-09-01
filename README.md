<h1>Advanced Movement Module (AMM) by Yoshey for Pavlov VR</h1>
<h3>Version 2.1 - 2021</h3>
Ingame Showcase: https://steamcommunity.com/sharedfiles/filedetails/?id=2221534545
<br>
<ul><h3>Features</h3>
  <li>Climbing (With VR Controllers)</li>
  <li>Grabbing (Interactive Drawers, Levers, Doors etc)</li>
  <li>Swimming (Only Custom Gamemodes)</li>
  <li>Replicated Physics Interactibles (Pickup and Hand-Pushing)</li>
  <ul>
    <li>Pick Up</li>
    <li>Push with Hands</li>
    <li>Replicated</li>
  </ul>
  <li>Velocity based Falldamage (By Mottflyer)</li>
  <li>Parachuting (By Mark Dey)</li>
  <li>Jumping</li>
  <ul>
    <li>Bunny Hopping</li>
    <li>Changeable Jump Button</li>
  </ul>
</ul>
<h2>Note: Due to my personal life such as University, I cannot always work on this project</h2>
<br>
All logic, art assets and models are ultimately owned by Yoshey, if not stated otherwise in Credits.txt
<br>
<br>
<b>BE SURE TO READ <i>"License - ReadMe.txt"</i></b>
<br>
<br>
<h3>Special thanks to all the Donators that supported me while creating this!</h3>
<br>
If you do not have the Pavlov Workshop Plugin, you must link your UE4 account with your
GitHub account to get access to the plugin.
<br>
<br>
<br>
<h3>Extra</h3>
The Advanced Movement Module works best for custom gamemodes. Some parts will break or fail with default gamemodes.
<br>
<br>
You can modify some features by changing the "Configuration" variables such as enabling/disabling jumping and setting some BunnyHopping parameters.
<br>
<br>
<h5>The Advanced Movement Module is Licensed under the
Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)</h5>
<br>
<br>
<br>
<br>
<h3>Version History:</h3>
<b>2.1</b><br>
<ul>
	<li>Fixed going through walls while climbing</li>
	<li>Improved swimming out of water onto sloped surfaces</li>
	<li>Added variable for jump height</li>
	<li>disabled shooting while jumping</li>
	<li>Fixed in-editor desktop debug pawn</li>
</ul>
<b>2.0a</b><br>
<ul>
	<li>Made Swimming possible for Default Gamemodes</li>
	<li>Velocity Based Falldamage now works for Default Gamemodes</li>
	<li>Updated the installation documentation for a more reliable installation method</li>
</ul>
<b>2.0</b><br>
<ul>
	<li>Added Swimming (currently only works for Custom Gamemodes)</li>
	<li>Added Climbing and Swimming Animations</li>
	<li>Added Pickup-able Physicsobjects with Replication</li>
	<ul>
		<li>Added BeachBall</li>
	</ul>
	<li>Added Haptic Feedback (Controller Rumbling)</li>
	<li>Cleaned up Code</li>
	<ul>
		<li>Removed the Events "Child Tick" and "Child Beginplay" (this should be done in reverse, "Parent Tick" and "Parent Beginplay"</li>
		<li>Renamed Property Categories such as "Advanced Movement (Modify me!)" to "AMM Properties" make sure to doublecheck your custom Properties!</li>
	</ul>
	<li>Added the Plugin "AMMTools" for easier in-editor developement, including a VR and FPS pawn</li>
	<li>Removed the included Pavlov's CustomMapTools. They need to be downloaded and imported manually (to ensure people receive the latest versions)</li>
	<li>Updated "Installation&Info" to an .pdf with images</li>
</ul>
<b>1.4b</b><br>
Be sure to rename your folders as seen below and fix up redirectories before updating, or your custom blueprints will break when updating
<br>
<br>
<ul>
	<li>Renamed some File Paths to shorten overall path length</li>
	<ul>
		<li>Content\AdvancedMovement -> Content\AMM</li>
		<li>Content\AdvancedMovement_Examples -> Content\AMM_Examples</li>
	</ul>
	<li>Changed Climbing_Box visuals (its now blue and thicker lines)</li>
	<li>Changed the Falldamage Types to an Enum Structure (You can now Select between "Disabled" "Velocity Falldamage" and "Pavlov Falldamage" in the gameinfo)</li>
	<li>Added Example Child-Proxies with Variable Previews</li>
	<li>Redid the example climbing blueprints since they kept breaking when being moved</li>
</ul>
<b>1.4</b>
<ul>
  <li>Reworked the HandProxy from Scratch</li>
  <ul>
    <li>Fixed Climb events triggering multiple times</li>
    <li>New Event Dispatchers (one hand, two hands)</li>
  </ul>
  <li>Fixed some AMM Player Proxy Bugs (Sometimes not receiving all Variables) and improved Setup Time</li>
  <li>Added Oculus Keybind Buttons (Example: FaceButton2 -> B)</li>
  <li>Fixed Settings Menu Buttons overlapping with the Border</li>
  <li>Added Text-To-Speech 0-10 Countdown for Debugging</li>
  </ul>
<b>1.3</b>
<ul>
  <li>Added Grabbing Logic</li>
  <ul>
    <li>Added Grabbing Linear (Drawers etc)</li>
    <li>Added Grabbing Rotator (Levers, Doors etc)</li>
  </ul>
  <li>Added a "no Falldamage" Volume</li>
  <li>Newest Version Number now gets fetched directly from Github</li>
  </ul>
<b>1.2</b>
<ul>
  <li>Made Climbing compatible for Vanilla Gamemodes (Prevent Falldamage)</li>
  <li>Made Jumping compatible for Vanilla Gamemodes</li>
  <li>Jump Settings button hides automatically if jumping is disabled</li>
  <li>Added a few more options like "Enable Vanilla Falldamage"</li>
</ul>
<b>1.1b</b>
<ul>
  <li>Hotfix for:</li>
    <ul>
    <li>Jump Settings Loader</li>
    <li>missing mesh reference</li>
    <li>BHop Max speed Calculator</li>
    </ul>
</ul>
<b>1.1</b>
<ul>
  <li>Added Mottflyer's Velocity based Falldamage</li>
  <li>Added Mark Dey's Parachute Falling</li>
  <li>Fixed some Left/Right mixup for the Keybinds</li>
  <li>Fixed Settings Menu not detecting if it's a Community Server properly</li>
  <li>Fixed Bunnyhopping causing you to jump less higher</li>
</ul>
<b>1.0</b>
<ul>
  <li>First Release</li>
</ul>

