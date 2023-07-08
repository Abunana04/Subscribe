# Subscribe
mail verification

## Table of contents

  - The challenge
  - Screenshot
  - Links
  - My process
    - Built with
    - What I learned
  - Continued development
  - 
- Author


### The challenge

Users can be able to:

- Add their email and submit the form
- See a success message with their email after successfully submitting the form
- See form validation messages if:
  - The field is left empty
  - The email address is not formatted correctly
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](/design/desktop-access.jpg)
![](/design/desktop-access-hover.jpg)
![](/design/desktop-access-valid.jpg)
![](/design/desktop-invalid-reqst.jpg)
![](/design/desktop-alert.jpg)
![](/design/moble-acces.jpg)
![](/design/moble-access-valid.jpg)
![](/design/moble-access-invalid.jpg)
![](/design/mobile-alert.jpg)



## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Chrome
- CSS Grid
- Mobile-first workflow

### What I learned

I learn about "Email pattern" and "localStorage" in javaScript,not know about javaScript and CSS gradient.
it takes me a week to complete the task because of something that comes i have to face them and return back to me friend Coding at last I successfuly complete it.
 
 code sample 
    use of localStroge code
    - page1 
    use localStorage.setItem("textvalue",variable name);
    page2
    use
    localStorage.getItem("textvalue");

    CSS Gradients
    let say we want to style background using gradient
    Than 
       background :linear-gradient (to left #fe4 44%,#0f0 20%);

       Areas that I want to reinforce my knowledge on are
    -CSS3
    -javaScript

 Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```js
 const email = document.getElementById("email");

        email.addEventListener("input",()=>{
            const emailBox = document.querySelector(".emailBox");
            const emailAlert = document.querySelector(".emailAlert");
            const emailPattern = /[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{1,63}$/;

            if(email.value.match(emailPattern)){
                emailBox.classList.add("valid");
                emailBox.classList.remove("invalid");
                emailAlert.innerHTML = "Valid mail";
            localStorage.setItem("textvalue",emailBox.value);
                emailAlert.style.color ="#0f0";
                emailAlert.style.marginLeft= "240px";
```
### Continued development

CSS3
javaScript


## Author

- Github - [Abunana04](https://www.your-site.com)
- Frontend Mentor - [Abunana04](https://www.frontendmentor.io/profile/Abunana04)
- Twitter - [@Abu_Nana04](Twitter:Https//www.twitter.com/Abu_Nana04 )
- Facebook - [Abu Nana]( https://www.facebook.com/AbuNana.ABZ)  
