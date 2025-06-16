DaddyLive New Proxy, this is a new setup to the other proxy

Example of how to use your url
https://your-hugging.hf.space/playlist/channels.m3u8
https://your-hugging.hf.space/playlist/events.m3u8

HuggingFace Setup
1, Download the full repo to your PC, (To download click the code button above and download as zip & then extract the zip file)
2, Now sign up for a FREE ACCOUNT - https://huggingface.co - This is going to host your proxy/streams
3, On HuggingFace look to the top‑rightish corner & click 'Spaces' Then Click 'New Space'
4, Name: Enter any name you want
5, Select the Space SDK: Choose 'Docker'
6, Visibility: Select/Leave Public
7, Click Create Space
8, Click The Files Tab Then click 'Contribute' now click 'Upload Files' & upload all the files extracted in Part 1 (Drag & Drop)(just upload the files inside the folder and not the folder itself)
9, Now Click 'Commit New File To Main' (Its at the bottom) & WAIT.... for the build to say 'RUNNING'
10, Click the '3 Dots' next to settings
11, Choose 'Embed this Space'. It will show you the url of the space. Your own proxy url, Copy The Url & Keep Safe

========================================================================

Quick setup
Ignore everything above and click the url below, click the 3 dots (top right) and select duplicate this space
Give it a name and change to public.
https://huggingface.co/spaces/dadproxy-tfms-xyz/dadnewquicksetup

========================================================================

Self Hosting NEEDS TESTING

1, Clone the repo:
git clone https://github.com/MarkMCFC/NewDadProxy

2, SSH into the daddy folder (which is called NewDadProxy):
cd NewDadProxy

3, Launch the service:
docker-compose up -d --build
