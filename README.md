# **The Science of the Siphon Slideshow**

This project is an interactive HTML slideshow created for the Jigyansa Club of IISER Berhampur for its annual outreach event, **STREAM**. The slideshow's purpose is to explain the scientific principle of the siphon in a simple, engaging format for a high school audience, bridging fundamental concepts with real-world applications.

## **Features**

* **Interactive Navigation:** Users can move between slides using "Next" and "Previous" buttons.  
* **Dynamic Content:** Each slide updates with a new title, image, and text.  
* **Smooth Animations:** Slides feature fade-in and slide-in animations for a modern feel.  
* **Responsive Design:** The layout adjusts to fit different screen sizes, from mobile phones to desktop computers.  
* **Easy to Edit:** All slide content is stored in a simple JavaScript array, making it easy to add, remove, or modify slides.

## **How to Use**

Simply download the index.html file and open it in any modern web browser. No external servers or complex setup is required.

## **Customization**

The slideshow is highly customizable. To change the content, open the index.html file in a text editor and edit the slides array in the \<script\> section.

Here is an example of a slide object:

{  
    title: 'The Magic of Water:',  
    subtitle: 'A Science Trick',  
    image: 'https://placehold.co/600x400/87CEEB/ffffff?text=The+Magic+of+Water',  
    text: 'How can water move from one bottle to another all by itself? In this presentation, we will explore the science behind this amazing trick\!'  
}

* **title:** The main heading for the slide.  
* **subtitle:** A smaller subheading.  
* **image:** The URL for the image you want to display on the slide. You can use your own images or placeholder services.  
* **text:** The main body text for the slide. Markdown can be used for simple formatting like **bold** text.

## **Credits**

* **Developed by:** Gaurav Powar
* **Developed for:** The Jigyansa Club of IISER Berhampur  
* **CSS Framework:** [Tailwind CSS](https://tailwindcss.com/)  
* **Placeholder Images:** [placehold.co](https://placehold.co/)
