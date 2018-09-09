# Hello GitHub Pages!

### Todo

<div style="display:flex;flex-flow:row wrap;">
  <div style="flex:1 1 auto;min-width:20em">

* Stuff
* More stuff
* Stuff 3
* Stuff 4

Paragraph

[Link MD](https://nrk.no)

<a id="demo" class="abo-linkbtn" href="https://nrk.no">Link HTML</a>

  </div>
  <div style="width:400px">
    <div id="picker-example" style="display:inline-block;border:30px solid currentColor;border-radius:100%;" ></div>
    <script src="https://unpkg.com/vanilla-picker"></script>
    <script>
        new Picker({
            parent: document.querySelector('#picker-example'),
            popup: false,
            color: 'dodgerblue',
            onChange: function(color) { this.settings.parent.style.color = color; },
        });
    </script>
  </div>
</div>


## Info

...
