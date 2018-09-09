# Hello GitHub Pages!

### Todo

<div style="width:300px;height:350px;float:right;">
  <style>
    #picker-example: { display: inline-block; border: 30px solid currentColor; border-radius: 100%; }
    .picker_wrapper: { position: absolute; }
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
