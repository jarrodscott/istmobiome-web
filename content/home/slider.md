---
# Slider widget.
active: true  # Activate this widget? true/false
headless: true  # This file represents a page section.

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height: 250px

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Slides.
# Duplicate an block to add more slides.

item:
- title: The Istmobiome Project
  align: center # Choose `center`, `left`, or `right`.
  content: a microbial tale told in two oceans
  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color: '#1f4e74FF' # An HTML color value.
  overlay_filter: 0.0 # Darken the image. Value in range 0-1.
  overlay_img: '' # Image path relative to your `media/` folder.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  #cta_label: Get Academic
  #cta_url: https://sourcethemes.com/academic/
  #cta_icon_pack: fas
  #cta_icon: graduation-cap  
- title: The Isthmus of Panama Changed the World...
  align: center # Choose `center`, `left`, or `right`.
  content: Three million years ago an experiment began
  overlay_color: '#1f4e74FF'
  overlay_filter: 0.0
  overlay_img: ''
- title: '...on Land...'
  align: right # Choose `center`, `left`, or `right`.
  content: it connected two continents
  overlay_color: '#333'
  overlay_filter: 0.0
  overlay_img: site_banner/land.jpg
- title: '...in the Sea.'
  align: right # Choose `center`, `left`, or `right`.
  content: 'it divided one ocean. '
  overlay_color: '#333'
  overlay_filter: 0.3
  overlay_img: site_banner/sea.jpg
- title: ''
  align: center # Choose `center`, `left`, or `right`.
  content: Learn more about this website & the grant that supports the work---*Divergence
    of Marine Symbiosis After the Rise of the Isthmus of Panama*.
  cta_icon: info
  cta_icon_pack: fas
  cta_label: More Information
  cta_url: about/
  overlay_color: '#1f4e74FF'
  overlay_filter: 0.0
  overlay_img: ''
weight: 10 # Order that this section will appear.
widget: slider  # See https://sourcethemes.com/academic/docs/page-builder/
---
