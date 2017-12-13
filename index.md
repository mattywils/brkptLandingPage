---
layout: default
---
<!-- Start Home Slider -->
<div id="slider">

    <!-- START REVOLUTION SLIDER 3.1 rev5 fullwidth mode -->
    <div class="fullwidthbanner-container">
        <div class="fullwidthbanner" >
            <ul>
                               
                <!-- Slide - Microsoft 365  -->
                <li data-transition="fade" data-slotamount="7" data-masterspeed="300" >
                    <!-- MAIN IMAGE -->
                    <img src="http://placehold.it/1920x500/f4f4f4/f4f4f4" data-fullwidthcentering="on" alt="microsoft-365"  data-bgfit="cover" data-bgposition="center center" data-bgrepeat="no-repeat">
                    
                    <!-- LAYER NR. 1 -->
                    <div class="tp-caption uppercase big_font_size boldest_font_weight dark_font_color"
                        data-x="center"
                        data-y="center"
                        data-speed="300"
                        data-start="1000"
                        data-easing="easeOutExpo"
                        ><span class="accent-color">Microsoft 365</span>
                    </div>
                    
                    <!-- LAYER NR. 4 -->
                    <div class="tp-caption"
                        data-x="center"
                        data-y="center"
                        data-hoffset="84"
                        data-speed="600"
                        data-start="1000"
                        data-easing="easeOutExpo"
                        ><a href="#" class="btn-system btn-medium">More Info</a> 
                    </div>
                    
                </li>
                
            </ul>
            <div class="tp-bannertimer" style="visibility:hidden;"></div>
        </div>
    </div>
    
    <!-- THE SCRIPT INITIALISATION -->
    <!-- LOOK THE DOCUMENTATION FOR MORE INFORMATIONS -->
    <script type="text/javascript">
        var revapi;
        jQuery(document).ready(function() {
            revapi = jQuery('.fullwidthbanner').revolution({
                
                delay:9000,
                startwidth:1140,
                startheight:450,
                hideThumbs:200,
                
                thumbWidth:100,
                thumbHeight:50,
                thumbAmount:3,
                
                navigationType:"none",
                navigationArrows:"solo",
                navigationStyle:"round",
                
                touchenabled:"on",
                onHoverStop:"on",
                
                navigationHAlign:"center",
                navigationVAlign:"bottom",
                navigationHOffset:0,
                navigationVOffset:20,

                soloArrowLeftHalign:"left",
                soloArrowLeftValign:"center",
                soloArrowLeftHOffset:20,
                soloArrowLeftVOffset:0,

                soloArrowRightHalign:"right",
                soloArrowRightValign:"center",
                soloArrowRightHOffset:20,
                soloArrowRightVOffset:0,
                        
                shadow:0,
                fullWidth:"on",
                fullScreen:"off",
                lazyLoad:"on",

                stopLoop:"off",
                stopAfterLoops:-1,
                stopAtSlide:-1,

                shuffle:"off",
                
                hideSliderAtLimit:0,
                hideCaptionAtLimit:0,
                hideAllCaptionAtLilmit:0,
                startWithSlide:0,	
            });
        });
    </script>
            
</div>
<!-- End Home Slider -->