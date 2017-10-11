# mn-jq-slide
Simple jquery slider


* Prepare slider:

      <div class="mn-jq-slider" id="slider" data-timer="5000">
        <div class="mn-jq-chrome">
          <div class="mn-jq-prev"><i class="fa fa-fw fa-chevron-left"></i></div>
          <div class="mn-jq-next"><i class="fa fa-fw fa-chevron-right"></i></div>
          <div class="mn-jq-counter"></div>
          <div class="mn-jq-dots"></div>
        </div>
        <div class="mn-jq-slide" data-copy="&copy; 2017 Marco Montanari" data-img=""></div>
        <div class="mn-jq-slide" data-copy="&copy; 2017 Marco Montanari" data-img=""></div>
        <div class="mn-jq-slide" data-copy="&copy; 2017 Marco Montanari" data-img=""></div>
        <div class="mn-jq-slide" data-copy="&copy; 2017 Marco Montanari" data-img=""></div>
        <div class="mn-jq-slide" data-copy="&copy; 2017 Marco Montanari" data-img=""></div>
      </div>
      
* run slider in your JS.
  
      makeSlider("#slider");
  
