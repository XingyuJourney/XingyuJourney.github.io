---
layout: base
title: "Peak District Part 3"
date: 2024-03-04
categories: blog
tags: [UK]
---

# Chesterfield

## Parish Church
### Church with spiral angle
<a href="javascript:void(0);" onclick="showImage('/assets/images/ChesterfieldChurch.jpg', 'Parish Church')">
    <img src="/assets/images/thumbnails/ChesterfieldChurch_thumbnail.jpg" alt="ChesterfieldChurch" style="width: 50%; max-width: 100%; height: auto;">
</a>

# Baslow

## Gardom's Edge
### Nice looking stone piles and a relaxing trail
<a href="javascript:void(0);" onclick="showImage('/assets/images/GardomEdge1.jpg', 'Gardom\'s Edge 1')">
    <img src="/assets/images/thumbnails/GardomEdge1_thumbnail.jpg" alt="GardomEdge1" style="width: 50%; max-width: 100%; height: auto;">
</a>
<br>
<a href="javascript:void(0);" onclick="showImage('/assets/images/GardomEdge2.jpg', 'Gardom\'s Edge 2')">
    <img src="/assets/images/thumbnails/GardomEdge2_thumbnail.jpg" alt="GardomEdge2" style="width: 100%; max-width: 100%; height: auto;">
</a>

## Eagle Stone
### A giant stone
<a href="javascript:void(0);" onclick="showImage('/assets/images/EagleStone.jpg', 'Eagle Stone')">
    <img src="/assets/images/thumbnails/EagleStone_thumbnail.jpg" alt="EagleStone" style="width: 50%; max-width: 100%; height: auto;">
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
