# UFO Sightings Website
## Overview
This website was built to share the UFO related article and UFO sighting dataset. This analysis utilized a wide variety of tools including HTML, JavaScript, and CSS. The resulting website allows users to interface with the website to filter the UFO sightings table by date, city, state, country, and shape.

## Results
### Filtering
The website will initially open with the table unfiltered, so all the data can be seen if you scroll down. This is shown in Figure 1.

![NoFilter.PNG](/static/images/NoFilter.PNG)

Figure 1. The unfiltered table as the webpage default.

Filters are applied by typing the desired value into one of the appropriate text boxes. When you're finished you can press "enter" or click out of the box. Figures 2 through 4 show multiple filters being applied and the changing results.

![SingleFilter.PNG](/static/images/SingleFilter.PNG)

Figure 2. A single filter, State = ca, is applied to the table.

![DoubleFilter.PNG](/static/images/DoubleFilter.PNG)

Figure 3. A second filter, Shape = light, is applied to the table.

![MultiFilter.PNG](/static/images/MultiFilter.PNG)

Figure 4. Four filters are applied to the table.

Note that the filters are case/format sensitive, so capitalized state abbreviations or typing out the month-day-year will eliminate all options. Additionally, filters can be removed by deleting the text in the Filter Search box.

### Returning to Normal
To return to the default page, select the "UFO Sightings" button in the top left corner of the webpage. This button also clears all the filters with one click. The button's location is highlighted in Figure 5.

![UFO_Sightings.PNG](/static/images/UFO_Sightings.PNG)

Figure 5. The "UFO Sightings" button is highlighted by the red box.

## Summary
There are a few drawbacks to the new website design, such as the image behind "The Truth is Out There" being stretched to an extreme, or the website not being properly optimized for mobile users. Further development of this website should certainly be improving on those two issues, but could also include an additional filter for duration or scraping the internet for newer articles on UFOs. Additional improvements could be adding a "Clear All Filters" button near the Filter Search and the dataset could also likely be improved or expanded using scraping tools. 
