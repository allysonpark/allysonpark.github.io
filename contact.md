# Let's get in touch!

I'm always open to job opportunities, feedback, and any old thing you might find interesting!

<form class="wj-contact" action="https://formspree.io/{{site.email}}" method="POST">
    <input type="text" name="email" placeholder="Email Address">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="<REDIRECTION LINK> ">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>

<style>
form.wj-contact input[type="text"], form.wj-contact textarea[type="text"] {
    width: 60%;
    margin: auto
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: Helvetica, Arial, sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #5198DF;
    outline-color: #5198DF;
    border-width: 1px;
    border-radius: 10px;
    transition: box-shadow .2s ease;
}

form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    font: Helvetica, Arial;
    background-color: #2e83e6;
    border-radius: 3px;
    padding: 0.5em;
    margin: 1.0em 0 0 0;
    border: 1px solid transparent;
    height: auto;
}
</style>
