---
permalink: finalprojects.html
title: Archived Fall 2020 Student Projects using Thunkable App Builder
layout: defaults/page
narrow: true
images:
  - images/g1.png
  - images/g2.png
  - images/g3.png
  - images/g4.png
  - images/g5.png
  - images/g6.png
  - images/g7.png
captions:
  - by Eric Holm, Brendan Humphrey, Ryan Rafati, and Mohamed Al-Shizawi
  - by Isaac Bilsel, Rigel Brown, and Jack Palaian
  - by Kaj Boeri, Jack Brookshaw, and Ben Chapman
  - by Aidan McKernan, Kaitlyn Noether, and Alexandra Trotter
  - by Evan Fries, Maria Hayes-Navas, and Caitlyn Hollander
  - by Henry Mackay, Salah Mohammed, and Marcela Pineda
  - by Lucas Mah, Lily Samoyan, and Joachim Santiago 
linked_captions:
  - Group 1 - COVerify
  - Group 2 - Quarantine Quality
  - Group 3 - Quarantine Quality
  - Group 4 - Quarantine Quality
  - Group 5 - COVerify
  - Group 6 - Crowd Alert
  - Group 7 - Crowd Alert
links:
  - https://x.thunkable.com/projectPage/5fc94553b0c9b90011a373e0
  - https://x.thunkable.com/projectPage/5fc9457e8e5b21001263aeca
  - https://x.thunkable.com/projectPage/5fc9459da34a4a001313768a
  - https://x.thunkable.com/projectPage/5fc945be847af700129d845a
  - https://x.thunkable.com/projectPage/5fc945e4245f6000117b308d
  - https://x.thunkable.com/projectPage/5fc9460742f6870012dae060
  - https://x.thunkable.com/projectPage/5fc9462642f6870012dae087
---

Students were tasked with building a Thunkable app to <a href="{{ site.baseurl }}/files/thunkable_final.pdf" target="_blank">meet one of these specs</a>. Great work, everyone!

<hr>

<div>
    <div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
        <div class="carousel-inner">
            {% for img in page.images %}
                <div class="carousel-item {% if forloop.first %}active{% endif %}">
                    <div class="card mb-3">
                        <img src="{{ img }}" class="d-block w-100">
                        <div class="card-body bg-light">
                            <div class="card-text" style="text-align: center">
                                <a href="{{ page.links[forloop.index0] }}" target="_blank">{{ page.linked_captions[forloop.index0] }}</a>
                                <br>
                                {{ page.captions[forloop.index0] }}
                            </div>
                        </div>
                    </div>
                </div>
            {% endfor %}
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</div>

### Group Presentations
- <a href="{{ site.baseurl }}/files/g1_pres.pdf" target="_blank">Group 1's Presentation</a>
- <a href="{{ site.baseurl }}/files/g2_pres.pdf" target="_blank">Group 2's Presentation</a>
- <a href="{{ site.baseurl }}/files/g3_pres.pdf" target="_blank">Group 3's Presentation</a>
- <a href="{{ site.baseurl }}/files/g4_pres.pdf" target="_blank">Group 4's Presentation</a>
- <a href="{{ site.baseurl }}/files/g5_pres.pdf" target="_blank">Group 5's Presentation</a>
- <a href="{{ site.baseurl }}/files/g6_pres.pdf" target="_blank">Group 6's Presentation</a>
- <a href="{{ site.baseurl }}/files/g7_pres.pdf" target="_blank">Group 7's Presentation</a>