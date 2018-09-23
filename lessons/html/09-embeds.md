# The truth about embedding a Tweet

**Tweets aren't easy to embed in an intuitive way. It's not your fault. You aren't crazy... the Twitter people are... but here's what you do:**

You copied and pasted the exact code that Twitter generated for you once you clicked the "Embed Tweet" option. You did everything correct, yet you discovered that the result does not look like the preview. You got the text, but not the styling.

```
<blockquote class="twitter-tweet" data-lang="en">
<p lang="en" dir="ltr">I got the <a href="https://twitter.com/amazonsmile?ref_src=twsrc%5Etfw">@AmazonSmile</a> prompt and chose Brooklyn&#39;s <a href="https://twitter.com/hashtag/500MenMakingADifference?src=hash&amp;ref_src=twsrc%5Etfw">#500MenMakingADifference</a>. Great charity. <a href="https://t.co/dPotEy5K6J">https://t.co/dPotEy5K6J</a> <a href="https://t.co/oNHv3bLOdY">https://t.co/oNHv3bLOdY</a></p>
&mdash; Malik Singleton (@MalikFromLA) <a href="https://twitter.com/MalikFromLA/status/692903343908327425?ref_src=twsrc%5Etfw">January 29, 2016</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
```

So how do you get the styling to render?

Look at the last part of the end of the embed code for the `<script>` tag and its `src` attribute. The `src` attribute expects a web address. The proper styling lives at this web address that is effectively a public stylesheet that's available for everyone to use -- some magic style file that works via JavaScript or something so they named it widgets.js -- but whatevs, that ain't important.

All you need to know is that the geniuses at Twitter output the web address ==incompletely== so the dern thing doesn't work! WAIT... WHAT? YES! HUH? OMG! So crazy! Whisky Tango Foxtrot! Sugar Honey Ice Tea!!!

### The URL protocol is missing!!!

*...what the heck does that mean?*

You need to add ==`https:`== so that the address is complete.

:::danger
**Here's the address that Twitter gives you:**
`//platform.twitter.com/widgets.js`
:::

:::	success
**Here's what it ought to be instead:**
`https://platform.twitter.com/widgets.js`
:::

Type in those six characters, save your HTML file and refresh it in your browser and it should finally work this time.

Did it work?

Great. You owe me a beer.


https://twitter.com/NYUHistory/status/913082618543042560

## Challenge
- test all of the attributes of the iframe tag
- embed the following: tweet, IG post, youtube video, soundcloud audio, google map, drive slides, 

