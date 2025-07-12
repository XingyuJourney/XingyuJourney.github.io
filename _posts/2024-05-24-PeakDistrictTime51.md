---
layout: base
title: "Edensor: Second Time"
date: 2024-05-24
categories: blog
tags: [UK]
---

## Front of the villiage
<a href="javascript:void(0);" onclick="showImage('/assets/images/Edensor1.jpg', 'Edensor 1')">
    <img src="/assets/images/thumbnails/Edensor1_thumbnail.jpg" alt="Edensor1" style="width: 100%; max-width: 100%; height: auto;">
</a>

## On the road to Edensor from Bakewell, I take two pictures.
<a href="javascript:void(0);" onclick="showImage('/assets/images/Bakewell1.jpg', 'Bakewell 1')">
    <img src="/assets/images/thumbnails/Bakewell1_thumbnail.jpg" alt="Bakewell1" style="width: 50%; max-width: 100%; height: auto;">
</a>

## This tree again.
<a href="javascript:void(0);" onclick="showImage('/assets/images/EdensorTree2.jpg', 'Edensor Tree 2')">
    <img src="/assets/images/thumbnails/EdensorTree2_thumbnail.jpg" alt="EdensorTree2" style="width: 50%; max-width: 100%; height: auto;">
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
