---
layout: post
title: jQuery Timer Test
---

<!-- Valid global date and time string -->
<div><time>2018-12-08T17:47:00+0800</time></div><!-- Paris (winter) -->
<div><time>2018-12-08T08:47:00-0800</time></div><!-- California -->
<div><time>2018-12-08T16:47:00+0000</time></div><!-- UTC -->

<!-- Human readable duration -->
<h1 class="alt-1">24h00m59s</h1>
<h1 class="alt-1">4h 18m 3s</h1>
<h1 class="alt-1">00:01</h1>

<!-- Valid time string -->
<div class="alt-2">12:30:39.929</div>
<!-- Valid duration string -->
<div class="alt-2">P2DT20H00M10S</div>
<!-- Python datetime.timedelta str output -->
<!-- print datetime.timedelta(days=600, hours=3, minutes=59, seconds=12) -->
<div class="alt-2">600 days, 3:59:12</div>

<h2>Test1</h2>
<time datetime="2018-01-05T17:43:00+0900">Friday, December 13th, 2013 5:43pm</time>

<h2>Test2</h2>
<time datetime="2018-12-20T17:47:00+0100">December 20, 2018 at 17:47 UTC+1 (Paris Winter)</time>

<h2>Test3</h2>
<time class="countdown" datetime="P12DT05H16M22S">
    <span class="item item-dd">
        <span class="dd"></span>
        <span class="label label-dd">days</span>
    </span>
    <span class="separator separator-dd">,</span>
    <span class="item item-hh">
        <span class="hh-1"></span>
        <span class="hh-2"></span>
        <span class="label label-hh">hours</span>
    </span>
    <span class="separator">:</span>
    <span class="item item-mm">
        <span class="mm-1"></span>
        <span class="mm-2"></span>
        <span class="label label-mm">minutes</span>
    </span>
    <span class="separator">:</span>
    <span class="item item-ss">
        <span class="ss-1"></span>
        <span class="ss-2"></span>
        <span class="label label-ss">seconds</span>
    </span>
</time>