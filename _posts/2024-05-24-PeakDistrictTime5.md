---
layout: base
title: "Chatsworth House"
date: 2024-05-24
categories: blog
tags: [UK]
---

## Chatsworth House is one of England’s most iconic stately homes, set within the breathtaking Derbyshire countryside of the Peak District. Home to the Cavendish family, Dukes of Devonshire, for over 500 years.
<a href="javascript:void(0);" onclick="showImage('/assets/images/ChatsworthHouse1.jpg', 'Chatsworth House 1')">
    <img src="/assets/images/thumbnails/ChatsworthHouse1_thumbnail.jpg" alt="ChatsworthHouse1" style="width: 100%; max-width: 100%; height: auto;">
</a>
<br>
<a href="javascript:void(0);" onclick="showImage('/assets/images/ChatsworthHouse2.jpg', 'Chatsworth House 2')">
    <img src="/assets/images/thumbnails/ChatsworthHouse2_thumbnail.jpg" alt="ChatsworthHouse2" style="width: 50%; max-width: 100%; height: auto;">
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
