+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "400px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome :smile:"
  content = ""
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
  overlay_img = "background1.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Get Academic"
  cta_url = "https://sourcethemes.com/academic/"
  cta_icon_pack = "fas"
  cta_icon = "github"

[[item]]
  title = "Left"
  content = "I am left aligned :smile:"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Right"
  content = "I am right aligned :smile:"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++

{{% alert note %}}
This homepage section is an example of adding [elements](https://sourcethemes.com/academic/docs/writing-markdown-latex/) to the [*Blank* widget](https://sourcethemes.com/academic/docs/widgets/).

Backgrounds can be applied to any section. Here, the *background* option is set give a *color gradient*.

**To remove this section, delete `content/home/demo.md`.**
{{% /alert %}}
