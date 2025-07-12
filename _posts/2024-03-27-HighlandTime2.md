---
layout: base
title: "Around Fort William"
date: 2024-03-27
categories: blog
tags: [UK]
---
## Loch Linnhe
### A loch located on the west coast of Scotland. Loch Linnhe is part of the Grand Canyon and the only lake in the Grand Canyon that is actually part of the ocean.

### It is rumored that an unknown marine creature called "Linnhe" lives here. (Why does it feel similar to the legend of the Loch Ness Monster)
<a href="javascript:void(0);" onclick="showImage('/assets/images/LochLinnhe.jpg', 'Loch Linnhe')">
    <img src="/assets/images/thumbnails/LochLinnhe_thumbnail.jpg" alt="LochLinnhe" style="width: 100%; max-width: 100%; height: auto;">
</a>

## Fort William

### Located in the West Highlands, the town is described as the Outdoor Capital of the UK. I can see the nearby mountains from the town.

<a href="javascript:void(0);" onclick="showImage('/assets/images/NevisRangeFromFT.jpg', 'Nevis Range from Fort William')">
    <img src="/assets/images/thumbnails/NevisRangeFromFT_thumbnail.jpg" alt="NevisRangeFromFT" style="width: 100%; max-width: 100%; height: auto;">
</a>
<br>
<a href="javascript:void(0);" onclick="showImage('/assets/images/FortWilliam.jpg', 'Fort William')">
    <img src="/assets/images/thumbnails/FortWilliam_thumbnail.jpg" alt="FortWilliam" style="width: 50%; max-width: 100%; height: auto;">
</a>

## Corran
### A former fishing village
<a href="javascript:void(0);" onclick="showImage('/assets/images/Corran.jpg', 'Corran')">
    <img src="/assets/images/thumbnails/Corran_thumbnail.jpg" alt="Corran" style="width: 100%; max-width: 100%; height: auto;">
</a>

## Lower Falls
### A waterfall in Glen Nevis
<a href="javascript:void(0);" onclick="showImage('/assets/images/LowerFalls.jpg', 'Lower Falls')">
    <img src="/assets/images/thumbnails/LowerFalls_thumbnail.jpg" alt="LowerFalls" style="width: 50%; max-width: 100%; height: auto;">
</a>

<script>
function showImage(src, alt) {
    var popup = document.getElementById('image-popup');
    var popupImage = document.getElementById('popup-image');

    popupImage.src = src;
    popupImage.alt = alt;
    popup.style.display = 'flex';
}

function closeImagePopup() {
    var popup = document.getElementById('image-popup');
    popup.style.display = 'none';
}
</script>
