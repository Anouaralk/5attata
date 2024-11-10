<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Play m3u8 Stream</title>
</head>
<body>
    <video id="videoPlayer" width="640" height="360" controls>
        <source src="https://raw.githubusercontent.com/Free-TV/IPTV/master/playlist.m3u8" type="application/x-mpegURL">
        Your browser does not support the video tag.
    </video>

    <script>
        document.getElementById('videoPlayer').addEventListener('error', function(event) {
            console.error('Error loading video:', event);
        });
    </script>
</body>
</html>
