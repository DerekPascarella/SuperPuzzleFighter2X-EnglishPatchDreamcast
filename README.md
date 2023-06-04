<h1>Super Puzzle Fighter 2X</h1>
<img width="165" height="165" align="right" src="https://github.com/DerekPascarella/SuperPuzzleFighter2X-EnglishPatchDreamcast/blob/main/cover.jpg?raw=true">Download the English translation patch (more information in the <a href="#patching-instructions">Patching Instructions</a> section):
<ul>
 <li><b>GDI Format (Users of ODEs or Emulators)</b><br>Download <a href="https://github.com/DerekPascarella/SuperPuzzleFighter2X-EnglishPatchDreamcast/releases/download/1.0/Super.Puzzle.Fighter.2X.English.v1.0.dcp">Super Puzzle Fighter 2X (English v1.0).dcp</a> for use with <a href="https://github.com/DerekPascarella/UniversalDreamcastPatcher">Universal Dreamcast Patcher</a> v1.3 or newer.</li>
 <li><b>CDI Format (Users Burning to CD-R)</b><br>Download <a href="https://github.com/DerekPascarella/SuperPuzzleFighter2X-EnglishPatchDreamcast/releases/download/1.0/Super.Puzzle.Fighter.2X.English.v1.0.xdelta">Super Puzzle Fighter 2X (English v1.0).xdelta</a> for use with <a href="https://www.romhacking.net/utilities/704/">Delta Patcher</a> (or equivalent tools).</li>
</ul>
This English translation patch combines the original status/information message translation by <a href="https://www.romhacking.net/community/8124/">comradesnarky</a> from <a href="http://rdcproject.blogspot.com/">ReviveDC</a>, along with a new hack that leverage the game's secret built-in language selector to bring players a 100% complete English-language experience out of the box (sans text/graphics related to network play).  A special thanks to <a href="https://cdromance.com/">Spike</a> for pointing out the existence of the secret language-selection menu, which provided a foundation for modifying the game to default to English, rather than Japanese.

<h2>Table of Contents</h2>

1. [Patching Instructions](#patching-instructions)
2. [Credits](#credits)
3. [Release Changelog](#release-changelog)
4. [What's Changed](#whats-changed)
5. [Important Notes](#important-notes)

<h2>Patching Instructions</h2>
<ul>
 <li><b>GDI Format (Users of ODEs or Emulators)</b><br><img align="right" width="250" src="https://github.com/DerekPascarella/UniversalDreamcastPatcher/blob/main/screenshots/screenshot.png?raw=true">The DCP patch file shipped with this release is designed for use with <a href="https://github.com/DerekPascarella/UniversalDreamcastPatcher">Universal Dreamcast Patcher</a> v1.3 or newer.  Note that Universal Dreamcast Patcher supports both TOSEC-style GDI and Redump-style CUE disc images as source input.<br><br><ol type="1"><li>Click "Select GDI or CUE" to open the source disc image.</li><li>Click "Select Patch" to open the DCP patch file.</li><li>Click "Apply Patch" to generate the patched GDI, which will be saved in the folder from which the application is launched.</li><li>Click "Quit" to exit the application.</li></ol></li>
 <br>
 <li><b>CDI Format (Users Burning to CD-R)</b><br><img align="right" width="250" src="https://i.imgur.com/r4b04e7.png">The XDelta patch file shipped with this release can be used with any number of Delta utilities, such as <a href="https://www.romhacking.net/utilities/704/">Delta Patcher</a>. Ensure the source CDI has an MD5 checksum of <tt>07BEF82A4E0F51CC3B8F6CED3335D88E</tt>.<br><br><ol type="1"><li>Click the settings icon (appears as a gear) and enable "Backup original file" and "Checksum validation".</li><li>Click the "Original file" browse icon and select the unmodified CDI.</li><li>Click the "XDelta patch" browse icon and select the XDelta patch.</li><li>Click "Apply patch" to generate the patched CDI in the same folder containing the original CDI.</li><li>Verify that the patched CDI has an MD5 checksum of <tt>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</tt>.</ol></li>
</ul>

<h2>Credits</h2>
<ul>
 <li><b>Hacking</b></li>
  <ul>
   <li>Derek Pascarella (ateam)</li>
  </ul>
 <br>
 <li><b>Original Status/Information Text Translation</b></li>
  <ul>
   <li>comradesnarky</li>
  </ul>
 <br>
 <li><b>Special Thanks</b></li>
  <ul>
   <li>Spike</li>
  </ul>
</ul>

<h2>Release Changelog</h2>
<ul>
 <li>Version 1.0 (2023-06-04)</li>
 <ul>
  <li>Initial release.</li>
 </ul>
</ul>

<h2>What's Changed</h2>
<img align="right" width="149" height="112" src="https://github.com/DerekPascarella/SuperPuzzleFighter2X-EnglishPatchDreamcast/blob/main/screenshot.png?raw=true">Below is a high-level list of changes implemented for this English translation patch.
<br><br>
<ul>
 <li>All information and status messages appear in English.</li>
 <li>All in-game dialogue text appears in English.</li>
</ul>

<h2>Important Notes</h2>
Because this patch purposefully does not hardcode the English-language setting ubiquitously throughout the game, the secret "extra" options menu remains functional.  If booting the game with this patch applied while using a VMU containing an old save from the original Japanese retail version (or the previous incomplete English translation patch), the language setting present at the time of writing said save file will be restored.  Ultimately, this means no in-game dialogue text will appear in English.  If a player wishes to continue using their old save file, two options exist to remedy the problem.
<br><br>
<ol>
 <li>Delete the old save file from the VMU, or use a different VMU where no such save is present.</li>
 <li>Enter the secret "extra" options menu to set the game's language to English.</li>
  <ul>
   <li>After the title screen, navigate down to the "OPTIONS" setting.</li>
   <li>Hold the L and R buttons on the controller, then press Start to select "OPTIONS".</li>
   <li>Inside the menu that appears, select "ALL GAMES".</li>
   <li>Navigate down to "Version", then select "U.S.A.".</li>
   <li>Navigate down and select "Exit" to return to the main menu.</li>
 </ul>
</ol>
