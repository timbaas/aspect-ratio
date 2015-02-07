# Easy Aspect Ratios with SCSS

### How to use:

##### Import the SCSS file:

    @import "aspect-ratio";

##### Adjust your HTML:

    <div class="aspect ratio-16-9">
      <div class="aspect-inner">
        Content
      </div>
    </div>

### Available ratios:

    .ratio-1-1    // 1:1
    .ratio-1-2    // 1:2
    .ratio-2-1    // 2:1
    .ratio-4-3    // 4:3
    .ratio-16-9   // 16:9

### Customize:

You can add ratios by editing the `$ratios` variable in the file, or specify your own `$ratios` variable before `@import`:

    $ratios: 3 4, 16 10;
