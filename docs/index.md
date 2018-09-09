# Hello GitHub Pages!

### Todo

<div id="example-container">
    <style>
        #example-container { width:300px;height:330px;float:right; }
        #picker-example { display: inline-block; border: 30px solid currentColor; border-radius: 100%; }
        .picker_wrapper { position: absolute; }
        @media(max-width: 600px) {
            #example-container { float:none; }
        }
    </style>
    <div id="picker-example"></div>
    <script src="https://unpkg.com/vanilla-picker"></script>
    <script>
        new Picker({
            parent: document.querySelector('#picker-example'),
            popup: false,
            color: 'dodgerblue',
            onChange: function(color) { this.settings.parent.style.color = color.rgbaString; },
        });
    </script>
</div>

* Stuff
* More stuff
* Stuff 3
* Stuff 4

Paragraph

[Link MD](https://nrk.no)

<a id="demo" class="abo-linkbtn" href="https://nrk.no">Link HTML</a>


## Info

...
