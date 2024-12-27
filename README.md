# P3_Portfolio
My 339 Portfolio


<!-- This is the AI citation for the typing and scrolling animation
Prompt: add an animation that when the page loads the intro should almost be typed into the screen

Answer:@keyframes typing {
    from {
        width: 0;
    }
    to {
        width: 100%;
    }
}

@keyframes blink-caret {
    from, to {
        border-right-color: transparent;
    }
    50% {
        border-right-color: #1D54B2;
    }
}

.baseer-para {
    font-size: 4rem;
    max-width: 37.5rem;
    color: #1D54B2;
    margin: 0;
    position: relative;
    z-index: 1;
    border-right: 0.15rem solid #1D54B2;
    white-space: nowrap;
    overflow: hidden;
    width: 0; /* Start with width 0 to animate */
    animation: typing 3s steps(30, end), blink-caret 0.75s step-end infinite;
}

Prompt:With Featured Projects have it so that the words scroll across the screen. as it hits the edge it comes back around the other side

Answer:@keyframes scroll {
    0% {
        transform: translateX(100%);
    }
    100% {
        transform: translateX(-100%);
    }
}

.project-title {
    margin-top: 2rem;
    color: #1D54B2;
    font-size: 5rem;
    white-space: nowrap; /* Prevent the text from wrapping to a new line */
    position: absolute; /* Position it to move across the screen */
    animation: scroll 15s linear infinite; /* Infinite loop, linear speed */
}

AI use to make the words vertical and create image animations

Prompt:Make chat-header vertical and align it to the left side of the image

Answer:.chat-header {
    color: black;
    font-size: 1.8rem;
    writing-mode: vertical-rl; /* Makes the text vertical */
    text-orientation: upright; /* Ensures the text is upright */
    margin-right: 1rem; /* Add spacing between the text and the image */
    align-self: flex-start; /* Aligns text to the start of the container */
}


Prompt:add a hover effect to the images that when hovered over they should darken a bbit

.projects img {
    width: 60%;
    height: auto;
    transition: filter 0.3s ease; /* Smooth transition for the hover effect */
}

.projects img:hover {
    filter: brightness(0.8); /* Darken the image slightly on hover */
}

 -->