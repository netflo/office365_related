![image](https://github.com/netflo/office365_related/assets/41306895/b9b531ca-ad1f-4172-a35c-b221135b905d)# office365_related

this link to save Stream video for the long run if you dont want them to be deleted as they will expire at some point ...
https://www.lisenet.com/2022/how-to-download-view-only-teams-meeting-recording-video-from-sharepoint/

To save video:

	1. Open stream and play video in browser
	2. Start Dev Tool and go to network tab
	3. Hit refresh
	4. Filter for "videomanifest"
	5. Right click the link
	6. Copy the link (or it may say URL)
Start ffmpeg -i "the copied link" -codec copy video.mp4
