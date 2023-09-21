# Kingpin: Life of Crime v1.21 "ReadError: function pointers have moved" Load game fix
<p>WARNING: Older savegames files might not work with this modification, please backup your original "gamex86.dll" before using the modified one.</p>
<h2>Description:</h2>
<p>Modification of the Kingpin: Life of Crime v1.21 gamesrc, fixes the 
infamous "ReadError: function pointers have moved" problem with loading 
a savegame on Windows 11.</p>
<p>Copyright Xatrix Entertainment, Interplay and iD Software.</p>
<h2>Compiling (Windows only):</h2>
<p>To Compile the gamesrc you'll need to download Microsoft Visual Studio Express 2012: 
<a href="http://download.microsoft.com/download/1/F/5/1F519CC5-0B90-4EA3-8159-33BFB97EF4D9/VS2012_WDX_ENU.iso" target="_blank"> Download</a></p>
<p>Once you've download and installed Visual Studio Express you'll need to
clone the repo and open the file "kingpin_gamesrc_fix.sln", then go to 
"BUILD" in the top bar and click on "Build Solution". Once it compiles, 
go to the "Release" folder (which is in the repo folder) and copy the "gamex86.dll" into your Kingpin/main folder.</p>
<h2>Credits:</h2>
<p>QuakeTools for the Github Repo and Xatrix Entertainment for the Kingpin SDK.</p>
