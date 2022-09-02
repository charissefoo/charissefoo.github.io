---
title: "The Island Lodge"
date: 2022-08-01
featureImage: images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-01-thumbnail.jpg
postImage: images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-01.jpg
shortDescription: Optimising the hotel booking process on mobile
tags: UX Design, UX Research
categories: project
---

service:
client: Academic
shortDescription: Optimising the hotel booking process on mobile
challenge: To ensure a smooth booking process on a new hotel's mobile website
solution: A mobile website designed through in-depth user research and competitive benchmarking

### Try it out for yourself

Try out the interactive prototype here, booking a room for 2 adults, from 15-18 July.

<!-- {{< figma "https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FIMfNWbAtt7nOLjwAldt1iz%2FIsland-Lodge-Hotel-Booking%3Fnode-id%3D92%253A5209%26scaling%3Dscale-down%26page-id%3D92%253A5112%26starting-point-node-id%3D92%253A5209" >}} -->

_A note on prototype limitations: please choose the dates of your stay before adding guests. Please choose the **Dolphin Deluxe Room,** the **Flexible Rate** payment option, and add the **Romance Under The Stars** additional package. Enjoy!_

### Overview

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-03.jpg" >}}

As part of my [Professional Diploma in UX Design](https://www.credential.net/358581c5-0f90-41d7-9301-82ff6f7b1d3e#gs.9pjyb3), I designed a mobile website for a hotel, The Island Lodge, focusing on the hotel booking process.

The Island Lodge is a proposed luxury beachfront resort located on St John's Island, Singapore. Imagined as a consolidation and redevelopment of the [four existing campsites](https://www.sla.gov.sg/state-land-n-property/management-of-state-land-and-property/visiting-the-sla-managed-islands/st-johns-island) on the island (Eagle, Turtle, Dolphin, and Otter), The Island Lodge offers a premier island getaway right next to the country's most pristine beaches.

<!-- As St John's Island is also home to Singapore's marine observatory, guests can immerse themselves in educational biodiversity-related activities. St John's Island offers a quieter alternative to the touristic holiday island of Sentosa, and guests looking for a staycation will be sure to find themselves transported to a new world. -->

_For a more complete overview of the research process, please refer to the research case study._

### User Flow

This primary user flow targets users who have concluded their browsing: they know the dates and rooms they plan to book. Determining the screens, screen states, and user actions involved in the most straightforward hotel booking process was a necessary first step before sketching wireframes.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-04.jpg" >}}

Earlier usability tests revealed that users would first browse through the hotel website, before committing to making a hotel booking. These users first explored the different types of rooms and amenities offered, without bothering to enter any planned dates for travel. To smoothly connect the browsing and booking processes, it was important to enable room selection before date selection as a secondary user flow.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-05.jpg" >}}

Of course, both user flows merge at the end, and can transition into each other if the selected rooms or dates are not available.

### Wireframe Sketches

These sketches were a first stab at designing screens based on the primary user flows.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-06.jpg" >}}

### Medium-Fidelity Prototypes

#### Initial Wireframes

I then designed a medium-fidelity prototype for user testing. These initial wireframes focused on key interactions within the primary user flow, as well as layout and visual hierarchy.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-08.jpg" >}}

#### Usability Testing

Early user testing revealed that visual content was key: actual images made it a lot easier for users to interact with the prototype and understand the content that was on the site. All images used are freely usable and obtained from [Unsplash](https://unsplash.com/) or [Pexels](https://www.pexels.com/).

User feedback was extremely helpful in highlighting places where layout was confusing, as well as digital affordances that should have been stronger. While I had prioritised the ability to complete the hotel booking as a guest, without the need to sign up or sign in, user testing conveyed the desirability of a membership portal for easy retrival and management of their hotel reservations. Hence, I detailed more screens reflecting additional user flows, depending on whether guests sign up for a new account or sign in to their existing account. Finally, it was a useful reminder of the need for large tap targets on mobile, and a source of many refinements to content and copy.

#### Design Iterations

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-11.png" >}}

**Problem:** A user was confused as to whether the price and photo applied to the room above or the room below.  
**Response:** The price is now displayed after the room name, as the user expected. Clicking anywhere in the room title area will bring the user to the individual room page.

**Problem:** It did not make sense to allow a '0 Adult' or '0 Room' booking.  
**Response:** When the number of guests or rooms is at a minimum of 1, the '-' button disappears.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-12.png" >}}

**Problem:** Users were equally interested in the 'Sign In' or 'Sign Up' options as they were in the 'Continue as Guest' one. Not all requests need follow-up.  
**Response:** Buttons were standardised in size and alignment, allowing for greater visual consistency. The line about necessary follow-up was removed.

**Problem:** Making the 'Sign In' screen an overlay over the previous screen increased visual clutter. There was potential confusion regarding the grayed-out back button.  
**Response:** The 'Sign In' screen is its own screen, and the page title and back button behave consistently across all screens.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-13.png" >}}

**Problem:** A summary of the booking details should be presented legibly, with details such as a price breakdown and reservation number.  
**Response:** More information was added and differentiated through visual hierarchy.

#### Improved Wireframes

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-09.jpg" >}}

### Visual Design

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-14.jpg" >}}

Since _The Island Lodge_ is a high-end beach resort, I went for warm earthy tones, a primarily dark, muted palette, and serif headings to convey a sense of timeless tropical luxury.

In this style guide for typography and colour, the dark primary green evokes lush tropical vegetation. The light colours are used for pages with specific microtasks, such as date selection, before the user returns to the darker 'home' colour palette.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-15.jpg" >}}

Knowing that yellow and green are a common set of confusion colours when it comes to colour blindness, I [tested](https://davidmathlogic.com/colorblind) the colour scheme for accessibility to people with colour blindness and made adjustments.
{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-16.jpg" >}}

### High Fidelity Prototype

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-10.jpg" >}}

These wirefames are the basis for the high fidelity prototype shown at the start. Besides improvements to copy and content, I designed additional screens to facilitate the secondary user flow where room selection occurs before date selection. Screens for error states are also included.

#### Design Iterations

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-17.png" >}}
As price transparency is very important to users, and there is a lot of information presented, I expanded the price breakdown screen from a modal dropdown to a separate page.

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-18.png" >}}

Similarly, I split the final success screen into two, to properly congratulate the user for completing the booking process with a splash image, and present the all-important booking details on a separate page. The 'Back to Home' button was also replaced with the more useful functions of editing the reservation or sharing the trip with friends and family.

### Design Annotations

{{< figure width="100%" src="/images/portfolio/island-lodge/charisse-foo-island-lodge-hotel-booking-19.jpg" >}}

To wrap up the design process, I produced these design annotations as handover documentation for developers to build the website accurately. The full 18-page document can be found [here](https://drive.google.com/file/d/1ZkRj5t5BSqYcLx8gPDEsAxVvdqbTjg45/view?usp=sharing).

### Design Feedback

"The prototype functions very well, it was easy to get through, easy to understand and very pleasant to look at."

### Further Exploration

#### Next Steps

As this was an academic project, a significant next step would be to integrate real-life hotel information, which often has a much higher level of complexity: many more details regarding payment, hotel policies, terms and conditions, health and security regulations, just to name a few. Working with a client with an existing repository of information to be presented would be a very different challenge, adding complexity to the design process.

Since I chose to focus on a mobile website, a separate desktop version would also have to be designed.

To further expand the scope of this project, I'd integrate this particular hotel into a larger hotel group, which manages several hotels across different locations. This is often the case with large hotel brands such as Four Seasons or Shangri-La. Each hotel would have its own identity, but be linked to the larger brand ecosystem. I'd expect this to make the booking process more exploratory and complex, with greater importance placed on brand loyalty and membership privileges.

#### Learning Points

Going through the entire UX process from research to analysis to design was highly enriching and educational. I especially appreciated the insights gained through usability testing - nothing challenges or validates a design as much as seeing someone completely unfamiliar with it interact with it for the first time.

Technically, I thoroughly enjoyed learning Figma from scratch through this project, and enjoyed exploring Miro and Whimsical as well. I'd like to delve deeper into user interface design by establishing a grid system for pixel-perfect designs, and visual design by developing a strong brand identity.
