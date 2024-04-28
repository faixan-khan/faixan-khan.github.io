<h2 id="news">News</h2>

<style>
  #scrollableDiv {
    min-height: 100px;
    height: 100px;
    overflow-y: hidden;
    opacity: 1;
    transition: height 0.5s ease-in-out, opacity 0.5s ease-in-out;
  }
</style>


<ul id="scrollableDiv" onmouseover="showScrollbar()" onmouseout="hideScrollbar()">
  <li><strong>[Apr. 2024]</strong> Co-organizing the <a href="https://cv4e.netlify.app/">ECCV24 Computer Vision For Ecology(CV4E)</a>.</li>
  <li><strong>[Apr. 2024]</strong> One paper (AI Art Neural Constellation) was accepted at CVPRW'24.</li>
  <li><strong>[Oct. 2023]</strong> Co-organizing the <a href="https://iccv23-wecia.github.io/">ICCV 2023 Workshop on Emotionally and Culturally Intelligent AI (WECIA)</a>.</li>
  <li><strong>[July. 2023]</strong> Two papers (FishNet, HRS-Bench) were accepted at ICCV’23.</li>
  <li><strong>[Jun. 2023]</strong> Started my internship at <a href="https://www.cvut.cz/en">CTU,Prague</a> with <a href='https://cmp.felk.cvut.cz/~toliageo/'>Pr. Giorgos Tolias</a>.</li>
  <li><strong>[Sep. 2022]</strong>One paper(HR-Talking Face) was accepted at WACV'23.</li>
  <li><strong>[Mar. 2022]</strong> One paper(Artemis 2.0) was accepted at CVPR'22.</li>
  <li><strong>[Dec. 2021]</strong> One paper(Intelligent Video Editing) was accepted at ICVGIP as an Oral.</li>
</ul>

<p></p>
<script>
  function showScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = div.scrollHeight + 'px';
    div.style.opacity = 1;
  }
  function hideScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = '100px';
    div.style.opacity = 1;
  }
</script>