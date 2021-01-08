
# BBBS FV Deals for Bigs Map

This project is comprised of an interactive map which centers around the Fraser Valley and businesses which support Big Brothers Big Sisters of the Fraser Valley through our Deals for Bigs program and can be accessed [here](/Work/bbbs.html)
## Cartographic Considerations

### Colour Iconography

The map is designed within the Big Brothers Big Sisters national branding guidelines in mind. Since the main purpose of the map is to connect matches with activities to participate in, parks were one of the exclusive coloured polygons on the map. Parks also feature labels where possible, and their inclusion on the map promotes healthy lifestyles and connecting with the outdoors. 

The focus of the map is the deals themselves. This has two purposes. 

* Initially this stylization makes locations easy to find for matches. Icons are clearly displayed and clusters are a bright yellow as per branding guidelines. The geolocation feature builds on this, providing locations that are nearby and easily accessible. 
* Secondarily, they act as marketing for businesses. We appreciate the support we get from businesses and hope to promote them as much as possible. Future possibilities include differing icon sizes or 'preferred locations' which contribute more towards fundraising goals. 

For the future an alternative map could be included for major donors. This could be included on the BBBS website and incentivize larger donations due to marketing value.

### Interactivity

As mentioned earlier, a geolocation feature is included to assist with relating the user to what is nearby. Additionally, a popup was created which gives the deal location's phone number and the deal description, and the cursor changes upon hovering clickable objects to assist with usability. Zoom is also included. At this time mobile is not entirely supported but this could change in future iterations.

### Web Considerations

A notable addition is the side menu which allows for further interactivity with the organization. Most notably is the inclusion of a 'submit a deal' button which automatically composes an email to be sent to ED Corina Caroll with significant deal information. 

## Files Included

This repository contains the physical HTML file of the map, a GeoJSON file which can be edited easily on the geoJSON.io website, as well as font files which assist with branding


## Limitations
At this time some limitations exist and will be listed in point form, along with a difficulty of implementation
* Different icons per category of deal - low to moderate (Planned for further update)
* Filter of Categories of Deals - Low to moderate (Planned for further update)
* Turn by turn navigation to deals - Moderate
* Special event locations and times - Moderate to implement, Difficult to maintain without training
* Additional map layer which shows general sponsors at other capacities. Easy to moderate to implement, easy to maintain without training, time consuming
