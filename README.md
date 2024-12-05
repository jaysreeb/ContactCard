# ContactCard
This is a simple yet elegant Contact Card built using HTML and CSS, demonstrating the modern glassmorphism design trend. The card features a flip animation, allowing users to view details on the back and front with a smooth transition.

**Features**
Glassmorphism Design:
                    1. A frosted-glass appearance with transparency and blur effects.
                    2. Clean, modern, and visually appealing design.
Card Flip Animation:
                    1. Hover or click to flip the card and view content on the reverse side.
                    2. Smooth transitions.
                    3. Responsive layout.

Technologies Used
                    HTML: For the structure of the contact card.
                    CSS: For styling, animations, and glassmorphism effects.

The project consists of two main files:
                    index.html: Contains the structure of the contact card.
                    styles.css: Includes the glassmorphism effects and flip animations.  
**Key Sections in Code**
**Glassmorphism Effect**
Implemented using the following CSS properties:
                                      backdrop-filter: blur(15px)
                                      box-shadow: 0 0 80px rgba(0, 0, 0, 0.25)
**Flip Animation:**
                                Achieved using transform and perspective 
                                transform-style: preserve-3d;
                                transform: rotateY(180deg);
                                transition: transform 0.8s;
