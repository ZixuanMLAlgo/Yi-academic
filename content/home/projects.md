+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Machine Learning"
  #   tag = "Machine Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  

 
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
  Projects:
  
  * Bosch Intelligent Glove(2018): Responsible for part of gesture recognition algorithm development
  * Bosch E-bike Guardian Angel(2018)：Responsiblefor E-bike posture recognition algorithm development
  * Bosch PT Smart Helmet(2019): Responsible for behavior recognition algorithm development [(Tree ensemble)]
  * Bosch EAI PCB Anomaly Detection(2019): Responsible for PCB Cracks, Copper deformation detection and measuring (CV2)
  * Bosch AE Plant Visual Inspection on AOI  Machine(2019): Responsiblefor labeling, data processing, modeling and model optimization [**(ResNet + XGBoost)**]
  * Bosch Wujin Plant Visual Inspection(2019): Responsible for data augment, modeling  and model optimization [**(ResNet + XGBoost)**]
  * Bosch Braking System Anomaly Detection(2019-2020): Responsible for algorithm development to detect anomalies in braking maneuvers during validation tests on braking systems [**(Variantional autoencoder)**]
  * Bosch Autonomous Driving(2020-present):
  *   *Working on state of paving classification basedon Bosch Frontvideo Camera [**(CNN)**]
  *   *Working on lane detection in Bosch Driver Assistance System [**(UNet, runtime 20ms)**]
  """
