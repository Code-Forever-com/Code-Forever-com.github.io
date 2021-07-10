---
layout: page
title: "Görev: Yer Altı"
permalink: /gorev-yer-alti/
---

<style>
      .embed-responsive{
                position: relative;
    display: block;
    width: 100%;
    padding: 0;
    overflow: hidden;
      }
      
      .embed-responsive-item{
          position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
      }
</style>

<div class="row">
      <img src="https://user-images.githubusercontent.com/59289764/125142891-8f57d300-e121-11eb-94d1-5d1570fb0162.png" class="w-100"/>
</div>

Robotik bilimi ve robotlar hayatımızın her noktasında yerini alırken insansız görevler için geliştirilen robotlara yoğun mesai harcanıyor. İnsansız robotların öncelikli hedefi insan canını korumak ve kurtarmak, bu nedenle arama-kurtarma, keşif gibi görevlerde yer alan robotlar için farklı platform çalışmaları sürüyor. Görev: Yer Altı’nın hizmet ettiği amaç ise yer altı koşullarında insanın fizikî varoluşuna ihtiyaç duymadan çeşitli görevleri tamamlayabilecek robot fikirlerinin keşfedilmesidir.
Bu amaç doğrultusunda “akıllı teknolojiler entegre çözümler” anlayışını benimseyen, 38 yıllık tecrübe sahibi HAVELSAN ile iş birliğimizin, yarışma kazanımlarını uluslararası boyuta taşımasını, aynı zamanda yerli ve milli teknolojilere katkıda bulunmasını diliyoruz.
Bir robotik kavramsal tasarım yarışması olan Görev: Yer Altı, belirtilen pist özelliklerine uygun ve görevleri tamamlayabilecek robot fikirlerinin, çözümler ve tasarılarla birlikte çevrimiçi ortamda sunulmasını kapsamaktadır. Bir proje gelişim raporu, bir final sunumu ve jüri değerlendirmesi ile sonuçlanacak yarışmada; içerikler, pist özellikleri, puanlama kriterleri, önemli tarihler ve ödüller yarışma dosyaları bölümünde verilmiştir.
HAVELSAN mühendisleri ve ODTÜ akademisyenlerinin jüri olarak yer alacağı bu yarışmada, robotik alanında çalışmalar gösteren insanlar ile bir araya gelme fırsatını ve büyük ödülleri kaçırmayın!

### Pist
<div class="embed-responsive embed-responsive-16by9">
<iframe class="embed-responsive-item" src="https://www.youtube.com/embed/14x37Z5qpXQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
      
### Jüriler

<div class="row">
{% for i in site.data.gorev_juri %}
      <div class="col-12 col-md-4 text-center">
        <img src="{{ i.image }}" class="d-block rounded-circle" style="width: 10rem;height: 10rem;margin: 0 auto;"/>
        <div style="margin: 1rem auto;font-size: large;font-weight: 500;">
          {{ i.name }}
        </div>
        <div style="margin: 1rem auto;">
          {{ i.label }}
        </div>
      </div>      
{% endfor %}
</div> 
