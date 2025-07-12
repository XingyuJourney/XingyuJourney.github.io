---
layout: base
title: "Izu Peninsula"
date: 2024-07-09
categories: blog
tags: [Japan]
---

## Jogasaki Coast
### A famous coastline attraction in the eastern part of Izu Peninsula
<a href="javascript:void(0);" onclick="showImage('/assets/images/城ヶ崎海岸1.jpg', '城ヶ崎海岸')">
    <img src="/assets/images/thumbnails/城ヶ崎海岸1_thumbnail.jpg" alt="城ヶ崎海岸1" style="width: 50%; max-width: 100%; height: auto;">
</a>

<br>

<a href="javascript:void(0);" onclick="showImage('/assets/images/城ヶ崎海岸2.jpg', '城ヶ崎海岸')">
    <img src="/assets/images/thumbnails/城ヶ崎海岸2_thumbnail.jpg" alt="城ヶ崎海岸2" style="width: 50%; max-width: 100%; height: auto;">
</a>

## Mount Fuji From Far
### Symmetrical conical volcano
<a href="javascript:void(0);" onclick="showImage('/assets/images/MtFuji1.jpg', 'MtFuji')">
    <img src="/assets/images/thumbnails/MtFuji1_thumbnail.jpg" alt="MtFuji1" style="width: 50%; max-width: 100%; height: auto;">
</a>

## Izu Nagaoka
### Chitosebashiteigaichi Park
<a href="javascript:void(0);" onclick="showImage('/assets/images/伊豆長岡.jpg', '伊豆長岡')">
    <img src="/assets/images/thumbnails/伊豆長岡_thumbnail.jpg" alt="伊豆長岡" style="width: 50%; max-width: 100%; height: auto;">
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