---
layout: page
permalink: /video/
---

<iframe width="560" height="315" src="//www.youtube.com/embed/t0N-WbiDuJA" frameborder="0" allowfullscreen></iframe>

<h2 class="video-heading">Juniper <span>May 2015</span></h2> 
Acoustic guitar, four-part humming harmonies, bass, and percussive tapping recorded live on Mother's Day in 2015 on my rooftop in Harlem. Composed on the guitar in drop D tuning, the piece experiments with a 5/4 meter.

<br>
<hr>
<br>

<iframe width="560" height="315" src="//www.youtube.com/embed/mQyBLslQeLc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<h2 class="video-heading">Oh, the Sugars <span>October 2013</span></h2>

Ben Crouse wrote and directed this "comic visual poem" which I scored with recorder, cello, piano, vocals, and triangle. He released it with Grossbus Animation on his birthday, a day before mine. 

<br>
<hr>
<br>

<iframe width="560" height="315" src="//www.youtube.com/embed/9uoWYLm2rXE" frameborder="0" allowfullscreen></iframe>

<h2 class="video-heading">Spotlight On... &amp; Rapid Fire <span>July 2013</span></h2>

I composed, recorded, and performed the soundtracks for Lincoln Center's artist interview web series as a Media Development intern. I edited the footage of Joshua Bell, Claire Chase, and Iván Fischer timed to these underscores.

<br>
<hr>
<br>

<iframe width="560" height="315" src="//www.youtube.com/embed/PR-rKHqk2n0" frameborder="0" allowfullscreen></iframe>

<h2 class="video-heading">Seasonal i-iii. <span>April 2013</span></h2>

A project throughout my years at Columbia, these three movements of chamber music were composed between September 2009 and April 2013. Each movement's themes were conceived during the corresponding season. I conducted this premiere, performed by Columbia ensemble LyricLion (two flute, French horn, bassoon, 2 violins, 2 celli) joined by Juilliard harpist Katherine Siochi. Debussy and Ravel most influenced thi style of chamber music, and the fourth movement was premiered at a later performance.

<br>
<hr>
<br>

<iframe width="560" height="315" src="//www.youtube.com/embed/lXsKIJFXV8s" frameborder="0" allowfullscreen></iframe>

<h2 class="video-heading">Seasonal iv. No Ears <span>February 2014</span></h2>

This fourth movement was composed for LyricLion to conclude the earlier performance. Solomon Hoffman conducted this premiere, performed by his ensemble LyricLion joined by harpist Ellie Kirk.

<br>
<hr>
<br>

<iframe width="560" height="315" src="//www.youtube.com/embed/R2FIr4I59ec?enablejsapi=1" id="ted_x" frameborder="0" allowfullscreen></iframe>

<h2 class="video-heading">TEDxColumbiaCollege <span>November 2012</span></h2>

I created this looping cello and guitar performance using Ableton Live. A rendition of the third movement of Seasonal, the looping technique was inspired by Andrew Bird. The looping begins at <a id="time4">1:17</a>.

<br>
<hr>
<br>

<iframe src="//www.youtube.com/embed/X9IWRm469jM?enablejsapi=1" width="560" height="315" id="varsity_show" frameborder="0" allowfullscreen></iframe>

<h2 class="video-heading">V118: The Corporate Core <span>May 2012</span></h2>

The <a href="http://www.wikipedia.org/wiki/Varsity_Show" target="blank">Varsity Show</a> is Columbia's oldest performing arts tradition, with composer-lyricist alumni including Rodgers, Hammerstein, Hart, Kitt, and Yorkey. In its 118th annual installment, our spring satire on the year's memorable moments attracted an audience of over 5,000. Solomon Hoffman and I devoted our sophomore springs co-composing the two-act score for 11 singers and a pit of 25 musicians. For plot information, visit <a href="http://www.thevarsityshow.com/v118/">our year's page</a>. My favorite songs begin at the following times:

<p><a id="time1">0:54</a> Another Epic Day!</p>
<p><a id="time2">43:36</a> Nothing But Love</p>
<p><a id="time3">57:55</a> Alma's Army</p>

<script type="text/javascript">
    var tag = document.createElement('script');
    tag.src = "https://www.youtube.com/iframe_api";
    var firstScriptTag = document.getElementsByTagName('script')[0];
    firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);
    var player, player2;
    function varsityShowReady() {
        document.querySelector("#time1").onclick = function() {
            player.seekTo(54);
        };
        document.querySelector("#time2").onclick = function() {
           player.seekTo(2616);
        };
        document.querySelector("#time3").onclick = function() {
            player.seekTo(3475);
        };
    }
    function tedXReady() {
        document.querySelector("#time4").onclick = function() {
            player2.seekTo(77);
        }
    }
    function onYouTubeIframeAPIReady() {
        player = new YT.Player(
            'varsity_show',
            {
                events: {
                    onReady: varsityShowReady
                }
            }
        );
        player2 = new YT.Player(
            'ted_x',
            {
                events: {
                    onReady: tedXReady
                }
            }
        );
    }
</script>
