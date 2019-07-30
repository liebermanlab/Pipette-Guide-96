Pipette-Guide-96
================
Making you hate normalization from 96-well plates less.
------------------------------------------------------------

Have to add or take different volumes to/from each well of a 96 well plate?
This will let you do it in less than 15 minutes. <br> <br>
Use this script to generate an html file from a csv and open the html file on a tablet. Then start transfering to/from the highest-volume well (highlighted in yellow) and click to find the next-highest volume well. <br> <br> Add variable amounts of water/buffer to a plate using this tool, then add uniform volumes of sample using a multichannel (or 96-channel) pipette. Voila, you've now got 96 normalized wells.  <br>

Created by Tami Lieberman, 2014.

To run:
------------------------------------------------------------
1) Download the repository folder via the button on the right and unzip. Move it to your Dropbox folder (e.g. ~/Dropbox/Pipette-Guide-96) <br> 
2) Paste desired volumes into volumes.csv <br>
3) Run "python makehtml.py" in the repository folder <br>
4) Open the updated index.html on your tablet/phone and get pipetting <br>

Tips:
------------------------------------------------------------
For easy finding of wells, draw 3 lines on your 96 well plate, as shown in red on the pipette guide. (Between rows D&E, columns 4&5, and columns 8&9) <br>

A shared dropbox between your PC and tablet will allow you to easily open index.html on your tablet. <br>

Rename index.html, so that you can have one html file per plate. <br>

If running on a Mac or Linux machine you can make this slightly faster by double-clicking on generate.sh in step 3. You will need to change the first line of generate.sh to point to the correct directory. <br>

As of May 2016, there are suitable tablets available online for ~$60 (e.g. bestbuy.com, newegg.com)

Example output
------------------------------------------------------------
http://tamilieberman.github.io/PipetteGuide-example.html

Suggestions for improvements welcome!! 
