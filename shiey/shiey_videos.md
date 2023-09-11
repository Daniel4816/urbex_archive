#### Videos not available from official sources

Rooftop Escape From Armed Man (POST-ENCOUNTER)  
2016/10/15  
[https://www.youtube.com/watch?v=sqaWGbNlkIE](https://www.youtube.com/watch?v=sqaWGbNlkIE)   
[discord cdn]()
<video id="videoPlayer" autoplay autobuffer controls></video>

<script>
var videoPlayer = document.getElementById('videoPlayer')

var vArray = [
    "https://cdn.discordapp.com/attachments/930023820365037588/1150803008762937385/NEON_Skyscraper_Climb_in_Paris._turned_on_power-6.mp4",
    "https://cdn.discordapp.com/attachments/930023820365037588/1150803259485847652/NEON_Skyscraper_Climb_in_Paris._turned_on_power-1.mp4",
    "https://cdn.discordapp.com/attachments/930023820365037588/1150803268335829052/NEON_Skyscraper_Climb_in_Paris._turned_on_power-2.mp4",
    "https://cdn.discordapp.com/attachments/930023820365037588/1150803279832420362/NEON_Skyscraper_Climb_in_Paris._turned_on_power-3.mp4",
    "https://cdn.discordapp.com/attachments/930023820365037588/1150803284307742720/NEON_Skyscraper_Climb_in_Paris._turned_on_power-4.mp4",
    "https://cdn.discordapp.com/attachments/930023820365037588/1150803288804044951/NEON_Skyscraper_Climb_in_Paris._turned_on_power-5.mp4",
]

videoPlayer.src = vArray[0]

i = 1
videoPlayer.onended = function(){
    if (i < vArray.length) {
        videoPlayer.src = vArray[i]
       i++
    }
}
</script>