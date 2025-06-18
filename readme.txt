DaddyLive New Proxy, this is a new setup to the other proxy. Live Events WORK
========================================================================

Quick setup, Sign-in/up to huggingface first

Click the url below then Click the 3 dots (top right side) & select duplicate this space
Give it a name and change it to public.
https://huggingface.co/spaces/tfmsXYZ/dadnewproxy2

When the build says running
Click the '3 Dots' next to settings
Choose 'Embed this Space'. It will show you the url of the space. Your own proxy url, Copy The Url & Keep Safe

Example of how to use your url, Load into any browser to download your playlists
https://your-hugging.hf.space/playlist/channels.m3u8
https://your-hugging.hf.space/playlist/events.m3u8

========================================================================

HuggingFace Setup for more advanced users

1, Download the full repo to your PC, (To download click the code button above and download as zip)
2, Extract the zip file on your pc
3, Now sign up for a FREE ACCOUNT - https://huggingface.co - This is going to host your proxy/streams
4, On HuggingFace look to the top‑rightish corner & click 'Spaces' Then Click 'New Space'
5, Name: Enter any name you want
6, Select the Space SDK: Choose 'Docker'
7, Visibility: Select/Leave Public
8, Click Create Space
9, Click The Files Tab Then click 'Contribute' now click 'Upload Files' & upload all the extracted files from Part 2 (Drag & Drop)(just upload the files inside the folder and not the folder itself)
10, Now Click 'Commit New File To Main' (Its at the bottom) & WAIT.... for the build to say 'RUNNING'
11, Click the '3 Dots' next to settings
12, Choose 'Embed this Space'. It will show you the url of the space. Your own proxy url, Copy The Url & Keep Safe

========================================================================

Self Hosting NEEDS TESTING MIGHT NOT WORK

1, Clone the repo:
git clone https://github.com/MarkMCFC/NewDadProxy

2, SSH into the daddy folder (which is called NewDadProxy):
cd NewDadProxy

3, Launch the service:
docker-compose up -d --build

Visit https://forum.tfms.xyz for more
