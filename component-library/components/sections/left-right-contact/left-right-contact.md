  - _bookshop_name: sections/left-right-contact
    content:
      show_note: true
      id:
      display_social_icons: true
      heading: A contact block
      description: >-
        This is a simple yet powerful block to display not only your location by
        using OpenStreetMaps, but also any other contact details you wish to
        share with your customers.
      contact_details:
        - _type: Email
          text: 'Email address: mybusiness@business.com'
          hero_library_icon_name: envelope
        - _type: Phone
          text: 'Phone number: 312 325 326'
          hero_library_icon_name: phone
        - _type: Address
          text: 'Address: 1 Fake St, Faketown'
          hero_library_icon_name: map-pin
        - _type: Hours
          text: 'Opening hours: 9-5pm, Monday to Friday'
          hero_library_icon_name: clock
      map:
        _bookshop_name: simple/map
        latitude: -45.8715491
        longitude: 170.5130604
        zoom_level: 9
      buttons:
        - _bookshop_name: generic/button
          url: '#contact-form'
          open_in_new_tab: false
          text: Contact us
          variant: primary
          arrow: right
          onclick:
    styles:
      color_group: primary
      image_alignment: left