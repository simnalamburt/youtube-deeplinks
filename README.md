youtube-deeplinks
========
### Youtube

- [Open Youtube root page](vnd.youtube://)
- [Watch video with longform player](vnd.youtube://GLs61zYhmlc)
- [Watch video with longform player (alternative links)](vnd.youtube://watch?v=GLs61zYhmlc)
- [Watch live stream](vnd.youtube://live/tNkZsRW7h2c)
- [Watch video with shortform player](vnd.youtube://shorts/GLs61zYhmlc)
- [Shorts section](vnd.youtube://shorts)
- [Shorts BGM page](vnd.youtube://source/szeZX1hgG0o/shorts)
- [Subscriptions](vnd.youtube://feed/subscriptions)
- [Watch playlist](vnd.youtube://playlist?list=PLwS9SkJJ-OoucP6uRi0GPXXbJ3pphQPX2)
- [Search](vnd.youtube://results?q=search%20query)
- [Channel (Channel ID)](vnd.youtube://channel/UCsJ6RuBiTVWRX156FVbeaGg)
- [Channel (username)](vnd.youtube://user/savethechildrenkr)
- [My channel](vnd.youtube://profile)
- ...

<!-- 
If you replace the "https://www.youtube.com/" part
of a web URL with "vnd.youtube://", it will usually work.
-->

### Youtube Music

- [Open Youtube Music root page](vnd.youtube.music://)
- [Listen to a song](vnd.youtube.music://qbgqlSWTt2o)
- [Search](vnd.youtube.music://search?q=everybody+wants+to+rule+the+world)
- ...

### Test random deeplinks

<input id=input value="vnd.youtube://shorts" placeholder="Type your deeplink in here">

Link: <a id=link></a>

<script type=module>
const sync = _ => link.href = link.innerText = input.value
sync()
input.addEventListener('input', sync)
</script>
